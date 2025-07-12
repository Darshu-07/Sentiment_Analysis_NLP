# Sentiment Analysis and Natural Language Processing for Marketing

   * Download the dataset of Amazon reviews.
   * Create your own dataset from the Amazon reviews.
   * Decide whether people like or dislike the video game they bought. Label each review with a sentiment score between -1 and 1.
   * Check the performance of your sentiment analyzer by comparing the sentiment scores with the review ratings.
   * Evaluate the performance of your sentiment analyzer and find out if you managed to correctly label the reviews.
   * Try out other methods of sentiment analysis. Explore how people evaluate the video game they purchased by classifying the reviews as positive, negative, and neutral.

Summarize your results to the Head of the Growth Hacking Team. Based on your findings, list those things that are liked and those ones that are disliked about video games.

## Techniques Employed

In order to get a deeper understanding of people’s opinion about video games, you will employ various NLP techniques. Here is a short list about what you will do and what techniques you will use.

   * Sampling from imbalanced datasets using the imbalanced-learn package
   * Enquiring about the sentiment value of the reviews with the dictionary-based sentiment analysis tools, which are part of NLTK, a natural language processing toolkit, used in Python.
   * Finding out if your algorithm did a good job. Data evaluation with scikit-learn in Python.
   * Analyzing the reviews with a state-of-the-art deep learning technique, namely with the DistilBERT model. To build this model, you will need to run Pytorch, transformers, and the simpletransformers packages.
   * Evaluating your model and creating descriptive statistics in Python with scikit-learn library before reporting your results to your boss.
   * Visualizing your findings about preferable and non-preferable words related to video games using Altair.
   
## Project Outline

The project is made up of five steps, which are built on each other:

   * Creating your dataset.
   * Creating a dictionary-based sentiment analyzer.
   * Evaluating your dictionary-based sentiment analyzer.
   * Creating neural network-based sentiment analyzers.
   * Reporting your results.

Both the steps and the techniques in this project model a real-life scenario. If you are employed as an NLP Specialist, you are likely to accomplish jobs like these ones.

## Dataset

The Amazon review dataset can be downloaded from [here](https://nijianmo.github.io/amazon/index.html). Download the zipped json file of the category of video games 5 core, which can be found under the title Small subsets for experimentation. Once the download is complete, extract the file.


<img width="785" height="656" alt="Screenshot 2025-07-12 234831" src="https://github.com/user-attachments/assets/ab0cc193-e9f5-48e1-a9a1-c7d8411f8fde" />

<img width="1293" height="763" alt="Screenshot 2025-07-12 234813" src="https://github.com/user-attachments/assets/6aa4f391-b70c-4b94-ba1b-0849e569fbc6" />

<img width="684" height="462" alt="Screenshot 2025-07-12 234755" src="https://github.com/user-attachments/assets/e6c06824-2cbc-41ca-bb87-831b1ef4e475" />

<img width="690" height="464" alt="Screenshot 2025-07-12 234737" src="https://github.com/user-attachments/assets/02cdd973-9137-4a03-8593-d8018eed4fe7" />



