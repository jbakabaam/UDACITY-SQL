UDACITY-SQL
===
![temp](https://user-images.githubusercontent.com/103108988/164614280-c19fba8b-ab6c-4f92-8fbd-a47cd5bb6818.jpeg)

Created By JBAKABAAM
---
This repository contains projects did for Udacity SQL Nanodegree.

⭐️ Project1: Deforestation Exploration
---
### Overview:
You’ve been able to find tables of data online dealing with forestation as well as total land area and region groupings, and you’ve brought these tables together into a database that you’d like to query to answer some of the most important questions in preparation for a meeting with the ForestQuery executive team coming up in a few days.  
Ahead of the meeting, you’d like to prepare and disseminate a report for the leadership team that uses complete sentences to help them understand the global deforestation overview between 1990 and 2016.

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
