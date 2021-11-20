# E-Commerce_Back_End

## Links

- [Video](https://drive.google.com/file/d/1ZHnAT6FUUYsNoRn7GrA_y0sGEIN6gy1t/view?usp=sharing)
- [Github](https://github.com/PAW6063)

## Description
This is an application that controls the back-end of you new e-commerce site! This application as the ability to add product, categories, and tags. You are able to give a product you created a tag, and a category to refence it. You may also update, delect and view all the following items when view you will also see the connect with category,tag, and products.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Test](#tests)
- [Credits](#credits)
- [License](#license)

## Installation
Clone the GitHub repository 
```
git git@github.com:PAW6063/E-Commerce_Back_End.git
```
then enter the command 
```
npm i
```
if you would like to create and seed your data base then enter
```
npm run sql
```
once in the mySQL CL enter
```
SOURCE ./db/schema.sql
```
then quit with the follow command to exit mySQL
```
quit;
```
once back to the terminal out of mySQL run the following command
```
npm run seed
```
Finally when you are ready to run the program enter
```
npm start
```

## Usage
[![video](https://img.shields.io/badge/video-How%20to%20Use-orange)](https://drive.google.com/file/d/1ZHnAT6FUUYsNoRn7GrA_y0sGEIN6gy1t/view?usp=sharing)


To use this program run the command 
```
npm start
```
or
```
npm run watch
```
Then you back-end e-commerce site is up and running.

Here is list of api calls to gather the information.
- Category full list
```
http://localhost:3001/api/categories/
```
- Category id search
```
http://localhost:3001/api/categories/:id
```
- Category create
```
http://localhost:3001/api/categories/
```
- Category update
```
http://localhost:3001/api/categories/:id
```
- Category delete
```
http://localhost:3001/api/categories/:id
```
- Tag full list
```
http://localhost:3001/api/tags/
```
- Tag id search
```
http://localhost:3001/api/tags/:id
```
- Tag create
```
http://localhost:3001/api/tags/
```
- Tag update
```
http://localhost:3001/api/tags/:id
```
- Tag delete
```
http://localhost:3001/api/tags/:id
```
- Product full list
```
http://localhost:3001/api/products/
```
- Product id search
```
http://localhost:3001/api/products/:id
```
- Product create
```
http://localhost:3001/api/products/
```
- Product update
```
http://localhost:3001/api/products/:id
```
- Product delete
```
http://localhost:3001/api/products/:id
```

## Features
- Node
- Express
- JavaScript
- mySQL
- Insomnia (to use without front-end)


## Tests
- None

## Credits
[PAW6063](https://github.com/PAW6063)

## License
[![license](https://img.shields.io/badge/license-MIT%20License-brightgreen)](https://choosealicense.com/licenses/mit/)