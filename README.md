# ten-years-of-nba-data

Using ten NBA seasons of NBA data from 2010-2019 to practice web scrapping, data cleaning, and wrangling. The scrapped information includes teams, coaches, champions, and players. Some of this data is going to be used for a finals winner prediction project. This repository will therefore highlight how to clean data and make notes about why certain decisions about missing data were made.

## Data

- Scrapped and read from [Basketball Reference](https://www.basketball-reference.com/)
- Teams consolidated names and abbreviations read from [this Wikipedia list](https://en.wikipedia.org/wiki/wikipedia:WikiProject_National_Basketball_Association/National_Basketball_Association_team_abbreviations)
- For teams that changed names or locations, the names and abbreviations were cross-referenced manually on basketball reference's site for that particular season. This is documented on the `import_clean.ipynb` Jupyter notebook

### Instructions

** These instructions are subject to change as the project is updated

- Have Jupyter notebooks compatibility with your machine and editor of choice; either with [Anaconda or miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/download.html) for a lighter download.
- Download the all `.ipynb` files from this repository, and run in this order

> - `import_clean.ipynb` to scrape and read html tables and clean them before exploring data features
> - `data_wrangling.ipynb` to explore missing feature values, and see documentation (on Jupyter notebook) on how decisions were made to handle the missing data
> - `EDA_players_coaches.ipynb` to see some descriptive statistics and correlations for data on teams from the last decade

### Data Usage

The data was part of practice and learning on how to collect, clean/wrangle data while making decisions on how to handle missing information along with using some libraries to conduct exploratory data analysis. There are some thoughts for each step and decision. If throughout the Jupyter notebooks something is unclear, please feel free to reach out for clarification. This is a learning experience, so your feedback (and time) is appreciated if you choose to give it :smile:!
