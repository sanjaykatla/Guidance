# 03-04-2023

### 1. What is Key?
-Key is an attribute or set of attributes to identify a record uniquely.
### 2. Why we need key?
-To identify a record uniquely
-To maintain relationship between tables
### 3. List the available type of keys?
* A.Primary Key 
* B.foreign Key
* C.Candidate Key
* D.Composite Key
* E.Super Key
* F.Alternate Key
### 4. Explain each of the above listed Key? 
* A.Primary Key
It is a unique identifier for a record(row)
It cannot contain any null or duplicate values
* B.foreign Key 
-An attribute in current table refers to the primary key of another table.
-Used to maintain relation between the table.
* C.Candidate Key
-An attribute or combination of attributes that could serve as primary Key
* D.Composite Key
-It is a primary Key that consists of multiple fields
* E.Super Key
-set of one or more fields that uniquely identifies a record.
* F.Alternate Key
-A candidate key that is not selected as to be the primary key
### 5. Give an example with a sample table and columns for the above listed keys.
-A table consists of Id,Name,Phone,Address
-Id is Primary key
-(name,phone),(name,address) ->super keys
-phone might be a foreign key provided if phones numbers are unique
-(name,phone),(name,address) -> composite key
-phone might be a candidate key provided if phones numbers are unique
-phone might be a alternate key provided if phones numbers are unique
### 6. How many keys a table can hold?
-Maximum number of keys may be limited by factors such as the available memory and disk space,
the specific data types being used for the keys, and the indexing algorithms being employed.