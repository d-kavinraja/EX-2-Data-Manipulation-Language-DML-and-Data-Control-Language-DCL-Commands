# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:

![image](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/081ff76d-e743-4fee-993b-4fd367716f94)

### OUTPUT:

![image](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/b667993b-d5b9-4197-be2c-ee7cab1c7d1e)

### Q2) Delete the records from manager table where the salary less than 2750.

### QUERY:

![image](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/c3469723-36d2-4488-ac58-b5c8683a0e93)

### OUTPUT:

![image](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/91233fd3-5dfa-4318-b62f-db528e31914c)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![270733395-72faf04a-7d00-4070-8b1b-433f67d05a51](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/180d48fb-dd02-4d7e-991d-79e92d50f3ae)

### OUTPUT:

![270733298-b697b096-ba16-4329-ac6b-d015128fd061](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/cbf1e6e9-9633-4cf9-ad85-341e7b03c613)

### Q5)	List the names of Clerks from emp table.


### QUERY:

![270737656-b1f05e5a-a309-424e-b910-cb103f5413e3](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/feb4b41d-8428-440b-8961-078212a7e836)

### OUTPUT:

![270738265-f8bc5ab3-f99d-400e-aa3f-c1f6c4a06c5d](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/86f71191-94a7-45e6-b756-6020a06350b7)


### Q6)	List the names of employee who are not Managers.

### QUERY:

![270738366-01b12f80-95f7-431c-95a7-4470c12c4a72](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/a65b548c-2cd5-45c9-b21b-89cbdb1114c4)


### OUTPUT:

![270738422-0cf2a6ad-398f-4d29-bebb-c31a84334347](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/02933c79-0073-4274-9b90-2bc9f4814d8b)

### Q7)	List the names of employees not eligible for commission.

### QUERY:

![270738943-42336775-5693-4b45-93b4-f60e6b80183c](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/6d3c980b-752e-4df5-9648-2a4bcf6e1962)

### OUTPUT:

![270739010-8f6da561-78ad-4573-9c8b-406de97e5e19](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/f4a825b1-ac41-4d65-9b0c-e59a55e4ca33)

### Q8)	List employees whose name either start or end with ‘s’.

### QUERY:

![270739894-63e34f73-6454-4c79-bafd-403fbb23ca66](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/aec361f2-371a-43c0-8be2-7fae5ecfa2e8)


### OUTPUT:

![270739952-b947469e-7ad5-4b63-966b-652d7d2c8c0f](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/6c098d6f-d039-4325-9810-93275772b07f)

### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.

### QUERY:

![270742384-ea09fd51-d67f-4b14-abc7-7093026e69dd](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/89b37e50-40ad-42ab-9d4a-dbba66165238)

### OUTPUT:

![270742433-b3a0080f-b755-412a-b631-2c8484061c1c](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/9bd94ed7-a460-4084-8ede-87fdaf6191cf)


### Q10) List the Details of Employees who have joined before 30 Sept 81.

### QUERY:

![270743084-d96047cf-2bbb-4e35-9509-b6948cc69eff](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/a5349ed1-9a23-4d89-ad1f-4f1ea9cd63c0)

### OUTPUT:

![270743263-dc101670-2467-428c-bf52-734adc718334](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/85269e01-cc98-47d0-8e3a-18ca0b00d42e)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.

### QUERY:

![270743688-b195dae7-d5fb-405b-b0fd-8f3cac28497c](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/faf3c43b-22f9-467b-ac0d-ce28c829d279)

### OUTPUT:

![270743781-8366de8d-6502-4a70-a202-8540b84db42c](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/4298c229-f964-4b6d-a0a2-a95cf3efb38c)


### Q12) List the names of employees not belonging to dept no 30,40 & 10

### QUERY:

![270744159-ab24e141-c401-4a54-92a5-6b83dec1f504](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/b8bed764-1ff6-4925-a0e7-a6c41359274e)

### OUTPUT:

![270744231-5b712bd1-29b3-465b-93c0-5076e2aa9128](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/971930f3-b375-4560-acfc-2319350f6264)

### Q13) Find number of rows in the table EMP

### QUERY:

![270744415-c7af2c72-f955-4cfa-925e-e1768eff217b](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/ddeee89b-b882-4857-b1b6-9d03bafb1db5)

### OUTPUT:

![270744469-c5628317-f034-4f88-951c-339f05cd7079](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/d33535ee-03c1-4985-a55c-a101cc7ee17b)

### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![270744958-b50b8a48-eb40-42e5-9fd4-c638757f67ba](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/cf58aa29-f3fa-4c7f-8d1f-d6a59c8ea7dd)

### OUTPUT:

![270745021-fa7dd8b3-a982-48f3-b03e-bd7f9152564e](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/4b00eb99-b144-4f53-becb-39f06680a9f3)

### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![270745532-16718b1f-b7d9-4fbf-97df-0b4a4e74466c](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/534963f4-9772-4bab-90ec-1ccef54fb3c5)

### OUTPUT:

![270745586-123c7d66-c434-4809-8e89-85fefdf37f24](https://github.com/22008539/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/118707617/c0e4cac3-dd5f-40df-84f2-d3126c560d40)

### RESULT:

To create a manager database and execute DML queries using SQL is executed successfully.
