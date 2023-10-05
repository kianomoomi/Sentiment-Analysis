# Sentiment Analysis
In this project, I conducted sentiment analysis on a movie reviews. Initially, I performed preprocessing on the data. Subsequently, I employed two approaches to obtain embeddings for each sentence:
### Approach 1
In this approach, I utilized a straightforward TF-IDF vectorizer to construct the term-document matrix, resulting in an embedding for each sentence.
### Approach 2
This represents a more sophisticated approach in which I employed FastText for feature extraction, enabling the generation of embeddings for each sentence.
## Training the model
Given that neural networks are capable of capturing intricate relationships between features, they are a suitable choice for this task. I constructed two distinct neural networks for different approaches using TensorFlow and trained them individually. In the end, I compared their results, and it was evident that FastText performed slightly better.
