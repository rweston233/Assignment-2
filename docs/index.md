# Assignment 2 Repo

## Assignment 2 Learning Objectives

### Part I
> Getting familiar with MySQL

- Using MySQL Workbench Model and illustrate tables, the table properties, property data types, and any relationships.
- Decipher which columns are the primary key or keys, and which columns are foreign keys. (Surrogate columns are welcome to be used for primary keys.)

- Using the list below of required table names. Make a relational model that can be used to track who comes to a family wedding.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  **- Person** - 3 columns minimum and 10 rows minimum  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  **- Relationship** - 1 column minimum and 10 rows minimum  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  **- Family** - M:N, 3 columns minimum and 5 rows minimum  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  **- Friend** - M:N, 3 columns minimum and 5 rows minimum  

**Part I Deliverables**
- A PDF of the entity relationships (ER) diagram named `er_diagram.pdf`
- The SQL to create the four tables in a single SQL file named `schema.sql`
- Four csv exports of the data of each of the four tables named `person_data.csv`, `relationship_data.csv`, `family_data.csv` and `friend_data.csv`


### Part II
> Start writing SQL queries

- **Construct the following queries:**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - A query to list all persons with family relationships using joins between person, family and relationship  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - A query to list all persons with friendship relationships using joins between person, friend and relationship  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - A query to list all person, with or without a relationship of any kind, and any family relationships (hint: left join)  

**Part II Deliverables**
- Create a file called `queries.sql` and add the queries to the SQL file. Include a query description before each query as a query comment.


### Part III - *Optional Extra Credit*
> Think how you might make it possible to calculate the number of generations one person is from someone else. In other words, a relationship from father to son is 1, while a relationship of grandfather to grandson is 2.

- Create a file called `generations.txt`, and write a paragraph of at least three sentences describing how you might solve this problem. Your solution should propose any additional tables, and any changes to existing tables, and how these changes would be used to compute generation numbers.

#### Deliverables
[assign02.zip](https://github.com/rweston233/Assignment-2/blob/main/assign02.zip)

>> Back to home page:
[Home](https://rweston233.github.io/)
