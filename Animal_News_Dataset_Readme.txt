This animal_news_database readme.txt file was generated on 2021-03-16

GENERAL INFORMATION

1. Title of Dataset: Animal News Database

2. Author Information
	A. Contact Information
		Name: Ritwik Kulkarni, Enrico Di Minin
		Institution: University of Helsinki
		Email: helics-lab@helsinki.fi


3. Date of data collection (single date, range, approximate date) : 2020 

4. Geographic location of data collection <latitude, longiute, or city/region, State, Country, as appropriate>: Online news over the internet

5. Information about funding sources that supported the collection of the data: European Research Council


SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) 

2. Links to publications that cite or use the data:  >Automated retrieval of information on threatened species from online sources using machine learning, Ritwik Kulkarni  and Enrico Di Minin, 2021, Methods in Ecology and Evolution

3. Recommended citation for this dataset: Automated retrieval of information on threatened species from online sources using machine learning, Ritwik Kulkarni  and Enrico Di Minin, 2021, Methods in Ecology and Evolution


DATA & FILE OVERVIEW

1. File List: animal_news_database_modified.json

2. Are there multiple versions of the dataset?
	This is the original data used for publication. The process of collection is continuous and authors may keep collecting more data with time. 


METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
Details can be found at : Automated retrieval of information on threatened species from online sources using machine learning, Ritwik Kulkarni  and Enrico Di Minin, 2021, Methods in Ecology and Evolution
This work specifically details the methods used for collection of large scale data on news publications on threatened species of conservation concern. 
The article describes a pipeline that implements an end-to-end application of downloading data to filtering using machine learning methods and processing the data using Natural Language Processing techniques. 

2. Methods for processing the data: 
Please refer to the publised article. 

3. Instrument- or software-specific information needed to interpret the data: 
The data is in json format and no special software is required to read the data.

4. Describe any quality-assurance procedures performed on the data: 
	The published methods descibe machine learning techniques to filter the data for relevancy and clean the data. 

5. People involved with sample collection, processing, analysis and/or submission: Ritwik Kulkarni, Enrico Di Minin


DATA-SPECIFIC INFORMATION:
	The json contains 2277 entires which details specifics of 585 species listed under he CITES Appendix I list of species (species under threat of extinction for which trade is prohibited except for non commercial purposes). There are 15088 articles as URL links to original articles published. The full text of the articles could not be stored in the data for distribution due to copyright constraints of some publishers. There is information on top 150 keywords along with thier frequencies in the articles. The URL can be used to download the full text of the article.  


Specialized formats or other abbreviations used: NER >>Named Entity Recognition.
