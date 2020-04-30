<p align="center">Desafio realizado do curso GoStack da Rocketseat em 2020</blockquote>


<h3 align="center">
  Desafio 04: Conceitos do React Native
</h3>

<p align="center">
  <a href="#tools-ferramentas-utilizadas">Ferramentas utilizadas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#intro-instruções-para-execução-do-projeto">Instruções para execução do projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#desc-descrição">Descrição</a>
</p>

## :tools: Ferramentas utilizadas

Neste desafio foram utilizados as ferramentas: **[NodeJS](https://github.com/nodejs)**, **[Yarn](https://github.com/yarnpkg/yarn)**, **[React](https://github.com/facebook/react)** e **[React Native](https://github.com/facebook/react-native)**

Este projeto foi rodado no **Windows**, então todos os comandos são para este SO.

## :intro: Instruções para execução do projeto

Para a devida execução desta ferramenta é necessário estar rodando o backend e o frontend antes de executar o mobile.

O backend pode ser encontrado **[AQUI](https://github.com/Smpontelli/DesafioConceitosNode)**.

O frontend pode ser encontrado **[AQUI](https://github.com/Smpontelli/DesafioConceitosReact)**.

Deve-se clonar cada um dos repositórios, inclusive este. Em seguida, estando em cada uma das respectivas pastas, é necessário executar o comando `yarn` pelo terminal para instalar todas as dependências.

Caso a simulação for feita por um dispositivo físico, é necessário que o mesmo esteja conectado via USB. Em seguida digite o comando `adb devices` e verefique se tem algum dispositivo conectado.

Neste **[LINK](https://github.com/Smpontelli/DesafioConceitosReactNative/blob/master/src/services/api.js)**. é mostrado a **baseURL** na linha 4, com o "IP" que deve ser trocado para o ip da maquina do usuário.
O "IP" pode ser encontrado rodando o comando `ipconfig` dentro do terminal.

Em seguida, com o terminal na pasta do backend deve-se rodar o comando `yarn dev` e deixar rodando.

Com outro terminal, acesse a pasta do frontend para rodar co comando `yarn start` e deixe rodando.
Abrirá uma página no seu navegador.

Dentro de om outro termina aberto, acesse a pasta do mobile digite o comando `npx react-native run-android` e deixe rodando
Abrirá um aplicativo no seu mobile.

## :desc: Descrição

Esta ferramenta é para mostrar que ao adicionarmos uma nova informação dentro do navegador, é possível exibir e interagir com ela dentro do mobile, tudo isto utilizando o backend para fazer o interfaceamento entre eles.

Depois dos comandos executados então abrirá no navegador uma página com a url `http://localhost:3000/` nela clice no botão **Adicionar** para mostrar a frase: **Novo Repositorio** seguida de um numero de identificação e por um botão **Remover**

Depois de algum tempo, se tudo tiver dado certo deverá abrir no mobile um aplicativo, nesse aplicativo é possível ver a frase: **Novo Repositorio** seguida de um numero de identificação e por **NodeJS** escrito duas vezes dentro de uma caixa verde
seguido pelo **numero de curtidas** e em baixo um botão **curtir**. Ao clicar no botão **curtir** o numero de curtidas aumenta.

Para cada vez que for adicionado um repositório dentro do navegador, aparecerá um novo "cartão" com as mesmas informações citadas acima, mas com o numero de curtidas zerado.
