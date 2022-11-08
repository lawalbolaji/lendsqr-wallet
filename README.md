// README.md
# lendsqr wallet

### Introduction
lendsqr wallet is an open source wallet...

### lendsqr wallet Features
* Users can signup and login to their accounts
* Authenticated users can fund their wallet, transfer funds to other wallets and make withdrawals.

### Installation Guide
* Clone this repository.
* The main branch is the most stable branch at any given time, ensure you're working from it.
* Run npm install to install all dependencies
* Create an .env file in your project root folder and add your variables. See .env.example for assistance.
* [database config]

### Usage
* Run npm start:dev to start the application.
* Connect to the API using Postman on port 3100.

### API Endpoints
| HTTP Verbs | Endpoints | Action |
| --- | --- | --- |
| POST | /api/v1/auth/create-account | To create a new user account and wallet |
| POST | /api/v1/auth/login | To login an existing user account |
| POST | /api/v1/user/:userId/wallet/:walletId/fund | To fund wallet |
| POST | /api/v1/user/:userId/wallet/:walletId/transfer | To transfer between wallets |
| POST | /api/v1/user/:userId/wallet/:walletId/withdraw | withdraw from wallet |

### Technologies Used
* [NodeJS](https://nodejs.org/) This is a cross-platform runtime environment built on Chrome's V8 JavaScript engine used in running JavaScript codes on the server. It allows for installation and managing of dependencies and communication with databases.
* [ExpressJS](https://www.expresjs.org/) This is a NodeJS web application framework.
* [Mysql](https://www.mysql.com/) This is a free open source SQL database with ACID compliance.
* [Knexjs ORM](https://knexjs.org/) This makes it easy to write mysql queries by providing a straight-forward, schema-based solution to model to application data.

### Authors
* [Abdulrasheed Lawal](https://github.com/lawalbolaji)

### License
This project is available for use under the MIT License.
