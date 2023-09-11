# EZ coding Assignment
# Introduction:
The Translation Memory ETL (Extract, Transform, Load) project is designed to streamline the extraction of bilingual translation data from the Translation Memory eXchange (TMX) file, performing data transformations, and loading the cleaned data into the MySQL server. This project serves as a foundational framework for managing multilingual translation data.
# Features:
**Data Extraction**: The project includes a module for reading TMX files, allowing easy access to bilingual translation pairs.

**Data Transformation**: Customize and apply transformations to the extracted content to clean, preprocess, or enhance the data.

**Relational Database Integration**: Cleaned data efficiently loaded into MySQL, enabling structured storage and easy retrieval.

# Prerequisites:
Before running the pipeline, ensure you have the following prerequisites installed:
1. Python 3.x.
2. 'XML.etree.ElementTree' for parsing XML (typically comes with Python standard library).
3. Pandas library for working with DataFrames (pip install pandas).
4. MySQL database server.
5. mysql.connector library for connecting to MySQL (pip install mysql-connector-python).
   
# Installation Steps:
1. **Download the Repository**: Download the TMX Data ETL Pipeline repository from your preferred version control platform or by clicking the "Download ZIP" option.
2. **Navigate to the Project Directory**: Change your working directory to the location where you've downloaded the repository.
3. **Install Python and Required Libraries**: You need to install the required Python libraries using pip.
   
# Execution instructions:
1. **Execute the ETL Pipeline**: Place your TMX file (ar-en.tmx) in the project directory.
   **Run the ETL pipeline**: python tmx_etl_pipeline.py
     This script will extract data from the TMX file, transform it (if needed), and load it into the MySQL database.
2. **Database Schema**: The pipeline creates a MySQL database called EZ1 and a table called Translator with columns in English and Arabic, both of data type TEXT.
3. **Troubleshooting**: If you encounter any issues during execution, refer to the error messages and logs for more information.
   
# Work process:
## Extract, Load, and Transform the TMX format file:
![Screenshot 2023-09-11 191206](https://github.com/Munavar7420/EZ_Works-assignment/assets/112122147/98365716-81cd-49c3-b03f-59752682d3ba)

## Transform to dataset:
![Screenshot 2023-09-11 191301](https://github.com/Munavar7420/EZ_Works-assignment/assets/112122147/55abe47c-7fad-4070-92f9-0f8b91f26ac7)

## Connecting Jupyter Notebook and MYSQL for further operations:
![Screenshot 2023-09-11 191334](https://github.com/Munavar7420/EZ_Works-assignment/assets/112122147/be76e486-ac2b-46b8-9c79-090a20d97a9d)

## Creating a database and table to store data:
![Screenshot 2023-09-11 191448](https://github.com/Munavar7420/EZ_Works-assignment/assets/112122147/ec5ad809-33f9-49fa-b0fc-c621f2ff2bf5)

## Storing data to MySQL server:
![Screenshot 2023-09-11 191539](https://github.com/Munavar7420/EZ_Works-assignment/assets/112122147/8f34fff3-1896-4e9e-b584-ad618d6f6b24)

## Data successfully stored in the MySQL database:
![Screenshot 2023-09-11 203106](https://github.com/Munavar7420/EZ_Works-assignment/assets/112122147/bdec7791-0c7a-4c20-835b-34ef162773b9)
