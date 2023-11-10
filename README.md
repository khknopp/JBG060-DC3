# South Sudan Project Group 5

## Requirements
To install the requirements open Terminal (macOS)/Command Prompt (Windows) and run pip install -r requirements.txt. If you create a new environment in PyCharm, an icon should appear to install requirements. The code runs with Python 3.9.16.

Main libraries used:
- bertopic == 0.15.0 
- pandas == 1.4.4 
- geopandas == 0.13.2 
- matplotlib == 3.7.2 
- seaborn == 0.12.2
- statsmodels == 0.14.0 


## Files description

topic_modelling.ipynb - file with the introduction of new categories from the articles and sentiment difference
final_plots.ipynb - file with the final plots used in our poster
final_model.ipynb - file with the final model used, and relevant performance metrics
articles.ipynb - file with data exploration of articles
news_sources.ipynb - file with data exploration of publishers
other_models.ipynb - file with other machine learning models used for exploration

## How to run code

1. Install requirements as described above
2. Run topic_modelling.ipynb to obtain data (we have generated it beforehand in (data/) so the functions to save them are commented out)
3. Run final_model.ipynb to get predictions 
4. Run final_plots to generate plots

Optional - run other files to access relevant information


