# ISKRA_02_ingenierowork

### React Scaffolding Step by Step

- Create React app with npx create-react-app my-app . (Change my-app to the name of your app, e.g. npx create-react-app emefa-mvp .
- In VSCode, in src folder, delete the App.test.js , serviceWorker.js ,setupTests.js and logo.svg files.
- In index.js , remove serviceWorker setup (lines 14-17), and the import from line 5.
- In App.css remove the default styling, but keep the file for if you will use some css styling later.
- In App.js , remove the logo import in line 2, and the header content in lines 8 - 21 (between the <header> tag).
- Change the functional component into class component, so you can add some state later on.

### Libraries Installed

- For the backend:

  - Bootstrap React: `npm install react-bootstrap bootstrap` (`https://react-bootstrap.github.io/getting-started/introduction`)
  - React Router: `npm install react-router-dom`
  - REACT - SVG: `npm i react-svg`
  - MDBReact: `npm i mdbreact`
  - MDBootstrap: `mdbootstrap`

- For the backend:
  - Express: `npx express-generator`
  - Mysql: `npm install mysql`
  - Nodemon: `npm install nodemon`
  - DotEnv: `npm install dotenv`
  - Axios: `npm i axios`

#### FALTA FER:

- Arreglar filtres MARCAR / DESMARCAR TODAS
- Arreglar NAVBAR logo resize SVG
- Arreglar SPONSORS logo resize SVG
- repassar responsive
- repassar disseny, imatges
- Styling CONTACTE + REGISTER + LOGIN
- Provar autenticació a REGISTER + LOGIN

- Acabar OFERTAS: Paginate: (`https://www.thatsoftwaredude.com/content/6125/how-to-paginate-through-a-collection-in-javascript`)
