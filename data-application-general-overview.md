# Data Application

## One Sentance Description
A data mart that you can use in your small to medium enterprise.  
A convenience store of data in your business. 

## Elevator Pitch
Businesses earning under $100m per year can benefit from consolidating data, generating reports and dashboards, and having trustworthy data. Most companies this size don’t have the resources or expertise to build a data warehouse like massive corporations do. Data Application allows users with Excel-level skills to build and use a data mart. The data mart extracts or writes data to and from many sources. You can create analyses and reports simply from your desktop.  Create and schedule tasks as simply as you would any spreadsheet.

## Problem Being Solved
Data Engineering (ETL, Scheduling, Normalization) is a difficult task that requires a lot of infrastructure and knowledge to implement. Data Application makes Data Engineering accessible through a single desktop application.

## Job to Be Done
We need to get our data into one place so that we can do something with it.

## Features
* Simple ETL Processes
* Extract from: 
    * csv, excel, text, etc
    * other databases
    * APIs
* Write to
    * csv, excel, text, etc
    * other databases
    * APIs
* Can use multiple database backends (SQLite, SQLServer, Azure Managed Database etc.) 
* Is fully desktop
* Can be run off a single shared file (SQLite)
* Anything that you do can be done through the command-line also. 
* Can create reports
* __Future:__ Can use your data to create machine learning models.
* Easily Create merge queries (and tables) 
* Easily normalize data (including api call data) 
* Easily create tables based on incoming data
* Quick and easy data navigation
* Saved queries (created views)
* Highlight rows or cells based on certain rules
* Can add, updated, delete data within the database
* Possible: forms over data? (This seems like it might not be a future.)
* Clean DAta
* Data cleaning functions (can be database or other)
* Functions per row
* Additional calculated column
* Columns based on groupings (eg rowcount/ rownumber functions) 
* Normalize data
* Remove duplicates
* Consolidate rows

## Constraints
* Desktop application (doesn’t need a specific server)
* Shared data repository
* Multiple applications can access the database at the same time. 
* Size constraints
* Maximum: 5m rows per table
    * 1000 maximum tables
    * 200 views
    * 200 functions
* Anything bigger than this and it seems like you should have your own data engineering department.

