# Y Combinator Web Scraper

This repository contains a Python script for scraping company data from the Y Combinator website. The script uses Selenium and BeautifulSoup to navigate the site, load more companies, and extract the relevant information.

## File Description
`yc-2.ipynb`: This Jupyter notebook contains the Python code for the web scraper. It navigates to the Y Combinator website, scrolls down to load more companies, and extracts the following information for each company: name, logo URL, location, description, batch, industry, and sub-industry.

## How to Run
1. Make sure Python 3, pip, chromedriver and Jupyter-lab are installed
2. `cd` terminal to the this directory
3. Rename `.env.sample` to `.env` and update the values.
4. Run `Jupyter-lab` (MacOS, Linux) (TODO: add how to run this from Windows)
5. Open the yc-2.ipynb file in Jupyter Notebook or JupyterLab.
6. Run the cells in the notebook to start the web scraper. The scraped data will be saved to a CSV file.

## Note
The output and metadata in the Jupyter notebook have been cleared to keep the code clean and readable. If you run the notebook, the output will appear below each cell.
