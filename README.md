# European-Soccer-League-Analysis

This project aims to analyze European soccer data obtained from the Kaggle European Soccer Database. The analysis includes cleaning and transforming the data, establishing connections with databases, and creating interactive dashboards to visualize and explore various aspects of European soccer.

## Data Source

The data used in this project is sourced from the [European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer) on Kaggle. It consists of SQLite files containing information about players, teams, matches, and leagues across different seasons.

## Project Overview

The project involves the following steps:

1. **Data Cleaning and Transformation**: The SQLite files are loaded into Alteryx, where the data is cleaned and transformed. CSV files are generated from the cleaned data.

2. **Database Connection**: Connections are established with MongoDB using Alteryx to load the CSV files directly into the database.

3. **Data Aggregation and Calculation**: Within MongoDB, new variables are calculated, and data is aggregated based on country, league, and season.

4. **Dashboard Creation**: Interactive dashboards are developed to visualize and analyze various aspects of European soccer, including team strategies, player statistics, and league comparisons.

## Project Structure

The project consists of the following components:

- **Alteryx Flow**: This directory contains the Alteryx workflow used for data cleaning, transformation, and loading into MongoDB.
- **MongoDB Files**: This directory stores the CSV files generated from the Alteryx workflow, which are loaded into MongoDB.
- **MongoDB Code**: This directory contains the MongoDB code used for data aggregation, calculation of new variables, and preparation of data for dashboard visualization.
- **Dashboards**: This directory houses the interactive dashboards created for analysis and visualization of European soccer data.

## Dashboards

The project includes the following dashboards:

1. **Team Strategy**: This dashboard compares multiple teams' offensive and defensive strategies over time, allowing for analysis of their strategic approaches.

2. **Player Statistics**: This dashboard presents detailed statistics and overall ratings for individual players, catering to the needs of scouts and analysts.

3. **League Comparison**: This dashboard compares various leagues based on the number of goals scored, home goals, and away goals over different seasons.

## Getting Started

To explore and run this project, you will need the following:

- Alteryx Designer (or compatible data preparation tool)
- MongoDB (or a compatible NoSQL database)
- Dashboard visualization tool (e.g., Tableau, Power BI, or any compatible tool)

Please refer to the respective documentation for installation and setup instructions for the required tools. Once set up, you can explore the provided files and dashboards to analyze the European soccer data.
