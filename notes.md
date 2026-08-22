# Database
A database may be defined as a collection of interrelated data stored together to serve multiple applications.

# Benefits of using DBMS
- No Data Redundancy (in DBMS data is centralized)
- Data Inconsistency can be avoided (mismatched multiple copies of same data)
- Secured and Sharable Data

# Relational Database Model
Data stored in Tabular format.
- Relation - A table is called a Relation.
- Rows/Tuples/Records
- Columns/Fields/Attributes
- Data Items - values stored in a relation.
- Domain - a pool of values from which the actual values appearing in a give column are drawn.
# Degree - Number of columns/attributes in a Relation.
# Cardinality - Number of tuples in a Relation.

# Properties of Relation
- All rows of a relation must be distinct.
- Ordering of rows and columns are immaterial.
- For a row, a column cannot have more than one value.
- In any given column of a table, all items must be of the same kind.

# Primary Key
- a set of one or more attributes which uniquely identifies tuples within a relation.
- all the values under a primary key are unique. (NO DUPLICATES)
* should be NOT NULL and unique.
* A table can have only one Primary Key.
# KEY ATTRIBUTE - any column that is a part of primary/alternate/candidate key.
# NON-KEY ATTRIBUTE - which are not KEY attributes.

# Candidate Key
- like one of the potential candidates to stand as a primary key.
- a column or a grp of columns which uniquely identify each record of a table.

# Alternate Key
- candidate key which is not Primary Key.
- can have more than one alternate key in a relation.

# Foreign Key
- A foreign key is used to represent the relationship b/w two tables.
- A non-key attribute, whose values are derived from the primary key of some other table is known as
foreign key in current table.

----------------------------------------------------------------------------------------------------


