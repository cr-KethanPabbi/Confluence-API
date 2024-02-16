# Confluence API

## Overview
The Confluence API is a Python script that interacts with the Confluence API to extract information about spaces and pages, and analyze the data for various purposes.

## Features
- Retrieve information about spaces and pages in Confluence.
- Extract details such as page creators, last modifiers, creation dates, and view counts.
- Save the extracted data to CSV files for further analysis or reporting.
- Update a space/spaces to be archived or set to current
- Delete a space/spaces

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone git@github.com:cr-KethanPabbi/Confluence-API.git

2. Navigate to the project directory:
   ```bash
   cd downloads/Confluence-API

## Prerequisites

Before getting started, ensure you have the following prerequisites:

- Python 3 installed on your system.
- Access to the repository.

## Configuration

1. Open the `config.py` file in an editor. Edit and save the API_KEY, CR_EMAIL to have your api and email
   ```bash
   open config.py
   
2. Add your generated API key and Email in the fields
   
3. Save and exit

## Usage
### 1. Getting Total Unique Spaces and Pages
To retrieve information about the total unique spaces and pages in Confluence, run the `Show Total.ipynb` notebook. This notebook contains the function `get_total_unique_spaces_and_pages_in_confluence()`.

### 2. Saving Page Details to CSV
To save the extracted page details to a CSV file, use the `save_page_details_to_csv()` function. This function takes the page details as input and saves them to a specified filename.

### 3. Combining CSV Files
If you have multiple CSV files and want to combine them into a single file, use the `combine_csv_files()` function. This function takes two input CSV files and an output filename as arguments.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Contact
For any inquiries or support, please contact [Kethan Pabbi](mailto:kethan.pabbi@cybereason.com).




