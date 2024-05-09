# SQL Normalization

- https://www.youtube.com/watch?v=SK4H5tTT6-M

## Intro

- 5 Rules for making data "normal" which build over each (so to be in 3rd normal form the data must be in 1st normal form)

  - The first 3 are for core basics
  - The latest 2 are for exceptions

- The magic og data lies in its relationships and types of relationships - Cardinality

- So, we are gonna focus in the core (first three Normal Form)

## 1st Normal Form (1NF)

- It's about Atomic Value and Unique Identifiers. The rules for normalization:

1. A cell must never contain more than one value

   - So, if there's an array or something, we must slipt the data

2. Each row must be unique

   - One Column, _or a combination of columns_, must be able to uniquely identify the row (primary key)
     -Primary keys often are system generated

3. Each column name must be unique

4. There must be no repeating groups
   - They must me moved to a new table
   - ![e.g.: ](image-1.png)
