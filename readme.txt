This dataset was created for the Paper 'From Group to Individual Labels using Deep Features', Kotzias et. al,. KDD 2015
Please cite the paper if you want to use it :)

It contains sentences labelled with positive or negative sentiment, extracted from reviews of products, movies, and restaurants

=======
Format:
=======
sentence \t score \n


=======
Details:
=======
Score is either 1 (for positive) or 0 (for negative)	
The sentences come from three different websites/fields:

imdb.com
amazon.com
yelp.com

For each website, there exist 500 positive and 500 negative sentences. Those were selected randomly for larger datasets of reviews. 
We attempted to select sentences that have a clearly positive or negative connotaton, the goal was for no neutral sentences to be selected.



For the full datasets look:

imdb: Maas et. al., 2011 'Learning word vectors for sentiment analysis'
amazon: McAuley et. al., 2013 'Hidden factors and hidden topics: Understanding rating dimensions with review text'
yelp: Yelp dataset challenge http://www.yelp.com/dataset_challenge
------------------------------------------------------------------------------------------------------------------------------------------------------------

NLM2 — NLM2 TASK 2: SENTIMENT ANALYSIS USING NEURAL NETWORKS
ADVANCED DATA ANALYTICS — D213
PRFA — NLM2
COMPETENCIES
________________________________________
4030.7.1 : Neural Networks
The graduate builds neural networks in the context of machine-learning modeling.
4030.7.3 : Natural Language Processing (NLP)
The graduate extracts insights from text data using effective and appropriate natural language processing (NLP) models.
INTRODUCTION
________________________________________
Throughout your career as a data analyst, you will assess continuing data sources for their relevance to specific research questions. Organizations use data sets to analyze their operations. Organizations have many possible uses for these data sets to support their decision-making processes.

In your previous coursework, you have explored a variety of supervised and unsupervised data mining models. You have seen the power of using data analytical techniques to help organizations make data-driven decisions and now want to extend these models into areas of machine learning and artificial intelligence. In this course, you will explore the use of neural networks and natural language processing (NLP).

In this task, you will choose a data file from the Web Links section. The available data sets are as follows:
•  Amazon Product Data set
•  UCSD Recommender Systems Data sets
•  UCI Sentiment Labeled Sentences Data set

For this task, you will build a neural network designed to learn word usage and context using NLP techniques. You will provide visualizations and a report, as well as build your network in an interactive development environment.

Note: You cannot use the same data set that was provided in the exemplar for this course.
REQUIREMENTS
________________________________________
Your submission must be your original work. No more than a combined total of 30% of the submission and no more than a 10% match to any one individual source can be directly quoted or closely paraphrased from sources, even if cited correctly. The originality report that is provided when you submit your task can be used as a guide.

You must use the rubric to direct the creation of your submission because it provides detailed criteria that will be used to evaluate your work. Each requirement below may be evaluated by more than one rubric aspect. The rubric aspect titles may contain hyperlinks to relevant portions of the course.

Tasks may not be submitted as cloud links, such as links to Google Docs, Google Slides, OneDrive, etc., unless specified in the task requirements. All other submissions must be file types that are uploaded and submitted as attachments (e.g., .docx, .pdf, .ppt).

Choose one dataset from the Web Links section and use it to complete the following:

Part I:  Research Question
A.  Describe the purpose of this data analysis by doing the following:
1.  Summarize one research question that you will answer using neural network models and NLP techniques. Be sure the research question is relevant to a real-world organizational situation and sentiment analysis captured in your chosen dataset.
2.  Define the objectives or goals of the data analysis. Be sure the objectives or goals are reasonable within the scope of the research question and are represented in the available data.
3.  Identify a type of neural network capable of performing a text classification task that can be trained to produce useful predictions on text sequences on the selected data set.

Part II:  Data Preparation
B.  Summarize the data cleaning process by doing the following:
1.  Perform exploratory data analysis on the chosen dataset, and include an explanation of each of the following elements:
•   presence of unusual characters (e.g., emojis, non-English characters, etc.)
•   vocabulary size
•   proposed word embedding length
•   statistical justification for the chosen maximum sequence length
2.  Describe the goals of the tokenization process, including any code generated and packages that are used to normalize text during the tokenization process.
3.  Explain the padding process used to standardize the length of sequences, including the following in your explanation:
•   if the padding occurs before or after the text sequence
•   a screenshot of a single padded sequence
4.  Identify how many categories of sentiment will be used and an activation function for the final dense layer of the network.
5.  Explain the steps used to prepare the data for analysis, including the size of the training, validation, and test set split.
6.  Provide a copy of the prepared dataset.

Part III:  Network Architecture
C.  Describe the type of network used by doing the following:
1.  Provide the output of the model summary of the function from TensorFlow.
2.  Discuss the number of layers, the type of layers, and total number of parameters.
3.  Justify the choice of hyperparameters, including the following elements:
•   activation functions
•   number of nodes per layer
•   loss function
•   optimizer
•   stopping criteria
•   evaluation metric

Part IV:  Model Evaluation
D.  Evaluate the model training process and its relevant outcomes by doing the following:
1.  Discuss the impact of using stopping criteria instead of defining the number of epochs, including a screenshot showing the final training epoch.
2.  Provide visualizations of the model’s training process, including a line graph of the loss and chosen evaluation metric.
3.  Assess the fitness of the model and any measures taken to address overfitting.
4.  Discuss the predictive accuracy of the trained network.

Part V:  Summary and Recommendations
E.  Provide the code used to save the trained network within the neural network.

F.  Discuss the functionality of your neural network, including the impact of the network architecture.

G.  Recommend a course of action based on your results.

Part VI: Reporting
H.  Create your neural network using an industry-relevant interactive development environment (e.g., an R Markdown document, a Jupyter Notebook, etc.). Include a PDF or HTML document of your executed notebook presentation.

I.  List the web sources used to acquire data or segments of third-party code to support the application.

J.  Acknowledge sources, using in-text citations and references, for content that is quoted, paraphrased, or summarized.

K.  Demonstrate professional communication in the content and presentation of your submission.
File Restrictions
File name may contain only letters, numbers, spaces, and these symbols: ! - _ . * ' ( )
File size limit: 200 MB
File types allowed: doc, docx, rtf, xls, xlsx, ppt, pptx, odt, pdf, txt, qt, mov, mpg, avi, mp3, wav, mp4, wma, flv, asf, mpeg, wmv, m4v, svg, tif, tiff, jpeg, jpg, gif, png, zip, rar, tar, 7z

