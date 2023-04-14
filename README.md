
## Multiclass Text Classification for Personal Assistant Chatbot with Wysdom.AI

## Introduction

Wysdom has also developed a tool called Conversation Analytics that does just that: it analyzes millions of chatbot and live-chat conversations to automatically determine the main contact reasons (i.e., topics). The tool also displays the results in an interactive dashboard so that clients can dive deep.

Conversation analytics is difficult because (a) the messages are unstructured, (b) the messages are noisy, (c) topic analysis is inherently subjective, and (d) the optimal number of topics (and other hyperparameters) is unknown beforehand.

There are two primary approaches to topic analysis/conversation analytics: supervised and unsupervised. In a supervised approach, a human must first manually label a subset of the messages with their associated topic. Then, data scientists use ML algorithms to build a model in the usual way for text classification. In an unsupervised setting, labelling is not required. Data scientists use unsupervised ML algorithms such as clustering or dimensionality reductions, although the quality of the topics will not be as high.

## Modelling 

Implemented Deep Models, Hybrid Models, Shallow Models and Auto ML Models (Hugging Face Transformers) algorithms to achieve the best performing model of
92.69% accuracy

Skill: Text Classification, Deep Learning, Tranfer Learning, Natural Language Processing, Topic Modeling

Hosted Inference API: https://huggingface.co/palakagl/Roberta_Multiclass_TextClassification

![image](https://user-images.githubusercontent.com/94947162/228115646-1369c822-8503-425e-be0e-23211cb879bb.png)

## Approach

### Shallow Machine Learning

Preprocessing: Removing HTML Tags, Lower Case, Removing Punctuation, Remove Non-Unicode, Removing numbers, Removing Stop words, Lemmatizing text

Vectorization: Count Vectorizer, Tfidf Vectorizer

Models: Decision Tree, Random Forest, XGBoost

<img src="https://user-images.githubusercontent.com/94947162/228115949-d6e767fd-0a72-4426-b1a4-a86857574891.png" width="200" height="150"><img src="https://user-images.githubusercontent.com/94947162/228117191-db7e0d08-8a0f-49ad-8850-ab6931072f28.png" width="200" height="150"><img src="https://user-images.githubusercontent.com/94947162/228117300-8f22ef6a-23ba-42fc-800b-99c54ebe7f9d.png" width="200" height="150">

### Hybrid Machine Learning 

Preprocessing: Removing HTML Tags, Lower Case, Removing Punctuation, Remove Non-Unicode, Removing numbers, Removing Stop words, Lemmatizing text
Sentence Embeddings: Sentence Transformer -  Sbert, BertNLI, RobertaNLI, Mpnet
Models: XGBoost , Naïve Baise, Random Forest

<img src="https://user-images.githubusercontent.com/94947162/228118819-4822ecf1-cdf4-464e-92d3-96033fae7fb6.png" width="200" height="150"><img src="https://user-images.githubusercontent.com/94947162/228118892-a6a9b30d-be2b-4945-94f3-d7568072def8.png" width="200" height="200"><img src="https://user-images.githubusercontent.com/94947162/228118936-443b19e4-0282-4856-a3b0-85e195d61615.png" width="200" height="150">

### Deep Machine Learning

Preprocessing: Removing HTML Tags, Lower Case, Removing Punctuation, Remove Non-Unicode, Removing numbers, Removing Stop words, Lemmatizing text
Word Embeddings: DistilBert, Roberta 
Models: DistilBert, Roberta, Auto ML

<img src="https://user-images.githubusercontent.com/94947162/228119250-ccfefaff-7ea5-4d08-9f8f-2869e4654a7e.png" width="200" height="150"><img src="https://user-images.githubusercontent.com/94947162/228119490-8d99ece4-5e14-4634-ba23-323391e69698.png" width="200" height="150"><img src="https://user-images.githubusercontent.com/94947162/228119553-59dd2b81-2b56-43ec-9fb8-1616b96bdd3d.png" width="200" height="150">

## Results 

The project aimed to improve the accuracy of contact reason detection in Wysdom's Conversation Analytics tool by building a text classification model that can classify new messages into predefined topics. These results indicate that advanced techniques like transfer learning, natural language processing, and topic modeling can significantly improve the accuracy of contact reason detection in Conversation Analytics. The project was part of research where we are trying to find whats the best approach, between suprvised and unsupervised way to train our model. The findings from this project saved over 2-3 months of research time. 
