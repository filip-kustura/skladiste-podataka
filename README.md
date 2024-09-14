# Advanced Database Systems - Data Warehouse Project

This project is part of the elective **Advanced Database Systems** course, which involved constructing a data warehouse using the existing PostgreSQL database, with its schema illustrated in the `olympics.png` file. The goal of the warehouse was to analyze Olympic Games data and gain insights into athletes' performance over time.

## Project Overview

The data warehouse was designed to cover the complete history of the Olympic Games, enabling analysis of various factors, including:

- Athletes' performance by discipline
- Success rates based on the location of the games
- Athlete demographics (gender, build, age, nationality)

### Key Tasks Completed

1. **Defining the Fact**: Defining the fact that the warehouse represents, considering the necessary data granularity.
2. **Designing the Star Schema**: Designing the fact table and associated dimension tables using a star schema model, with SQL `CREATE TABLE` commands written for all tables.
3. **Creating the Star Schema Diagram**: Creating a visual representation of the star schema to illustrate the relationships between tables.
4. **Populating Data**: Populating the dimension and fact tables with data extracted from the given database.
5. **Implementing Queries**: Executing several SQL queries on the data warehouse to enable:
   - Identifying the top 10 most successful countries in the Summer and Winter Olympics
   - Determining the top 10 athletes in the Summer and Winter Olympics post-1950
   - Analyzing trends in women's participation over time
   - Calculating the average age of medalists in athletics and gymnastics by gender post-1970
   - Investigating home advantage regarding medal wins by local athletes

## Deliverables

The completed assignment had to include two files which are located in the `deliverables` directory:
- A plain text file containing:
  - Description of the fact represented in the warehouse
  - SQL commands for creating the fact and dimension tables
  - SQL commands for populating all tables using data from the given database
  - SQL queries that provide the required insights
- An image of the star schema

### Important Notes

- The project was accomplished solely using SQL queries, with no additional programming languages required.
