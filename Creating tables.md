
## Introduction

Creating database inside postgresql is simple and straightforward as other query languages.

For this example I will be creating a two sample table in the database `mydb.`

```
CREATE TABLE employeedemographics (
empId INT,
firstname VARCHAR(50),
lastname VARCHAR(50),
age INT,
gender VARCHAR(20)
)
```

```
CREATE TABLE employeesalary (
empId INT,
jobtitle VARCHAR(50),
salary INT
)
```


To INSERT DATA into these tables follow [[Insert data into tables]]
To SELECT DATA follow [[Selecting data]]