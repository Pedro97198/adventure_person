# AdventureWorks Dashboard Project

## Project by:
- Ignacio Donderis
- Pedro Torrijos
- Miguel Santiago

## Introduction

This document explains the process of developing the dashboard for the person section of the AdventureWorks dataset. It includes the creation of a GitHub repository, uploading necessary datasets for exploratory data analysis (EDA), and the creation of the dashboard in Power BI. It also addresses the problems encountered and the solutions implemented.

## Definitions and Theory

Before starting with the repository, fundamental concepts and commands in Git were reviewed:

- `git checkout`: Switches to a different branch in the local repository.
- `git merge`: Merges branches.
- `git push`: Pushes commits from the local branch to the remote repository.
- `git pull`: Combines `fetch` and `merge`.
- `git stash`: Saves uncommitted changes for later use.
- `git rebase`: Maintains a linear project history.
- `git fetch`: Updates the local repository without merging changes.

## First Steps

1. Create branches and "experiment" with GitHub.
2. Create the main branch and upload files.
3. Create and modify new branches.
4. Push changes to new branches.
5. Merge secondary branches with the main branch.
6. Use `fetch` and `diff` to avoid conflicts.
7. Use `rebase` to maintain a clean history.

## Steps in GitHub

1. Prepare Anaconda for the entire process.
2. Create the local Git repository folder and open it with VS Code.
3. Clone the repository with `git clone`.
4. Close the remote connection with the GitHub repository.
5. Execute `git init`.
6. Create a GitHub repository.
7. Execute `git remote add <repository URL>`.
8. Execute `git add`, `git commit`, and `git push`.
9. Clean the data by removing unused items.
10. Set up SQL Server and connect it to Power BI.
11. Create an entity relationship diagram.

## SQL Server Installation and Configuration

1. Download and install Microsoft SQL Server.
2. Select the free edition option as "Developer".
3. Configure the database engine services.
4. Select mixed mode authentication and set a password.
5. Install SQL Server Management Studio.
6. Download the `AdventureWorks.bak` file.
7. Restore the database in SQL Management Studio.
8. Connect Power BI to the SQL server and load the data.

## Entity Relationship Map

1. Load the person department data into Power BI.
2. Select the model view to see the relationship map.
3. Export the data as CSV for EDA.

## Mockup

Design an initial mockup to facilitate the creation of the dashboard. Three "slides" focused on different topics were designed, although adjustments were made later due to data scarcity.

## EDA of the AdventureWorks Data (Person)

1. Work with all tables in the person department.
2. Join tables to create a main table called `Person`.
3. Formulate questions for analysis:
   - What are the regions/states/cities with the highest concentration of clients?
   - Create an interactive map showing customer locations.
   - Identify trends in customer demographics over time.
   - Distribution of employees by department, position, or hierarchical level.
   - Identify different customer segments based on demographic and geographic characteristics.

## Final Dashboard

Four versions of the dashboard were developed, improving various aspects in each iteration. The GitHub repository contains the version history.

- Front page to navigate to other sections.
- Map showing the distribution of people.
- Pages dedicated to customer and employee data.
- Sales section and a table with relevant data.
- table with customer information 