Overview
========

Materia is an easy-to-use backend to build all kinds of applications (mobile, web, gaming and more). Materia tooling aims to manage the entire development cycle for building enterprise class backends.

> ** Materia is in beta** and we need your help to track bugs. If you catch one of them, please, report it on [github.com/webshell/materia-designer/issues](https://github.com/webshell/materia-designer/issues).

## Materia Designer

Materia Designer is an easy to use yet powerful backend development UI. 

![Screenshot materia](/img/screen-entities.png)

It aims to handle all the lifecycle of developing an application from the development itself to the deployment.

Go to the [Download page](/) and grab the latest version for Mac OS X and Windows.

Materia Designer handles well every features of Materia Server.

## Materia Server

Materia Server is an opensource Node.js Framework built on top of [Express](http://expressjs.com/) which aims to build a web server with almost no code.

Most of the code are JSON and can be generated by Materia Designer or using the CLI. The code is highly extensible with your existing source code, NPM library and addons.

Out of the box, Materia Server allow you to:

* Configure a database connection (MySQL, PostgreSQL or SQLite)

* Define data structures (called entities) and data queries

* Synchronize your data structures with your connected database

* Build secure endpoints

* Git versionning

* Host your application anywhere

* Live edition of the production database

All of that described in a specified JSON format that you can generate easily from Materia Designer.

On top of that, you can define your own Javascript Database queries, Javascript endpoints (using Express Framework) and addons to extend what JSON can't define simply. You're not reinventing the wheel as you can access the full NPM ecosystem and use existing Materia Addons.

![Screenshot materia server](/img/lp-term-start.png)

Materia Server is free and opensource. The source code is available on [github.com/webshell/materia-server](https://github.com/webshell/materia-server).

You can install it using npm: `(sudo) npm install -g materia-server`

# Resources

* [Quickstart](/docs/quickstart) - Make a simple Todo application with Materia.

* [Guide](/docs/guide/install) - In-depth guide to use Materia.

* [Github Issues](https://github.com/webshell/materia-designer/issues) - Report issue and discuss about the future of Materia.