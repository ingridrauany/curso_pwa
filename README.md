# curso_pwa

## Curso PWA da TreinaWeb

### Configuração do ambiente

- Instalação do webpack

```
npm install -g webpack
```

- Instalação WebPack Dev Server

```
npm install -g webpack-dev-server
```

- Criação do packpage.json

```
npm init
```

- Instalação Webpack e Babel

```
npm install --save-dev babel-core babel-loader babel-preset-env webpack
``` 

- Instalação da biblioteca web-push

```
npm install --save web-push
```

### Configuração do webpack

- Criar e configurar o arquivo: `webpack.config.js` (indica o arquivo de entrada, o arquivo de saída, minificação do JavaScript com SourceMap e transpilação com o Babel)
- Iniciar webpack (empacota arquivos e minifica): 

```
webpack ou webpack-dev-server
```

- No dev será disponibilizado no servidor: [http://localhost:8080](http://localhost:8080).