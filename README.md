# Mars Weather Data Analysis

Module 11 Challenge - Mars News


## Table of Contents

- [Project Description](#project-description)
- [Data Source](#data-source)
- [Code Source](#code-source)
- [Installation and Usage](#installation-and-usage)
- [Results](#results)

## Project Description

The project consists of two parts:

1. **Part 1: Scrape Titles and Preview Text from Mars News**  
   A web scraper to extract news titles and preview text from the [Mars News website](https://static.bc-edx.com/data/web/mars_news/index.html) using BeautifulSoup and Splinter.

2. **Part 2: Scrape and Analyze Mars Weather Data**  
   A scraper to collect weather data from the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) and analyze the atmospheric conditions on Mars, including temperature trends, pressure variations, and the length of a Martian year.

## Data Source

The data used in this project comes from:

- **Mars Temperature Data Site**: [https://static.bc-edx.com/data/web/mars_facts/temperature.html](https://static.bc-edx.com/data/web/mars_facts/temperature.html)  
- **Mars News Site**: [https://static.bc-edx.com/data/web/mars_news/index.html](https://static.bc-edx.com/data/web/mars_news/index.html)

## Code Source

The code is organized into the following Jupyter Notebooks:

- **`part_1_mars_news.ipynb`**: Contains the code to scrape news titles and preview text from the Mars News website.
- **`part_2_mars_weather.ipynb`**: Contains the code to scrape weather data from the Mars Temperature Data Site, perform data analysis, and visualize the results.

## Installation and Usage

To run the notebooks, you will need to have Python 3 and the following libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `beautifulsoup4`
- `splinter`
- `jupyter`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/mars-news-challenge.git
   cd mars-news-challenge

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook

4. Open `part_1_mars_news.ipynb` or `part_2_mars_weather.ipynb` to run the analysis.

### Results
The analysis provides insights into:

The coldest and warmest months on Mars at Curiosity's location.
The months with the lowest and highest atmospheric pressure.
The estimated length of a Martian year in Earth days.
Visualizations of temperature trends and pressure variations are included in the Jupyter Notebooks.

