# AirBnB_Paris

## Motivation

This project analyzes the data from AirBnB flats of Paris. The goal is to first compare the relative characteristics of the different neighbourhoods using various metrics, and then to obtain wordclouds illustrating what to visit in each neighbourhood.

## Dependencies

For smooth running of the notebook, please install the following packages:  
* pandas >= 0.23.4  
* numpy >=  1.15.4  
* gensim >= 3.8.0  
* nltk >= 3.4  
* sklearn >= 0.20.1  
* matplotlib >= 3.0.2  
* wordcloud >= 1.5.0  
* pickle >= 4.0  
* tqdm >= 4.42.1
* unicodedata  
* langdetect

The reviews file should be downloaded on http://insideairbnb.com/get-the-data.html : please select the 'Detailed Review Data for listings in Paris' of the section 'Paris, Île-de-France, France'.

## Files Descriptions

The main file of this project is the enclosed jupyter notebook that was used for exploratory data analysis and results generation. There are two modes for the notebook execution : 
- The sampling mode where you can select a subsample of the data and run the full processing
- The full mode where the whole available data is used. Some code acceleration is used in this case (see below)

Also, some files present in the data repository were pre-loaded and saved, and can be loaded in the notebook. These files are AirBnB csv files and data from the french institue INSEE that provides with official statistics. 

Finally, some pickle files were saved and can be loaded to accelerate the notebook execution. 

## Licensing, Authors, Acknowledgements

Credit is given to Insideairbnb for the data. You can find the Licensing for the data at the link available http://insideairbnb.com/get-the-data.html  
Also, credit is given to INSEE for the names file, and for the population and flats statistics inside Paris. The official statistics are available on https://www.insee.fr/fr/statistiques/1405599?geo=COM-75101 (change 75101 by 750XX where XX represent two digits of the disctrict of interest).
