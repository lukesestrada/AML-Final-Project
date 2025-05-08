# AML-Final-Project LSE2117

This project aims to enable users to take large amounts of unstructured text data (in the form of text-based social media posts) and extract meaningful trends from it with respect to a certain topic/area of focus. The data I used for my analysis was a mixture of synthetic, artificially generated data (present at the top of the analysis_pipeline.py file, only used to validate the theoretical validity of the approach at a small scale) and a much larger Kaggle dataset containing over 1 million scraped Tweets. That original dataset can be obtained at this address: https://www.kaggle.com/datasets/kazanova/sentiment140 

The data_ingestion.py file is where I did my preliminary data exploration of the dataset I downloaded, and also where I did the subsequent processing necessary to get it ready for analysis. 

The analysis_pipeline.py file is where I performed trend analysis on subsets of the original dataset, depending on topic specified by the user. The demo() function packs together all of the functionalities I programmed into one function for easy testing; however, it requires an active Chat GPT API key if you want to try it for yourself. 
