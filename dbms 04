Emp( empId int ,empName varchar(10),empSal int ,empDeptId int)
Dept(deptId int, deptName varchar(10))
1. Insert few Record.
2. List employees belonging to department 30, 40, or 10
3. List the employee details whose salary is between 10000 to 30000.
4. List total no of employee.
5. List average sal of each deptID.
6. List employee details in ascending order of salary.


CREATE TABLE Emp(empId INT, empName VARCHAR(10), empSal INT, empDeptId INT);
CREATE TABLE Dept(deptId INT, deptName VARCHAR(10));

1️⃣    Insert few records
sql
INSERT INTO Emp VALUES (1,'Amit',12000,10);
INSERT INTO Emp VALUES (2,'Neha',25000,30);
INSERT INTO Emp VALUES (3,'Raj',18000,40);

INSERT INTO Dept VALUES (10,'HR');
INSERT INTO Dept VALUES (30,'Sales');
INSERT INTO Dept VALUES (40,'IT');

2️⃣    Employees in dept 30, 40, or 10
sql
SELECT * FROM Emp WHERE empDeptId IN (10,30,40);


3️⃣    Employees with salary between 10000–30000
sql
SELECT * FROM Emp WHERE empSal BETWEEN 10000 AND 30000;

4️⃣    Total number of employees
sql
SELECT COUNT(*) FROM Emp;

5️⃣   Average salary of each dept
sql
SELECT empDeptId, AVG(empSal) FROM Emp GROUP BY empDeptId;


6️⃣   Employees in ascending order of salary
sql
SELECT * FROM Emp ORDER BY empSal ASC;


