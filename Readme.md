<h1 align="center">
<br>
  <img src=".github/logo.svg" alt="Happy" />
  
  <p align="center">
    <b>Happy é uma plataforma para conectar instituições de cuidados infantis com pessoas interessadas em ajudar</b>
  </p>

  <div align="center" >
    <img src=".github/gif/web.gif"
    alt="demo-web" height="425">
    </div>
  
  <p align="center">
  <a href="#bookmark-about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#package-installation">Installation</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

</div>

## :bookmark: About

Esta e uma plataforma que foi desenvolvida durante a semana de aprendizado da rocketseat

<br>

## 🛠 Techs

- **Web**

  - [React](https://reactjs.org/)
  - [Typescript](https://www.typescriptlang.org/)
  - [Leaflet](https://leafletjs.com/)
  - [React Leaflet](https://react-leaflet.js.org/)
  - [Open Street Map](https://www.openstreetmap.org/) ou [Mapbox](https://www.mapbox.com/)
  - [Framer Motion](https://www.framer.com/motion/)

- **Backend**
  - [Nodejs](https://nodejs.org/en/)
  - [Express](https://expressjs.com/)
  - [Typeorm](https://typeorm.io/)
  - [Multer](https://github.com/expressjs/multer)
  - [Yup](https://github.com/jquense/yup)

<br>

## :package: Installation

### :heavy_check_mark: **Pré-requisitos**

E necessária apenas a instalação dos seguintes software

- **[Node.js](https://nodejs.org/en/)**
- **[Git](https://git-scm.com/)**
- **[NPM](https://www.npmjs.com/)** or **[Yarn](https://yarnpkg.com/)**
- **[Expo](https://expo.io/)**
- **[Expo App](https://play.google.com/store/apps/details?id=host.exp.exponent)**

<br>


### Para rodar a plataforma  🚀

#### Cloning

```ps
# Clone o repositório utilizando o git
$ git clone https://github.com/Brenovieira41/Happy1.0.git
```

### :arrow_forward: **Exutando**

- :package: API (Back-end)

```sh
  $ cd backend
  # Dependencies install.
  $ yarn # or npm install
  # Data base creation.
  $ yarn typeorm migration:run # or npm run typeorm migration:run
  # API start
  $ yarn dev # or npm run dev
```

- :computer: Site web

```sh
  $ cd web
  # Dependencies install.
  $ yarn # or npm install
  # Running web app
  $ yarn start # or npm start
```

- :cell: Aplicação mobile

```sh
  $ cd mobile
  # Entre na pasta mobile/src/services/api.ts
  # Altere a (baseURL) colocando o ip gerado pelo expo
  # Dependencies install.
  $ yarn # or npm install
  # Running mobile app
  $ yarn start # or npm start
```