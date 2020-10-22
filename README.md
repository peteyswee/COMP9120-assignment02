# Assignment 02: Logical Database Design
## Introduction
### This assignment is about the logical database design for an ER diagram included in this assignment description. The objectives are to gain practical experience in relational database schema creation, including integrity constraints, based upon a given entity-relationship (ER) diagram.
## Items for Submission
### Firstly, you should submit a sql file (.sql file suffix) containing all DDL statements necessary to fully instantiate a working database for the ER diagram, and DML statements to populate each relation. Your file should run without errors in PostgreSQL 9.5. You can annotate your statements using ‘--‘ at the start of lines for comment. You should group your statements for ease of reading (e.g., by keeping all table constraints within the relevant CREATE TABLE statement rather than declaring them externally, if possible).
### Secondly, you should submit a pdf file (.pdf file suffix) including the relational model (RM) diagram that provides a visual model of your database schema. The figure below summarises the syntax to use for the RM diagram.
## Design Brief: Relational Database Schema for a Book eCommerce System
### Your task is to create a relational database schema for the entity-relationship diagram that is shown on page 3. In particular, your solution should include:
• Tables and attributes with suitable data types to capture all information in the model (please use the same names as in the ER diagram for naming tables and attributes);
• Appropriate PRIMARY KEY, UNIQUE, FOREIGN KEY constraints for all tables;
• Correct foreign key specifications including ON DELETE clauses where suitable;
• Appropriate additional integrity constraints expressed by means of NOT NULL, or CHECK clauses;
• INSERT statements to populate each relation with at least one record, to demonstrate a database instance consistent with the ER model.
