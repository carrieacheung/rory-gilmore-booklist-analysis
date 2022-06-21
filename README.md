# rory-gilmore-booklist-analysis
Collect data from goodreads for all of the books in the Rory Gilmore booklist, and perform an exploratory analysis

goodreads_ids.txt is a text file containing the goodreads ids for all of the books in the Rory Gilmore booklist

collect_goodreads_data.ipynb is a Google Colab notebook that scrapes all of the data from the goodreads website for each book in the Rory Gilmore booklist. Change the path for the goodreads_ids.txt to match the txt files location.

goodreads_data.csv is an output of the collect_goodreads_data.ipynb notebook. This csv file contains all of the data collected from the goodreads website. This can be run directly into RG_booklist_analysis.ipynb notebook.

RG_booklist_analysis.ipynb is a Google Colab notebook that performs an exploratory analysis on the data collected in the goodreads_data.csv. Change the path for the goodreads_data.csv to match the csv files location.
