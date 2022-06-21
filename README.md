## Vite.js
- Site - https://vitejs.dev/
- Github - https://github.com/vitejs/vite


### O QUE É O VITE.JS, VS REACT.
- O que é o Vite?

Vite é uma ferramenta de construção para front-end, ele provê uma 
ferramenta de criação muito mais rápida e opinativa pronta para uso.

## Vite.js

Vite é uma ferramenta de construção que foi inicialmente desenvolvida para Vue.js. Com a nova atualização, o Vite agora oferece suporte à maioria das estruturas da web.

O Vite fornece código-fonte em ESM nativo . As importações dinâmicas condicionais são processadas apenas quando usadas pela tela atual requer a importação. O navegador faz a tarefa de agrupar o código-fonte. O Vite só serve e transforma o código-fonte sob demanda, conforme solicitado pelo navegador.

- ESM nativo - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

## Tudo muito mais rápido

O Vite 2.0 vem com um tempo de construção mais rápido usando esbuild . esbuild é um bundler escrito em Go. É de 10 a 100 vezes mais rápido do que outros empacotadores.

Vite 2.0 usa esbuild para converter módulos CommonJS em ESM para dependências. De acordo com a nota de versão do Vite 2.0 s , usando esbuild em vez de Rollup leva a um grande aumento de desempenho no tempo de construção. Atualmente, esbuild é usado para dependências de pré-agrupamento, mas a equipe Vite está planejando mudar completamente para esbuild no futuro.



## Como criar um app com React usando Vite

#### Com yarn
- yarn create vite

#### Com npm
- npm init vite@latest

## Install

Instale as dependências apenas com npm ou yarn e está pronto seu projeto. Inicie seu servidor apenas com yarn dev.

Se você preferir você pode apontar diretamente o template que deseja usar e nome do seu projeto:


#### npm 6.x
- npm init vite@latest my-vue-app --template vue

#### npm 7+, extra double-dash is needed:
- npm init vite@latest my-vue-app -- --template vue

#### yarn
- yarn create vite my-vue-app --template vue


## Outras Soluções
- Snowpack - https://www.snowpack.dev/
- React Boilerplate - https://github.com/react-boilerplate/react-boilerplate
- Create Nextjs App - https://nextjs.org/learn/basics/create-nextjs-app
- Preact.js - https://preactjs.com/
 