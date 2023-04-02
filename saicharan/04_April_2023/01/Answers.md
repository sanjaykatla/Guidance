# 01-04-2023

### 1. What is Transaction?
-It is a set of logically  related operations (can not be divided into further) to perform a unit of work.
-In simple words changes made in database.
-It results either success or failure.

### 2. What is the life cycle of a transaction?
-There are four transaction phases they are:
1. Beginning of Transaction
-Transaction is started and assigns a unique identifier by issuing begin traction statement.
2. Execution of Transaction
-preforms operations on database either all the operations are completely successful or none of them are successful.
3. Committee or Rollback
-if transaction is successful permanent changes in database else undone all operations during transaction.
4. End of Transaction
ends the transaction free up if any  resources are allocated during transaction like temporary storage.

### 3. What are ACID properties?
Acid Properties are used to set some rules in database to maintain
consistency and integrity in the database.
-They are:
* A.Atomicity
* C.Consistency
* I.Isolation
* D.Durability

### 4. Describe A in ACID with an example.
**A-ATOMICITY**
-if all operations executed successfully results committed. 
-else results rollback.
example:
-If we are booking an item from an ecommerce websites via card.
-we did everything write but failed to enter correct OTP.
-So we have to do the entire process from first to book that item.
-if current step is failed we cannot go to previous step.


### 5. Describe C in ACID with an example.
**C-Consistency**
-Database should be consistent before and after the transaction.
example:
-if we are inserting a duplicate item in primary key column it should not accept it.

### 6. Describe I in ACID with an example.
**I=Isolation**
-If number of transactions are performing at a time they do not interact with each other.
example:
-If two are more people are trying to buy item which is alone until and unless the payment from 
any of the buyer is completed with will not show out of stock.


### 7. Describe D in ACID with an example.
**D-Durability**
-After successful committed transaction the data will survive permanently.
example:
If any case system failed or power supply lost in database server the data will not be lost.


### 8. What are isolation levels?
-There are 4 isolation levels they are:
* A.Read Uncommitted 
* B.Read Committed
* C.Repeatable Read
* D.Serialization



### 9. Explain the isolation levels listed above?
-Not able to find a good lecture on isolation levels.