# Webscraping arrow scripts and extracting the main topics of each episode
Generating topics (using LDA) for each episode of the Arrow series to predict its success based on IMDb ratings.

Divided in:
1. Dataset_LDA_model.ipynb - Webscraping the scripts of each episode and the LDA model to generate a topic for each episode;
2. wikipedia_table.ipynb - Webscraping the wikipedia site for more information on the metrics of each episode;
3. 3_Dataset_final.ipynb - A notebook with the classification model and grid-searc of hyperparameters.

# The data

The scripts were taken from https://subslikescript.com/ and the ratings from https://www.imdb.com/ .

## **Streamlit**
The visualization is also compiled into a streamlit script. To do this, just install the dependencies in requirements-streamlit.txt and run the following command:

```bash
streamlit run app.py
```
