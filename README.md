# Money Saver

The purpose of **Money Saver** application is to help to manage the everyday expenses.

## Prerequisites

* [**Git**](https://git-scm.com/) - distributed version control system designed to handle everything;
* [**Node.js**](https://nodejs.org/en/) - open-source, cross-platform, back-end JavaScript runtime environment;

### Notes

* No database server required at the moment, as data stored with help of [SQLite3](https://www.sqlite.org/index.html);
* [Memcached](https://memcached.org/) might be used to store client`s sessions but is not necessarily;

## Getting Started

To launch the application for the first time, you shall clone it to your PC:

```bash
git clone --recursive git@github.com:idenisovs/money-saver.git
```

That will get the latest production versions of [backend](https://github.com/idenisovs/money-saver-backend) and [frontend](https://github.com/idenisovs/money-saver-frontend) parts of application and their submodules too.

**Note**: Check the [backend](https://github.com/idenisovs/money-saver-backend/blob/master/README.md) (**first**) and [frontend](https://github.com/idenisovs/money-saver-frontend/blob/master/README.md) _README_ files for setup instructions and future steps.

## The structure

### Backend (server side)

The **backend** is typical [REST API](https://en.wikipedia.org/wiki/Representational_state_transfer) service driven by [**Node.js**](https://nodejs.org/en/) runtime and [**Express**](https://expressjs.com/) framework. It provides mainly the authentication and data manipulation / data storage functions.  

### Frontend (client side)

The **frontend** is a [Single Page Application](https://en.wikipedia.org/wiki/Single-page_application), made with lovely help of [**Angular**](https://angular.io/guide/what-is-angular) framework. It calls the REST API functions provided by backend and allow end users to view and change the data in friendly manner. 

**Please, note**: You can write your own frontend to use with backend of **Money Saver** applications.

### Shared submodule

[**Shared**](https://github.com/idenisovs/money-saver-shared) submodule contains the [TypeScript](https://www.typescriptlang.org/) objects. Those objects help to interchange the data between **backend** and **frontend** parts of application.

## The purpose and history of project

The author as a person, who believes in _learning by doing_ approach started this project in 2014 to gather the skills and knowledge about programming in [Node.js](https://nodejs.org/en/).

The first version of **frontend** was written by [Angular.js](https://angularjs.org/) and [Bootstrap](https://getbootstrap.com/), for the same purpose.

Later the [Angular.js](https://angularjs.org/) has been replaced by [Angular 2](https://angular.io/), therefore [TypeScript](https://www.typescriptlang.org/) was introduced. 

In the same time the frontend has been moved into separate repository, so **frontend** and **backend** parts of application has been splitted. 

In 2021 the backend has been moved to TypeScript too. 

## License

You have a right to fork it, study it, change it, share it, blame it and use it if you're brave enough.
