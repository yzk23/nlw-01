# :recycle: ECOLETA
[![runs with expo](https://img.shields.io/badge/Runs%20with%20Expo-000.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000)](https://expo.io/)

Prática desenvolvida na **Next Level Week 1.0** oferecido pela **[Rocketseat](https://www.rocketseat.com.br)**. A aplicação tem como finalidade cadastrar e visualizar pontos de coleta de reciclagem e seus respectivos materiais.

<br/>

## :computer: Tecnologias utilizadas

### API
* [Node.JS](https://nodejs.org/en/docs/)
* [Express](https://expressjs.com/)
* [Cors](https://github.com/expressjs/cors)
* [Knex](http://knexjs.org/)
* [SQLite](https://www.sqlite.org/index.html)
* [Multer](https://www.npmjs.com/package/multer)

### Web
* [ReactJS](https://reactjs.org/)
* [Leaflet](https://leafletjs.com/)
* [ReactDropzone](https://react-dropzone.js.org/)
* [Axios](https://github.com/axios/axios)

### Mobile
* [React Native](https://reactnative.dev/)
* [Expo](https://docs.expo.io/)
* [Axios](https://github.com/axios/axios)
* [Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)
* [Map View](https://docs.expo.io/versions/latest/sdk/map-view/)

<br/>

## Instalando dependências
A primeira etapa consiste na instalação das dependências do projeto:
```
$ npm install
```
Logo após isso, deve ser criada a estrutura do banco de dados executando suas *migrations* e logo após seus *seeds*:
### SQLite
``` bash
# dentro do diretório server
$ npm run nkex:migrate
$ npm run knex:seed
```

## Executando a aplicação

### API
Independemente de qual aplicação você deseja rodar, mobile ou web, o back-end deve estar rodando. 

Utilizando o [npm](https://www.npmjs.com/):
```bash
# dentro do diretório server
$ npm run dev
```
Caso utilize o [yarn](https://yarnpkg.com/) :
``` bash
# dentro do diretório server
$ yarn dev
```

### Web
Utilizando o [npm](https://www.npmjs.com/):
```bash
# dentro do diretório web
$ npm start
``` 
Com o [yarn](https://yarnpkg.com/) :
```bash
# dentro do diretório web
$ yarn start
``` 

### Mobile
```bash
# dentro do diretório mobile
$ npm start
```
Ou:
``` bash
# dentro do diretório mobile
$ expo start
```
