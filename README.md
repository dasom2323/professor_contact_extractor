# Professor Contact Extractor
## Overview
The Professor Contact Extractor is a Python script designed for web scraping to collect contact information from San Jose State University (SJSU) faculty and staff web pages. 
This tool allows students easy access to faculty and staff contacts for academic purposes.

## Features
- Web Scraping: The program utilizes web scraping techniques to extract information from SJSU faculty and staff web pages.
- Command-Line Interface (CLI): Users can provide the name of the output CSV file as a command-line argument when running the script.
- Data Extraction: The script extracts the following information for each faculty or staff member:
  1. Last Name
  2. First Name
  3. Email Address
  4. Phone Number
  5. Education Information
 
## Usage
1. Run the script with the desired CSV filename as a command-line argument:
  ex) python professor_contact_extractor.py filename.csv
Replace filename.csv with the desired name of the output CSV file.
2. The script starts by accessing and parsing the SJSU faculty index webpage, which serves as a gateway to additional web pages containing detailed information about the faculty and staff.
3. The extracted information is then saved to the specified CSV file in a comma-separated format with column headers.

## Requirements
- Python 3.x
- Beautiful Soup 4 (bs4) library for web scraping

## Feature enhancement
Working on a webpage that displays all the collected information on a single page.

## Author
Author: Dasom Lee
