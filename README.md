# LinkedIn Scraper and Visualization

This repository contains two Jupyter Notebook scripts for scraping LinkedIn profiles and visualizing the obtained data.

## Scraper Script

The `scraper_script(2).ipynb` notebook uses browser automation, primarily Selenium, to gather profile information from LinkedIn. The script navigates through profiles, collects data, and creates a CSV file containing all the data entries.

### Dependencies

- Python
- Selenium
- Pandas

### Usage

1. Open the notebook in a Jupyter environment.
2. Run the cells to execute the scraper script.

## Visualization

The `visualization.ipynb` notebook focuses on visualizing the LinkedIn profile data collected using different methods. It includes various visualizations such as bar plots, word clouds, and density plots and makes csv for 5 top results as asked.

### Dependencies

- Python
- Matplotlib
- Seaborn
- Geopandas
- Opencage
- nltk

### Usage

1. Open the notebook in a Jupyter environment.
2. Run the cells to generate visualizations based on the collected data.

The project is one with potential and can definitely revised and optimized to be better

## Future Additions

This project is actively maintained, and here are some planned improvements:

- [ ] Use a corporate spider(get a script that uses linkedin API).
- [ ] Enhance data cleaning and preprocessing steps.
- [ ] Add more visualization techniques for deeper insights.
- [ ] Explore other data fields in profile section.
