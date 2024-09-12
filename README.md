Bank Application Simulation
Introduction
Welcome to the Bank Application Simulation project! This project is a simulation of a basic banking system, offering features like user registration, account management, transactions (deposits, withdrawals, and transfers), and admin dashboards. It provides a user-friendly interface and robust backend to ensure secure and reliable banking operations.

You can access the deployed site here: Bank Application Simulation - Live Demo

Read our comprehensive blog post about the development process: Building a Bank Application Simulation: Challenges and Learnings

Authors:
Author Name 1
Author Name 2
Installation
To run this project locally, follow these steps:

Clone the repository:

bash
Copier le code
git clone https://github.com/your-username/bank-application-simulation.git
Navigate to the project directory:

bash
Copier le code
cd bank-application-simulation
Install dependencies:

For backend dependencies, run:

bash
Copier le code
pip install -r requirements.txt
For frontend dependencies, run:

bash
Copier le code
npm install
Setup the Database:

Make sure you have PostgreSQL or your preferred database installed.
Create a new database and configure the connection settings in your .env file.
Run Migrations:

bash
Copier le code
python manage.py migrate
Start the Development Server:

Backend:
bash
Copier le code
python manage.py runserver
Frontend:
bash
Copier le code
npm start
Open your browser and navigate to:

arduino
Copier le code
http://localhost:3000
Usage
The application is divided into user and admin functionalities:

User Functions:

Register, log in, and log out.
Create and manage bank accounts.
Perform transactions like deposits, withdrawals, and transfers.
View transaction history and account details.
Admin Functions:

Monitor user activities and transactions.
Generate user reports.
Manage and audit user accounts.
Screenshot

Caption: User Dashboard showing account balances and transaction options.

Contributing
We welcome contributions from the community! If you'd like to contribute to this project, please follow these steps:

Fork the repository.

Create a new branch:

bash
Copier le code
git checkout -b feature-branch-name
Make your changes and commit them:

bash
Copier le code
git commit -m "Description of changes"
Push to the branch:

bash
Copier le code
git push origin feature-branch-name
Submit a pull request.

Please ensure your pull request adheres to the following guidelines:

Descriptive commits.
Include screenshots for any UI changes.
Include tests where applicable.
Related Projects
Online Banking System
Personal Finance Manager
FinTech Dashboard
Licensing
This project is licensed under the MIT License. See the LICENSE file for more information.





<div align="center">
<br>
    <a href="https://bank.pietrzakadrian.com"> 
        <img src="https://images.pietrzakadrian.com/logo.png" alt="Bank Application"/>
    </a>

[**Live Preview**](https://bank.pietrzakadrian.com) | [**Swagger Documentation**](https://api.pietrzakadrian.com/documentation) | [**Contact the developer**](mailto:contact@pietrzakadrian.com)

 <hr>
<h4>
Full Stack Web Application similar to financial software that is used in professional banking institutions.
</h4>

</div>

- The current account balance is calculated based on the SQL operation (**Double-entry bookkeeping**)
- Internalization of the application for three languages: **English**, **German** and **Polish**
- Support for **multiple currencies** with the current rate supplied from an external server via **API**
- Application programmed according to the correct design patterns and principle, i.e. **SOLID**, **DRY** and **KISS**
- Software supports **PWA**, it is adapted to all modern browsers and mobile devices (RWD)
- Implementation of **Google Analytics** along with the Cookie Consent according to the **GDPR**

<hr>

<div align="center">
    <img src="https://images.pietrzakadrian.com/app_dashboard.png"  />
</div>

<hr>

<dl>
  <h3>Frontend technologies stack (<a href="https://github.com/pietrzakadrian/bank-client"><strong>client</strong></a>)</h3>
  <dd>JavaScript, <a href="https://github.com/facebook/react">React.js</a>, <a href="https://github.com/reduxjs/react-redux">Redux</a>, <a href="https://github.com/redux-saga/redux-saga/">Redux-Saga</a>, <a href="https://github.com/reduxjs/reselect">Reselect</a>, <a href="https://github.com/immerjs/immer">immer</a>, <a href="https://github.com/ant-design/ant-design">Ant Design</a> and <a href="https://github.com/styled-components/styled-components">styled-components</a></dd>

  <h3>Backend technologies stack (<a href="https://github.com/pietrzakadrian/bank-server"><strong>server</strong></a>)</h3>
  <dd><a href="https://github.com/microsoft/TypeScript">TypeScript</a>, <a href="https://github.com/nodejs/node">Node.js</a>, <a href="https://github.com/nestjs/nest">Nest.js</a>, REST API, PostgreSQL and Swagger Documentation</dd>
</dl>

<hr>

<h4>System requirements</h4>

- [**Node.js** v12.18+](https://nodejs.org/en/)
- [**yarn** v1.22+](https://classic.yarnpkg.com/en/)
- [**PostgreSQL** v10.12+](https://www.postgresql.org/)

<h4>Installation</h4>

```bash
# 1. Clone the bank repository
git clone https://github.com/pietrzakadrian/bank

# 2. Enter the bank directory
cd bank

# 3. Initialize and clone attached submodules for backend and frontend app
git submodule init && git submodule update
```

<h4>License</h4>
This project is licensed under the MIT license. Copyright (c) 2019-2020 Adrian Pietrzak.
