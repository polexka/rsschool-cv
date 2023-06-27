---
layout: cv
title: Polina Tsukanova's CV
---
# Polina Tsukanova

St. Petersburg

+79812242407 | pol1na-tsukanova@yandex.ru | discord: pol1chka | tg: polexka 

Github: [polexka](https://github.com/polexka)

## Education

`2020-2026` 

__Saint Petersburg Electrotechnical University__

Faculty of Computer Technology and Informatics

Information Security

`2022-2023` 

__Yandex.Practicum__

Web Development Department

## Skills

`Programming languages` 
JavaScript, C/C++

`Databases` 
MySQL, MongoDB

`Web-development` 
HTML, CSS, Figma, React.js

`Server development` 
Node.js, Express, Nginx

`The Internet Protocols` 
TCP/IP, HTTP, REST API, CORS

`Languages` 
Russian Native, English B1

## Code Example

```JavaScript
const duration = 3;
const anotherDuration = 5;
const declensions = ['минута', 'минуты', 'минут'];

function getNoun(number, word) {
  let n = number % 100;
  if (n >= 5 && n <= 20) {
    return word[2];
  }
  n %= 10;
  if (n === 1) {
    return word[0];
  }
  if (n >= 2 && n <= 4) {
    return word[1];
  }
  return word[2]
}

console.log(getNoun(duration, declensions));
// '3 минуты'
console.log(getNoun(anotherDuration, declensions));
// '5 минут'
```

## Experience

`Study project, 2022`

__Movie Searcher__

[Frontend GH](https://github.com/polexka/movies-explorer-frontend) | [Backend GH](https://github.com/polexka/movies-explorer-api)

Tasks:
- set up the infrastructure and create a server on Express;
- connect database, create API schemas and resource models;
- implemented logging, authentication and authorization on the server;
- deploy backend on Yandex Cloud;
- create components in React;
- describe the logic and layout of registration, login, profile editing, saved movies pages;
- implement asynchronous GET- and POST-requests to the API;
- develop authorized and unauthorized states, saving movies in the profile;
- received movies should be filtered on the client side.

Technologies: HTML, CSS, React, Express, MongoDB, NodeJS, API, Nginx, JWT, Postman


`Study project, 2022`

__Photo sharing social network__ 

[Github](https://github.com/polexka/react-mesto-api-full-gha)

Tasks: 
- create a server on Express;
- connect database, create API schemas and resource models;
- implemented logging, authentication and authorization on the server;
- deploy backend on Yandex Cloud;
- create React components;
- describe the logic and layout of the registration page, login page, homepage with pop-ups to edit the profile and upload image cards;
- implement asynchronous GET- and POST-requests to the API;
- elaborate authorized and unauthorized states, setting and removing likes from image cards.

Technologies: HTML, CSS, React, Express, MongoDB, NodeJS, API, Nginx, JWT, Postman


`Study project, 2022`

__Database design__

Tasks: 
- design the database, create API schemas and resource models;
- create a client to interact with the database.

Technologies: MySQL, PHPMyAdmin, C#


`Academic practice, 2022`

__Software functionality research and development of functional analogues__

Tasks: 
- analysis of the original "gray box" application and its disassembling;
- functional analog development in C and FASM.

Technologies: C, FASM, Ghidra, Fresh IDE, Code::Blocks.