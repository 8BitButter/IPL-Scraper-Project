# IPL Scraper
### Overview
The IPL Scraper is a Python-based tool for extracting IPL auction data from the official IPL website. Designed with scalability and modularity in mind, this project provides a clean interface for scraping, processing, and exporting auction data. It is packaged as a Python module for seamless integration into larger analytics pipelines.

### Features
Web Scraping: Fetches IPL auction data using requests and BeautifulSoup.
Data Processing: Parses and organizes tabular data into a structured pandas DataFrame.
Data Export: Outputs data to a CSV file for further analysis.
Module Setup: Packaged for easy installation and distribution.

### Installation
#### Clone the repository:

```bash
git clone <repository_url>
cd <repository_folder>
```
#### Install the dependencies:

```bash
pip install -r requirements.txt
Install the package:
```
```bash
python setup.py install
```
### Usage

#### Run as a Jupyter Notebook:
1. Open `IPL_Scraper.ipynb` in Jupyter Notebook.
2. Execute the cells to scrape, process, and export the IPL auction data.

#### Use as a Python Module:
1. Import the package in your Python scripts to reuse the scraping and processing functionalities.

### Output:
The scraper generates a CSV file named `extracted_data.csv`, containing IPL auction data in a tabular format.

### Dependencies
The project relies on the following libraries:
- `requests`: For making HTTP requests to fetch web page content.
- `beautifulsoup4`: For parsing and navigating HTML content.
- `pandas`: For data manipulation and storage.
- `jupyter`: For running the notebook interactively.

All dependencies are listed in the `requirements.txt` file and installed automatically during setup.

### Setup Details
The project is configured using `setup.py` for modularity and ease of distribution:

- **Package Name**: IPL Scraper
- **Version**: 0.0.1
- **Author**: Rajat
- **Email**: rajatyofficial@gmail.com
- **Dependencies**: Dynamically loaded from `requirements.txt`.