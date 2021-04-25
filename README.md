# E-Commerce Backend

## Description
E-Commerce Backend is the complete backend code that contains the routing for creating, reading, updating, and deleting class information stored in a database. It is complete backend code in the sense that it contains server code, code connecting the server to the database, code used to initialize a database, and code defining the columns of that database.

## Demo
![E-Commerce Backend](assets/ecommerce-backend-demo.gif)

## Installation
Before you can use the E-Commerce Backend, you will need to download the necessary npm packages. To do so, change directories in the command line interface to the 'ecommerce-backend' folder. Then type ```npm install```. You should now have all of the required npm packages installed to be able to use this app. See the next section for usage instructions.

## Usage
Before you're able to get this backend code up and running on your device, you will have to create a .env file within the parent directory with your MySQL information. Once you've done this, and once you've installed the required packages, you will also need to create the database. You can do this by entering the contents of the file "schema.sql" in the "db" folder into MySQL Workbench. Next, you may seed the data provided in the "seeds" folder by entering the command ```npm run seed``` into the command line interface.

You are now in a position to start the server. Simply type ```npm start``` into the command line to start the server. You may then test the routing and functionality of the backend using an app like Insomnia 

## Questions
Have questions? Email me at: [ian.andrew.everitt@gmail.com](mailto:ian.andrew.everitt@gmail.com).

You can also visit my GitHub profile: [Link to Ian Everitt's GitHub profile](https://github.com/rflctvEQ)

## License
[![License: Unlicense](https://img.shields.io/badge/License-Unlicense-green.svg)](https://unlicense.org/)

[Unlicense link](https://unlicense.org/)

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>