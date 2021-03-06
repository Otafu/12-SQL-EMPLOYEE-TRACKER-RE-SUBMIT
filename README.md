
# 12-SQL-EMPLOYEE-TRACKER-RE-SUBMIT
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
      
## Table of Contents

[Description](#description)<br>[Installation](#installation)<br>[Usage](#usage)<br>[License](#license)<br>[Questions](#questions)


## Description<a id='description'></a>
Terminal based employee-tracker database with tables for departments, roles, and employees.  Inquirer is implemented to allow user input.  SQL is executed based on the input to perform CRUD functions.  Results are displayed in table form for READ and with success message and id for CREATE and UPDATE.


## Installation<a id='installation'></a>
Clone repo from https://github.com/otafu/12-SQL-EMPLOYEE-TRACKER-RE-SUBMIT.  Run command 'npm i' from the terminal to create the node_modules directory and pack-lock.json file.  


## Usage<a id='usage'></a>
To create the database, open the mysql shell with 'mysql -u root -p'.  On separate lines, use 'source db/db.sql', 'source db/schema.sql', 'source db/seeds.sql'.  This will create and use the database, create the tables, and seed the tables with initial values.  Next, run 'node index.js' to initiate the inquirer prompts.  Choose the desired action and follow the prompts.  Once all prompts are answered, the results will be displayed in the terminal.



## License<a id='license'></a>
This project is covered by the MIT License license



## Questions?<a id='questions'></a>
Contact me at [GitHub](https://github.com/otafu) or by email at <clinton.tarzia@gmail.com>
    