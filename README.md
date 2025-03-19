# Employee Position Data Analysis and Database Management

This project involves extracting, normalizing, segmenting, and managing employee position and job data into a relational database using MySQL Workbench. The objective is to optimize the dataset for querying, analysis, and reporting by following best practices in data normalization and relational database management.

## Project Overview

The dataset is segmented into various CSV files representing distinct entities such as **industry**, **location**, **job**, **position**, **employer**, and **state**. These entities are related to each other, and the data is organized using a normalized relational model, making it easy to query and analyze employment trends, wage distributions, and job position information.

## Process Breakdown

### 1. **Data Segmentation and Normalization using Power Query**
   - Data was initially extracted from the source into a raw format.
   - **Normalization**: Using Power Query, the data was organized into separate tables (e.g., **industry**, **location**, **job**, **position**, **employer**, and **state**) to eliminate redundancy and improve data integrity.
   - **CSV File Conversion**: After normalizing the data, I segmented it into individual CSV files. This segmentation process helps in better management and analysis.
   - **Command Prompt**: Used command prompt tools to convert the CSV files into **_bis** format to incorporate any additional corrections or refinements before the import process.

### 2. **Database Schema Design using ERD**
   - I created an **Entity-Relationship Diagram (ERD)** to design the database schema. The ERD helped visualize the relationships between the various entities like **state**, **location**, **job**, **position**, and **employer**, ensuring efficient organization of the data.
   - **Key Relationships**:
     - Jobs are linked to positions.
     - Positions are associated with employers and locations.
     - Locations are connected to states.
   - The ERD ensured relational integrity through primary and foreign key constraints.

### 3. **Data Import into MySQL Workbench**
   - The CSV files were imported into MySQL Workbench to populate the tables.
   - Data from normalized CSV files was inserted into the corresponding tables in the database for effective management and easy querying.

### 4. **Database Management and Querying**
   - **SQL Commands**: Used SQL queries to manage and manipulate the data after importing. This includes tasks such as:
     - Querying job positions and their associated wages.
     - Analyzing employer data and trends in hiring across various locations and industries.
     - Running joins across tables to generate detailed reports, such as linking job positions to employers and locations.
   - **Advanced Querying**: By leveraging the normalized schema and ERD, I was able to:
     - **Job Analysis**: Identifying job titles and their prevalence across different states and industries.
     - **Wage Trends**: Comparing wages for similar positions across different employers and locations.
     - **Employer Data**: Analyzing employer distribution by location and industry.

## File Overview

The data has been segmented into the following CSV files:

1. **industry.csv** - Contains industry data for employers.
2. **industry_bis.csv** - Refined version of **industry.csv**, ensuring data accuracy.
3. **job.csv** - Contains information about job titles and job codes.
4. **job_bis.csv** - Refined version of **job.csv**.
5. **employer.csv** - Contains details about employers, including names and locations.
6. **employer_bis.csv** - Refined version of **employer.csv**.
7. **location.csv** - Contains location details, including cities and states.
8. **location_bis.csv** - Refined version of **location.csv**.
9. **position.csv** - Contains detailed information on job positions, including total worker positions and wages.
10. **position1.csv** - Subset or filtered version of **position.csv**.
11. **position1_bis.csv** - Refined version of **position1.csv**.
12. **position2.csv** - Another subset of **position.csv**.
13. **position2_bis.csv** - Refined version of **position2.csv**.
14. **position3.csv** - Another detailed breakdown of position data.
15. **state.csv** - Contains state-specific data for work locations.
16. **state_bis.csv** - Refined version of **state.csv**.

## Technologies Used

- **Power Query**: Used for data normalization and segmentation.
- **MySQL Workbench**: Used for loading data into a relational database and managing the database.
- **ERD**: Entity-Relationship Diagram used for designing the database schema and relationships.
- **SQL**: Used for querying and analyzing data after import into MySQL Workbench.

## Conclusion

This project demonstrates efficient data normalization, segmentation, and management practices. By using Power Query for data processing, MySQL Workbench for database management, and ERD for schema design, the project ensures that the data is structured in a way that supports efficient analysis and querying, ultimately enabling valuable insights into employment trends, job position distribution, and wage analytics.
#SQL !Pytho # LargeDataSet
