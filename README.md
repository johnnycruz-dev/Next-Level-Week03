<div align="center">
    <img src="./images/NLW.jpg"/>
</div>

## Next Level Week#03 🚀️

### 💻 Sobre o Projeto

O Happy é uma aplicação que conecta pessoas à casas de acolhimento institucional para fazer o dia de muitas crianças mais feliz 💜

<div align="center">
    <img src="./images/Capa.png"/>
</div>

### 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [TypeScript](https://www.typescriptlang.org/)

### :zap: Executando o Projeto
#### Clonando o projeto
```sh
# Clone este repositório
$ git clone https://github.com/johnnycruz-dev/Next-Level-Week03.git

# Acesse a pasta do projeto no terminal/cmd
$ cd Next-Level-Week03
```
#### Iniciando a API
```sh
# Vá para a pasta backend
$ cd backend

# Instale as dependências
$ yarn
ou
$ npm install

# Rodando as migrations para o banco de dados
$ yarn typeorm migration:run
ou
$ npm run typeorm migration:run

# Execute a aplicação em modo de desenvolvimento
$ yarn dev:server
ou
$ npm run dev:server

# O servidor inciará na porta:3333 - acesse http://localhost:3333 

---
Obs: No arquivo "images_view.ts", alterar o ip na url -> para o ip da sua máquina
```

#### Iniciando o Frontend
```sh
# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ yarn
ou
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ yarn start
ou
$ npm run start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```
#### Iniciando o Mobile(Android)
```sh
# Vá para a pasta da aplicação Mobile
$ cd mobile

---
Obs: No arquivo "api.ts", alterar o ip na baseURL -> para o ip da sua máquina

# Instale as dependências
$ yarn
ou
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ yarn start
ou
$ npm run start
# Após rodar o comando acima, você será redirecionado para o "Metro Bundler"

# Caso for rodar em um dispositivo físico:
# Nessa tela terá um código um QR Code na parte inferior esquerda
# Agora no seu celular baixar o app do "Expo" na Google Play (link abaixo)
# Abra o Expo no seu celular e toque na opção Scan QR Code
# Escaneie o QR Code  e com isso o aplicativo será executado
---
Obs: Para funcionar tanto o celular quanto o computador devem estar conectados na mesma rede wi-fi.

# Caso for rodar em um emulador Android: (link abaixo)
# No "Metro Blunder" tem a opção "Run on Android device/emulator"
# Com isso o aplicativo será executado no emulador Android
```

#### Links Úteis
<a href="https://play.google.com/store/apps/details?id=host.exp.exponent">Expo</a>

<a href="https://react-native.rocketseat.dev/android/emulador">Emulador Android</a>

### Telas da aplicação:

-  Web:

<div align="center">
    <img src="./images/Web-Home.png"/>
    <img src="./images/Web-Mapa.png"/>
    <img src="./images/Web-Detalhes.png"/>
    <img src="./images/Web-Cadastro.png"/>
</div>

- Mobile

<div align="center">
    <img src="./images/Mobile-Home.png"/>
    <img src="./images/Mobile-Mapa.png"/>
    <img src="./images/Mobile-Mapa-Add.png"/>
    <img src="./images/Mobile-Detalhes.png"/>
    <img src="./images/Mobile-Cadastro.png"/>
</div>


