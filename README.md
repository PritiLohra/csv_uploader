## Overview

This project is a Django-based web application that allows users to upload CSV files, perform data analysis using pandas and numpy, and display the results and visualizations on the web interface.

## Features

- **File Upload**: Users can upload CSV files.
- **Data Processing**: The application reads the CSV file and performs basic data analysis:
  - Displaying the first few rows of the data.
  - Calculating summary statistics (mean, median, standard deviation) for numerical columns.
  - Identifying and handling missing values.
- **Data Visualization**: Generates histograms for numerical columns using matplotlib and seaborn.
- **User Interface**: A simple and user-friendly interface to display data analysis results and visualizations.

## Install Dependencies

   Ensure you have the following libraries installed:

   ```bash
   pip install django pandas numpy matplotlib seaborn
   ```

## Start the Django Project

   ```bash
   django-admin startproject csv_analysis
   cd csv_analysis
   python manage.py startapp analysis
   ```

## Run the Development Server

   Start the Django development server:

   ```bash
   python manage.py runserver
   ```

   Navigate to `http://127.0.0.1:8000/upload/` to access the file upload page.

## Sample CSV File

A sample CSV file for testing purposes is included in the repository.
