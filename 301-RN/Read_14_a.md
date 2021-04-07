# DB Normalization

![img](https://www.vector-networks.com/blog/wp-content/uploads/2016/05/Normalization-e1497448957800.png)

# What is Normalization?
> It is a database design to reduces repetitive data to store it logicaly.
> It devides larg tables to smaller connected ones.

## Database Normal Forms
1. **1NF** (First Normal Form).
2. **2NF** (Second Normal Form).
3. **3NF** (Third Normal Form).
4. etc.

> *normalization achieves its best in 3rd Normal Form.*

### 1NF (First Normal Form) Rules
1. Each table cell should contain a single value.
2. Each record needs to be unique.

### 2NF (Second Normal Form) Rules
1. Be in 1NF
2. Single Column Primary Key

### 3NF (Third Normal Form) Rules
1. Be in 2NF
2. Has no transitive functional dependencies

## Keys
> **primary key** uniquely identifies a record in a Table and can't be null.
> **foreign key**  used to connect tables and references a primary key.