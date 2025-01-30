# World Database SQL Exploration

Calling all data detectives and globe-trotting explorers!

Imagine a treasure trove of knowledge about countries, cities, and languages – that's exactly what awaits you here.

The primary goal of this lab is to provide hands-on experience with LIMIT, OFFSET, and pagination. You will practice using these tools to answer a variety of questions about the World database. By the end of this lab, you will have reinforced your understanding of these concepts and enhanced your SQL querying skills.

[View the project on Data Wars](https://profiles.datawars.io/moanwar910/projects/8fad5fa3-1300-4287-b395-60fce5e9a155)

## Key Concepts

### LIMIT
The `LIMIT` clause is used to specify the number of rows to return in a query result.

### OFFSET
The `OFFSET` clause is used to skip a specified number of rows before starting to return rows.

### Pagination
Pagination is a technique used to divide query results into smaller chunks (pages) for easier navigation.

## Sample Queries

```sql
-- Retrieve the first 10 countries
SELECT * FROM country
LIMIT 10;

-- Retrieve the next 10 countries (page 2)
SELECT * FROM country
LIMIT 10 OFFSET 10;
