# big-bucks-banking

## Description

Big Bucks banking is an e-commerce back-end application for online retailors using a single database to organize data such as categories, products and tags.

![License](https://img.shields.io/badge/mit-license-g.svg?style=for-the-badge&logo=&logoColor=white)

## Table of Contents

- [Technology](#Technology)
- [Installation](#installation)
- [Usage](#usage)
- [Test](#test)
- [Credits](#credits)
- [License](#license)

## Technology

- JavaScript
- Node.js
- Sequalize
- MySql
- Express
- dotenv
- mysql2

## Installation

Click on the repository link below to download the CLI app. Once there, download the zip file and copy into a directory or clone the repository into a directory using your terminal. Then, go to the directory where the CLI is kept and open in VS Code. Open the terminal in VS Code and download the requried packages by running `npm i` in the terminal. After downloading the packages create the database by running `mysql -u root` (add `-p` if you have a password) and then run `source db/schema.sql`. Once that is completed, exit out of mysql database (`quit`) and then run `npm run seed` to seed the database.

https://github.com/CullenKnott/big-bucks-banking

## Test

To test this app, open up the file in VS Code. Open the terminal, change directory into the root folder `big-bucks-banking`, and run `npm start`. This will initiate the server and allow you to host the server on your system. In order to see the data throught the server, you'll have to put the url into an app like insomnia. The walkthrough link below demonstrates how to test this application.

https://youtu.be/GCjqzUNoKl8

## License

MIT License

Copyright (c) [2023] [CullenKnott]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
