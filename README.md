
# Movie site

This project is based on Bootstrap, Express, Node.js, mongoDB to build the movie site

Main function modules:

- Phase I: Front movie show page, movie details page, background movie management center (movie entry, movie modification)

- Phase Ⅱ: user login registration cancellation function, user identification and persistence, background user management center (user input, user modification), movie comment

![图片预览](http://oph264zoo.bkt.clouddn.com/17-7-20/4151066.jpg)


## Technology stack

【web-design】

+ HTML/CSS/JS

+ ES6: ECMAScript

+ Monment.js: Time date formatting plugin

+ jQuery: Mainly using jQuery's ajax method to handle asynchronous requests and DOM operations

+ Bootstrap: Page UI framework

【browser side enginee】

+ pug: Used to generate HTML

+ Node.js: The entire backend is driven by Node.js; the resource file is installed with npm

+ Express: A web development framework based on the Node.js platform, consisting of routing and middleware

【database】

+ mongoDB: NoSQL database for data storage

+ mongoose: Node.js mongodb driver package, is a tool for rapid modeling mongoDB

【Automated construction】

+ gulp: Front-end automation build tool
+ JSHint: JS code validation


## to sum up

1. Familiar with the syntax of pug and its use in Node.js, understand the advantages and disadvantages of pug and how to choose

2. The initial grasp of the express framework of the use of how to deal with routing and middleware

3. Master mongoose in Node.js how to connect to the database, and schema, model, entity use

4. Front and rear data transfer and view the presentation process

5. learned to use bcryptjs (Node.js a encryption and decryption module) on the password "hash + salt" processing

6. User identification and persistence via session and cookie


## TODO

1. User login registration does not do form verification and so on

2. Full Promise

3. Upgrade to ejs template

4. The function of the movie comment function is too simplified

5. Increase the personal center

6. Front and back requests are used asynchronously using ajax

7. There are many


## Build Setup

```
# clone the repo into your disk.
$ git clone https://github.com/mrzhangjinyu/Node-demo.git

# install dependencies
$ npm install

# run
$ npm start

# visit
$ http://localhost:3000/
```


## License

The code is available under the [MIT license](LICENSE.txt).


## Thanks

@Scott
