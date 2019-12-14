# Final-Project
Home Depot Search Relevance<br>
<br>
1. Summary of the project and data<br>
Shoppers rely on Home Depot’s product authority to find and buy the latest products and to get timely solutions to their home improvement needs. From installing a new ceiling fan to remodeling an entire kitchen, with the click of a mouse or tap of the screen, customers expect the correct results to their queries – quickly. Speed, accuracy and delivering a frictionless customer experience are essential.<br>
In our project, we would help Home Depot’s to improve their customers' shopping experience by developing a model that can accurately predict the relevance of search results.<br>
Search relevancy is an implicit measure Home Depot uses to gauge how quickly they can get customers to the right products. Currently, human raters evaluate the impact of potential changes to their search algorithms, which is a slow and subjective process. By removing or minimizing human input in search relevance evaluation, Home Depot hopes to increase the number of iterations their team can perform on the current search algorithms.<br>
<br>
2. Instructions<br>
<br>
2.1 Import Data<br>
	Import libraries<br>
	Load data<br>
	Add product descriptions to all table<br>
2.2 Text Preprocessing<br>
	Text Feature Extraction Functions<br>
        Convert number to word<br>
	Lower, remove symbol stop words<br>
	Stemming<br>
2.3 Text Feature<br>
	String distance<br>
	TF IDF<br>
	Word2Vec<br>
2.4 Data Modeling<br>
	GBDT<br>
2.5 Conclusion<br>
        Results<br>
<br>
In our project, we would help Home Depot’s to improve their customers' shopping experience by developing a model that can accurately predict the relevance of search results.<br>
Home depot is the equivalent of selling hardware (like Google vertically) , when we type in the search box, "I want to build a house’’, all the tools used to build the house would show up. This is the background.<br>
The core of this project is natural language processing, the nature of NLP is the conversion of a natural language into a computer language, so the first thing we need to understand natural language processing steps, roughly from text, Tokenize, Lemma or Stemming, stopwords, to Word_List (this is the typical text pretreatment) and then do the feature engineering, which is the text into digital, finally we can build some model to train the data and We get what we want.<br>
The most different and interesting part of this project is that we can create different features by ourselves instead of simply calling third-party libraries<br>
