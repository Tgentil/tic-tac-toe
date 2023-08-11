# TicTacToe (Jogo da Velha) em Angular
[![GitHub](https://img.shields.io/badge/Visite-Meu%20Perfil-0891B2?style=flat-square&logo=github)](https://github.com/Tgentil) [![Aplicação](https://img.shields.io/badge/Aplicação-TicTacToe-FF4500?style=flat-square)](https://tic-tac-toe-tg-ng.web.app/)

Este projeto foi desenvolvido como uma implementação do jogo da velha utilizando Angular, inspirado no tutorial:

 [![Vídeo Tutorial](https://img.shields.io/badge/Assista%20o%20tutorial-Youtube-FF0000?style=flat-square&logo=youtube)](https://www.youtube.com/watch?v=G0bBLvWXBvc&list=PL0vfts4VzfNjsTV_6i9a9iczMnthWqHzM&index=12)


O projeto original pode ser encontrado:

[![Fireship GitHub](https://img.shields.io/badge/Repositório%20Original-Fireship-FF4500?style=flat-square)](https://github.com/fireship-io/angular-tic-tac-toe)
<img src="https://avatars.githubusercontent.com/u/46283609?s=200&v=4" width="20">

### Aplicação

![Aplicação funcionando](src\assets\vids\app.gif )

## 🌟 Destaques

- **Progressive Web App (PWA)**: o jogo pode ser instalado e rodado offline em dispositivos compatíveis.
- **Responsividade**: O design foi aprimorado para oferecer uma experiência otimizada para dispositivos móveis.
- **Atualizações e Melhorias** em relação ao projeto original:
  - Prevenção de novos movimentos após determinar um vencedor.
  - Ocultação da mensagem indicando o jogador atual quando há um vencedor.
  - Otimização no foco de itens clicados.
  - Melhor compatibilidade com o kit UI do Nebular (foi necessário utilizar uma versão anterior do Angular para garantir essa compatibilidade).

### Lighthouse Report (Desktop)

![Lighthouse Desktop](src\assets\img\desktop.png)

### Lighthouse Report (Mobile)

![Lighthouse Mobile](src\assets\img\mobile.png)

### Instalação PWA pelo Google Chrome

![Instalação PWA](src\assets\img\download.png)

## 🚀 Começando

### Pré-requisitos

Este projeto foi gerado com [Angular CLI](https://github.com/angular/angular-cli) versão 15. 

### Servidor de Desenvolvimento

Execute `ng serve` para iniciar o servidor de desenvolvimento. Acesse `http://localhost:4200/`. O aplicativo irá recarregar automaticamente caso você modifique algum arquivo fonte.

### Gerando Componentes

Use `ng generate component component-name` para gerar um novo componente. Outros comandos disponíveis incluem `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Construindo o Projeto

Execute `ng build` para construir o projeto. Os artefatos de construção serão armazenados no diretório `dist/`.

### Testes Unitários

Execute `ng test` para realizar testes unitários através do [Karma](https://karma-runner.github.io).

### Testes End-to-End

Execute `ng e2e` para realizar testes end-to-end através da plataforma de sua escolha. Para utilizar este comando, primeiro é necessário adicionar um pacote que implemente as funcionalidades de teste end-to-end.

## 📖 Documentação Adicional

Para obter mais ajuda sobre o Angular CLI, use `ng help` ou consulte a [Referência de Comandos do Angular CLI](https://angular.io/cli).
