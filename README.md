# JSONPowerDb
This project aims to get a brief introduction about the JSONPowerDB and its working. To get started, this project includes an index.html file when run on a local machine puts the input data into the database that is already created. 
## Description
In the first commit, the webpage is designed in a way that it takes input of the required information (Employee Id, Employee Name, Email). After taking the input, the data is fed to the function "SaveEmployee()". This function is used to store the information of employee in the database. This function has many sub tasks running. Firstly, the data that is taken as input from the webpage must be stored in a variable and it needs to be converted to a JSON string. This is handled by the function "validateAndGetFormData()". Then with this json string and other Database detailings, a PUT request is created to hit the URL and store in DB. The PUT request is created by the function "createPUTRequest". This function is in the commoons.js of the documentation which is directly used using the script tag. Thereafter, the request is hit to the URL using the ExecuteCommand function. Finally, the form is reset to original for the next input.

The implementation can be further extended to second commit. This may include updating the employee details, removing a record and other things, in the same webpage. 

## Benefits of using JsonPowerDB
There are various advantages of using JSONPowerDB in the project. First of all, the database is well structured and easy to use. It can be used in many cases and it is very compatiable with various use cases. It gives serverless support. It is schema free and hence improves writability. The database uses PowerIndex which is the world's fastest indexing engine. It is also a multimode database. In an instance, a million of the indexes are processed. The database is secured with multiple security layers.It can be used for all Backend DB's, RDBMS, Document DB, Key value DB, etc.

## Release History
Initial commit : index.html 27/5/2022
