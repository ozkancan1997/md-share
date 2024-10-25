# DYKT LOOKUP

Simple program for DYKT data upload and lookup.

## Table of Contents

- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [References](#references)


## Dependencies

- Node.js
    - npm
    - dotenv
    - ejs
    - express
    - mysql2

## Installation
<a id="installation"></a>

Execute following commands at your shell:

```bash
# Clone the repository
git clone https://adendumteknoloji@bitbucket.org/adendumteknoloji/dykt_lookup.git

# Navigate into the directory
cd your-repository

# Install dependencies
npm install 
```
## Usage
<a id="usage"></a>

a *.env* file required for settings like port number or database configuration.
This program uses MySql database.

| Field | Description |
| ----------- | ----------- |
| DB_HOST | Host of database for connection |
| DB_USER | Username for database connection |
| DB_PASS | Password for that username |
| DB_NAME | Database name you will connect |
| PORT | Port your program will listen |

Dependencies kept in *package.json* file as usual. Version setting can be done there.

```bash
# To Start Program
node app.js

# To Update Dependencies
npm update
```


## References
<a id="references"></a>

- [Node.js](https://nodejs.org/en)
- [Express.js](https://expressjs.com/)
- [npm](https://www.npmjs.com/)
- [MySQL](https://www.mysql.com/)

---

# Adendum Teknoloji - 2024
