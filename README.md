# newsArticleSentimentAnalysis
Sentimental analysis of news articles retrieved from "inshorts app", based on a polarity score calculated using a lexicon based approach.

SENTIMENT ANALYSIS OF NEWS ARTICLES :

About : This project retrieves news articles of various categories (technology, sports, world) from the internet,
	processes the articles using VADER lexicon to obtain sentiment scores. Using these scores it classifies the
	news articles as positive, negative or neutral. Finally, we get a graphical distribution of all the articles
	from different categories based on their sentiment (positive, negative or neutral). Along with that we also
	get the most positive and most negative news articles from the three categories.

	Submitted by : SWAPNIL RAWAT (17BCE1188)

How to run :

	Platform : This project is developed on Jupyter Notebook. As it is useful for handling huge amount of data
		   and effective graphical representation of data. User interface is built using tkinter library.

	Requirements :
 
	1. Originally Anaconda Navigator was used, so as to utilize Jupyter Notebook and create this project. However
           any compiler capable of running "ipynb" files can be used for running this project.
	2. Python should be installed on your system.
	3. vaderSentiment and tkinter libraries should be installed.

	Steps Involved : Run all the Jupyter Notebook cells, after execution you will be able to see the output graph.
			 On top of the output graph, there is a CLICK-ME button. On clicking that button, you will get
			 the most positive and most negative news articles from various categories.
