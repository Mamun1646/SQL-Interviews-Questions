# SQL Interview Questions

## Transaction
-Transaction is a single logical unit of work formed by a set of operations. Transaction is a bundle of operations.

### Transaction State Image
![Transaction](images/transactions.png)

### ACID Properties

-To ensure the consistency of the database ,Certain properties are followed by all .These properties are called as ACID properties of a transaction.



__ATOMICITY:__ Transaction occur completely or doesn't occur at all. That means no transaction occurs partially.

__CONSISTENCY:__ Database remains consistent before and after the transaction. __For Example__ Person 1 will send 100tk to Person 2 will have to receive 100tk.That is why after transaction will remain consistent.

__ISOLATION:__ Multiple transactions can occur simultaneously without causing any inconsistency.The transaction were executed serially one by one.

__DURABILITY:__ Its  After successful execution,Changes are written successfully to the permanent disk. Replication or something like that will be help to achieve durability.

### Normalization 
- Normalization is a process of making database consistent by :

 -Reducing the redundancies

 -Ensuring the integrity of data through lossless decomposition.
### First Normal Form (1NF)
 ![1N](images/1Normalization.png)

### Second Normal Form (2NF)
- In the 2NF, relational must be in 1NF.
- In the second normal form, all non-key attributes are fully functional dependent on the primary key

![1N](images/2Normalization1.png)
![1N](images/2Normalization2.png)

- For More Learn About It
[3 Normalization](https://www.javatpoint.com/dbms-third-normal-form)
[Boyce-CODD Normal Form](https://www.javatpoint.com/dbms-boyce-codd-normal-form)




<h1 align="center">SQL </h1>


### DDL
__Data Definition Language__ DDL which deals with database schemas and descriptions.
__CREATE__
__ALTER__
__DROP__
__TRUNCATE__
__RENAME__
### DML 
__DML__ is short form of Data manipulation language which deals with data manipulation and includes most common SQL statements such 
__SELECT__
__INSERT__
__UPDATE__
__DELETE__
__MERGE__

### DCL 
__DCL__ is short form Data control language which includes commands such as __GRANT__ and mostly concerned with rights, permissions and other controls of the database systems.

__GRANT__
__INVOKE__

### TCL
__TCL__ is a short form of Transaction Control Language which deals with a transaction within database.
__COMMIT__
__ROLLBACK__
__SAVEPOINT__

### SQL 
__SQL__ is a standard language for storing ,manipulating and retrieving data in database.


#####SELECT
```bash
SELECT col1, col2 from table_name;
Example : SELECT CustomerName,City from customers;

```


