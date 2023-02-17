# NER for Covid Tweets
 ## Named-entity recognition model for Covid and remote learning related Tweets 
 <img src="https://cdn-images-1.medium.com/max/2000/1*7DkqpU3E-E9yknyw9c7vCQ.png" title="NER">
 
  ### INTRODUCTION 
  This Named Entity Recognition (NER) project involves identifying and classifying named entities in text, which can include proper nouns such as people's names, organization names, and locations. To conduct this project, we extracted data from Twitter using data scraping tools. The data was then manually annotated using the Doccano tool to mark the named entities present in the tweets. We used these annotated data to train a named entity recognition model using the Spacy tool.

  This project enabled us to gain a better understanding of how named entities are used in Twitter tweets, which can be useful for various applications such as analyzing public opinion or monitoring the evolution of certain trends. The use of manual annotation helped to ensure accuracy in the model's training, and the resulting model can be further developed and applied to other datasets or applications. This project also highlights the importance of ethical considerations when working with user-generated content such as Twitter data, including privacy concerns and potential biases.
  
  
  ### PURPOSE
  Our goal is to develop a named entity recognition solution capable of identifying and classifying named entities in COVID-19-related tweets extracted from Twitter. To achieve this, we first extracted data from Twitter using data scraping tools, focusing on tweets related to COVID-19. We then manually annotated this data using the Doccano tool to mark the named entities present in the tweets. Finally, we used these annotated data to train a named entity recognition model using the Spacy tool.

  The outcome of our project will be a named entity recognition system capable of identifying and classifying named entities in COVID-19-related tweets on Twitter, which could be useful for various applications such as monitoring the spread of the disease or analyzing how COVID-19 is being discussed on social media. The manual annotation process ensures accuracy in the model's training, which can be further refined and optimized to improve its performance. Additionally, this project highlights the importance of ethical considerations when working with sensitive topics such as COVID-19, including the potential biases and the need to protect users' privacy. Overall, this project demonstrates the potential of using machine learning techniques to gain insights into important societal issues and make informed decisions.
  
 ### DATASET DESCRIPTION 
 We extracted our dataset from Twitter using the Tweepy API and the following hashtags: #COVID, #Remote, and #Distance Learning. We then processed and cleaned the data using various Python libraries to prepare the dataset for annotation. The final dataset comprises tweets related to COVID-19, remote work, and online learning, which were previously cleaned to remove irrelevant or unwanted data.

 We will now use this dataset to train a named entity recognition model. The cleaning process ensures that the dataset is consistent and relevant, which is essential for accurate training of the model. We will use machine learning techniques to develop a model that can identify and classify named entities in tweets related to COVID-19, remote work, and online learning. The model can then be used for various applications, such as monitoring trends in remote work and online learning or analyzing the sentiment towards COVID-19 on social media.
 
 ### ANNOTATION
  <img src="https://raw.githubusercontent.com/doccano/doccano/master/docs/images/logo/doccano.png" title="NER">

 Data Annotation refers to the process of manually labeling the named entities present in the tweets of the dataset by assigning them a specific tag. In our project, we used the tool Doccano to annotate the dataset using the following labels:

    Date 
    Country 
    Level 
    Pedagogic 
    Person 
    Location

  We chose these labels based on the context of our project, which focuses on identifying and classifying named entities in tweets related to COVID-19, remote work, and online learning.

  The annotation process is essential to train a named entity recognition model that can accurately identify and classify named entities in new, unseen tweets. Manual annotation ensures that the dataset is consistent and accurate, which is crucial for the success of the model. Our annotated dataset will serve as the training data for our machine learning model, enabling it to learn from the labeled examples and predict the named entities in new tweets.
 
 
 ### NLP MODEL 
  With our dataset now annotated, we can proceed to train our model for named entity recognition. We set up a named entity recognition model using Spacy, which will be trained on our annotated dataset using the labels we added manually to mark named entities in the tweets. Once trained, this model will be able to automatically spot and classify named entities in new data, which can be useful for various applications.
With our dataset now annotated, we can proceed to train our model for named entity recognition. We set up a named entity recognition model using Spacy, which will be trained on our annotated dataset using the labels we added manually to mark named entities in the tweets. Once trained, this model will be able to automatically spot and classify named entities in new data, which can be useful for various applications.

### CONCLUSION
  In this project, our aim was to develop a named entity recognition solution capable of identifying and classifying named entities in COVID-19 related tweets extracted from Twitter. We first extracted the data from Twitter using data scraping tools, focusing on COVID-19 related tweets. Then, we manually annotated the data with the Doccano tool to mark the named entities present in the tweets. Finally, we used these annotated data to train a named entity recognition model using the Spacy tool.

  Our results show that our named entity recognition model is capable of reliably identifying and classifying named entities in tweets, which could be useful for many applications such as monitoring the spread of the disease or analyzing how COVID-19 is being discussed on social media. However, we also identified important challenges in this project, such as data preparation and manual annotation of the dataset. In the future, we hope to continue our efforts to improve the performance of our model and expand its capabilities to new tasks. We thank everyone who contributed to this project.


 
