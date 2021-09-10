# employee-tracker

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)

## Description

As the user, I would like to be able view, update, and add to all the employees, departments, and roles within my company. The employee tracker allows the user to perform these tasks straight from the commandline. To use this application please see how to [use](#usage) the application.

## Installation

The dependencies that this application uses are asciiart-logo, console.table, inquirer, mysql, and mysql2.

Run the following commands after cloning the repo to install the dependencies

```
==== GitBash ====
npm init -y
npm i asciiart-logo console.table inquirer mysql mysql2
mysql -u root -p

==== MySQL ====
Enter password: ******

source db/schema.sql (if you opened terminal from the root folder)
source schema.sql (if you opened terminal from from the db folder)

source db/seed.sql
source seed.sql

==== GitBash ====
npm start
```

## Usage

To use this repo

1. Clone the repo
2. Open in vscode
3. Run the above lines of code to install packages and initialize mysql
4. Use the prompts in GitBash to create, add, update, or view employees

## Demo

[View Demo on Youtube](https://youtu.be/8DjZLqtqeys)
