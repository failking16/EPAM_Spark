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

# Spark Geolocation and Weather Data Integration

## 🚀 Project Overview
This project integrates **restaurant location data** with **weather data** using **geohashing** and performs a **left join** on the geohash column. The project utilizes **Apache Spark** for distributed data processing.

## ⚠️ Important Notice
**To run this project, you must manually upload all necessary files and execute the scripts step by step.**  
There are known technical issues that may impact execution.

## ❗ Known Issues & Challenges
During the development and execution of this project, several **critical issues** were encountered:
1. **Apache Spark conflicts with Python versions**: Spark had major compatibility issues with my current Python version.
2. **Memory limitations**: Lack of sufficient memory caused failures, preventing the project from displaying the expected results.
3. **Consistent execution failures**: The project encountered the same errors across **three different attempted solutions**:
   - Different approaches were tried, but the output remained incorrect.
   - Solutions were overwritten multiple times, making the file structure look incorrect.
   - Code formatting and execution became increasingly unstable.

Despite these issues:
- The **same code worked on Stack Overflow users' environments**.
- The **same logic worked correctly when tested using Pandas**.
- The errors appear to be **Spark-specific rather than a code logic problem**.

## 🛠️ Requirements
- **Python 3.x**
- **Apache Spark**
- **PySpark**
- **pandas**
- **OpenCage API (for geolocation lookups)**
- **pygeohash**

## 📌 How to Run the Project
1. **Manually upload all project files.**  
   Since Spark had severe conflicts with dependencies, files cannot be pre-loaded automatically.
   
2. **Ensure Spark is configured correctly.**  
   If Spark is not running properly, you may need to adjust the environment settings.

3. **Run the main script step by step.**  
   Execute the scripts in order to ensure correct data processing.

4. **Monitor for memory issues.**  
   If errors occur, try reducing dataset size or adjusting Spark memory settings.

## 🔹 Conclusion
This project encountered severe **Spark-related compatibility issues** that prevented a smooth execution. However, **the logic behind the implementation is correct**, as confirmed through alternative testing methods. The core functionality remains valid, but execution may require **manual adjustments** to work in different environments.

---

If you face issues while running the project, **consider testing with Pandas instead of Spark** as a workaround.

For more detailed insights into the code and processes used throughout this project, please refer to the provided IPython notebook.

---

*Note: This README relies on generic paths and descriptions. Specific details should be updated to reflect actual paths, filenames, and other relevant project-specific information.*
