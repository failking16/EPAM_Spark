# EPAM_Spark

# EPAM Spark ETL Project

This project demonstrates an ETL (Extract, Transform, Load) process using Apache Spark to handle large datasets efficiently. The purpose is to combine weather and restaurant data, geocode locations, and perform spatial joins based on geohashes.

## Setup

1. **Spark Installation:**
   Ensure Apache Spark is installed and properly configured. Use PySpark, the Python API for Spark, which allows easy integration with other Python libraries and functions.

2. **Python Packages:**
   The project requires the following Python libraries:
   - `pyspark` - for processing data using Spark
   - `pygeohash` - for generating geohashes from latitude and longitude coordinates
   - `requests` - for making API calls to fetch geocoding data

   Install them using pip:
   ```bash
   pip install pyspark pygeohash requests
   ```
# Project Overview

This project was undertaken to develop a Spark-based ETL (Extract, Transform, Load) pipeline. The aim was to integrate and process large datasets from restaurant and weather sources. While significant progress was made, the project encountered challenges related to data quality and structure that prevented full completion.

## Project Status

### Incomplete Implementation
The project is currently not fully implemented due to persistent issues primarily related to the handling of missing and improperly formatted data.

### Data Issues
- **Missing Values:** The data pipelines encountered significant challenges due to missing values which were not handled optimally from the outset.
- **Data Structure:** There were structural inconsistencies with the input data, particularly with the weather dataset, which led to errors during the data joining process.

### Data Loading
- **Restaurant Data:** This dataset was imported correctly without major issues, confirming the effectiveness of the initial data ingestion steps.
- **Weather Data:** Only partially loaded correctly; encountered errors that suggest issues with data consistency or completeness.

### Integration Problems
Attempts to join datasets based on geospatial hashing were unsuccessful due to the above data issues, leading to repeated errors during execution.

## Code and Error Documentation
All attempts, including code, error logs, and outputs, are well-documented in the accompanying IPython notebook. This documentation provides a comprehensive view of the tasks attempted, the approaches taken, and the errors encountered.

![figure 1]('figure1.png')  
*Figure 1: Example of error encountered during data processing.*

## Recommendations for Moving Forward
To resolve the current issues and move the project towards completion, the following steps are recommended:
1. **Data Validation:** Implement rigorous data validation and cleaning steps to ensure consistency and completeness of the data before processing.
2. **Error Handling:** Enhance error handling within the ETL pipeline to gracefully manage unexpected data values and missing information.
3. **Review Data Sources:** Re-assess the data sources for reliability and structure to ensure they meet the needs of the project.

## Conclusion
While not yet successful, the lessons learned from the challenges encountered provide a valuable foundation for further refinement of the ETL processes. Continued development and focused troubleshooting are required to achieve the project objectives.

For more detailed insights into the code and processes used throughout this project, please refer to the provided IPython notebook.

---

*Note: This README relies on generic paths and descriptions. Specific details should be updated to reflect actual paths, filenames, and other relevant project-specific information.*
