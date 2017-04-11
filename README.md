# Deprecated
For online modules (https://unpkg.com/) use this [link](https://github.com/vladimirpavk/Angular2-Skeleton-unpkg).

For locally installed modules use this [link](https://github.com/vladimirpavk/Angular2-Skeleton).

# Angular 2 application skeleton with lite server

Node, Lite-server, TypeScript, BrowserSync, Angular2 application skeleton

Provided for developing **Angular2** applications using **Typescript** served over **lite-server** server.

### Prerequisites
Must have node and npm installed

### How to use
Install node dependencies in your project root directory (this is where the 'package.json' file is located) using:
```sh
$ npm install
``` 
Start application with 
```sh
$ npm run start
```

Base **index.html** page and SystemJS configuration file **systemjs.config.js** are located in **./app** folder.

In your browser change the URL with **http://localhost:3333/app/index.html** and your Angular2 application will start.
Angular2 TypeScirpt application is located in **./app/ts** folder. The transpiled files are located in **./app/js** folder.
