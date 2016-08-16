# blog
The human brain is a sophisticated biological machine, forming rules and knowledge by memorizing everyday events. Those events help us to generalize learnings about things which we haven't seen yet, since memorization allows us to further refine our generalized rules about what is right. However, technology has a big growth in the recent times, a lot of computer scientists have been asking themselves the following question: Can we teach computer to learn like humans do? And the answer is simple: Yes, it´s possible!

Machine Learning is a type of artificial intelligence (AI) that provides computers with the ability to learn without being explicitly programmed. Machine learning focuses on the development of computer programs that can teach themselves to grow and change when exposed to new data. This a subfield of computer science have many applications such as:

* **Face detection:** The face detection feature in mobile cameras is an example of what machine learning can do.
* **Face recognition:** This is where a computer program can identify an individual from a photo.
* **Image classification:**  is an approach of classification based on contextual information in images by multiples categories.
* **Activity recognition:**  aims to recognize the human being actions and activities on videos.
* **Speech recognition:** Process of enabling a computer to identify and respond to the sounds produced in human speech.
* **Genetics:** Classical data mining or clustering algorithms in machine learning such as agglomerative clustering algorithms are used in genetics to help find genes associated.

Nonetheless, one important application is Sentimental analysis. Sentimental analysis is the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral. It is widely applied to reviews and social media for a variety of applications, ranging from marketing to customer service. 


Now, We will explore more about sentiment Analysis! 


Following below image, first step is data selection, i.e. , we need to split our data into three subsets: training set with positives and negatives examples, validation to help us to adjust our system and testing set or evaluation set.

** IMAGEN 1 **

**Source:** http://www.scielo.br/scielo.php?script=sci_arttext&pid=S0101-74382012000100009

On preprocessing step, we must be implemented a text extracting features algorithm as TF-IDF Transform. In information retrieval, tf–idf, short for term frequency–inverse document frequency, is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus. It is often used as a weighting factor in information retrieval and text mining. The tf-idf value increases proportionally to the number of times a word appears in the document, but is offset by the frequency of the word in the corpus, which helps to adjust for the fact that some words appear more frequently in general. Variations of the tf–idf weighting scheme are often used by search engines as a central tool in scoring and ranking a document's relevance given a user query. tf–idf can be successfully used for stop-words filtering in various subject fields including text summarization and classification. 

**Source:** http://scikit-learn.org/stable/modules/feature_extraction.html

Next step is about data mining and system evaluation, and to do get success on it we have to build a classifier which can interpret and discern about all extracted features previously. A common example is a Support Vector Machine (SVMs) that are a set of supervised learning methods used for classification, regression and outlier’s detection.

The advantages of support vector machines are:
* Effective in high dimensional spaces.
* Still effective in cases where number of dimensions is greater than the number of samples.
* Uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.
* Versatile: different Kernel functions can be specified for the decision function. Common kernels are provided, but it is also possible to specify custom kernels.

The disadvantages of support vector machines include:
* If the number of features is much greater than the number of samples, the method is likely to give poor performances.
* SVMs do not directly provide probability estimates, these are calculated using an expensive five-fold cross-validation.

