# Developers API

This is a simple web api. Built to provide the data needed for applications that work with tinder-style user match. Implemented entirely in javascript under nodejs platform using the express framework. We chose the non-relational database mongodb.
The Api allows us to create developers profile based on GitHub data setting likes and dislikes for them

## Getting Started

To run the api, just run the command to install node dependencies such as "npm install" or "yarn install". Then run the "yarn dev" command that references a script configured in the package.json file.

### Prerequisites

An environment variable file that stores the mongodb connection string through mongoose was used. It contains variable called CONNECTIONSTRING as shown below:

CONNECTIONSTRING=...


## Built With

* [Nodejs](https://nodejs.org) - The powerful platform ever
* [Express](https://expressjs.com) - Web Framework
* [Mongodb](https://www.mongodb.com/) - The database
* [Mongoose](https://mongoosejs.com/) - Used to modeling mongodb database

## Authors

* **Luiz Gustavo Moço** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


