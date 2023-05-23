# Covid-19-exploration.SQL

This Project forcuses on data exploration and analysis of COVID-19 dataset. It involves utilizing various skills such as joins, CTEs, temporary tables, window functions, aggregate functions, creating views, and converting data types. Here's a breakdown of the project's steps and objectives:

1) Selecting Data:
Retrieves relevant data from the "coviddeaths" table in the "ProfolioProjectA" database, filtering out records where the continent is not specified.

2) Total Cases vs. Total Deaths:
Calculates the death percentage by dividing the total deaths by the total cases for a specific location (e.g., Canada).

3) Total Cases vs. Population:
Calculates the percentage of the population infected with COVID-19 by dividing the total cases by the population for a specific location (e.g., Canada).

4) Countries with Highest Infection Rate:
Identifies countries with the highest infection rate by calculating the percentage of the population infected and sorting the results in descending order.

5) Countries with Highest Death Count:
Determines the countries with the highest death count per population by aggregating the total death count and ordering the results in descending order.

6) Breaking Things Down by Continent:
Analyzes the death count per population for each continent by grouping the data by continent and calculating the maximum death count.

7) Global Numbers:
Presents global COVID-19 statistics, such as total cases, total deaths, and the death percentage.

8) Total Population vs. Vaccinations:
Joins the "coviddeaths" and "covidVaccinations$" tables, linking data by location and date.
Calculates the rolling number of people vaccinated by summing the new vaccinations over time using a window function.
Displays the rolling number of people vaccinated and the percentage of the population vaccinated.

9) Using CTE (Common Table Expression) for Calculation:
Performs the same calculation as in the previous step using a CTE, allowing for more complex calculations and data manipulations.

10) Using Temporary Table for Calculation:
Performs the same calculation as in step 8 but utilizes a temporary table to store the intermediate results.

11) Creating a View:
Creates a view named "PercentPopulationVaccinated" that encapsulates the query used to calculate the rolling number of people vaccinated and the percentage of the population vaccinated.


The project aims to provide insights into COVID-19 data, including infection rates, death rates, vaccination rates, and comparisons across different locations and continents. It demonstrates your skills in data manipulation, analysis, and visualization using SQL and database tools.



