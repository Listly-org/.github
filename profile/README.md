# Listly
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/Listly-org/.github/blob/main/profile/README.md)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/Listly-org/.github/blob/main/profile/README.pt-br.md)

### Listly is a mobile app that manages to-do lists. It was made as a partial requirement for obtaining a Bachelor's degree at [URI](https://www.uricer.edu.br/site/).

## About
Listly its basically an app that manages to-do lists. Due to the short development time, the app is basically a MVP. The user can register itself in the plataform, manage list groups, lists and list itens.

## Architecture
The base architecture of the system is presented as follows:
![image info](./profile/images/diagram-en.png)
* **Client** - Application client made with Flutter, the source code is in the [listly-app](https://github.com/Listly-org/listly-app) repository;
* **Server** - Application server made in Express, the source code is in the repository [listly-api](https://github.com/Listly-org/listly-api);
* **Database** - Application database in PostgreSQL;

## Repositories
* [**listly-app**](https://github.com/Listly-org/listly-app) - Front-end of the application made in Flutter;
* [**listly-api**](https://github.com/Listly-org/listly-api) - Back-end of the application made in Express;