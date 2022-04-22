UDACITY-SQL
===
![](https://github.com/jbakabaam/UDACITY-SQL/blob/master/Images/temp.jpeg?raw=true)

Created By Jun Buhm Lee
---
This repository contains projects did for Udacity SQL Nanodegree.

⭐️ Project1: Deforestation Exploration
---
### Overview:
In this project, I put my sql skills to help determine where to concentrate efforts to combat deforestation.

### Project Details:
- Create a View called “forestation” by joining all three tables - forest_area, land_area and regions in the workspace.
- The forest_area and land_area tables join on both country_code AND year.
- The regions table joins these based on only country_code.
- In the ‘forestation’ View, include the following:
  - All of the columns of the origin tables
  - A new column that provides the percent of the land area that is designated as forest.
- Keep in mind that the column forest_area_sqkm in the forest_area table and the land_area_sqmi in the land_area table are in different units (square kilometers and square miles, respectively), so an adjustment will need to be made in the calculation you write (1 sq mi = 2.59 sq km).

⭐️ Project2: Udiddit, A Social News Aggregator
---
### Overview:
Investigate a poorly designed database for Udiddit, a social news aggregator.  
I designed a new, normalized and performant database and migrate over data from the previous database.

### Project Details:
- Part I: Investigate the existing schema
- Part II: Create the DDL for your new schema
- Part III: Migrate the provided data
