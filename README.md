# DistilBERT-sentiment-classification-huggingface-Deployment
Deploy a Flask DistilBERT App on AWS EC2 Instance/local machine, using **ktrain** package , achieve validation score **98%**

## What is DistilBERT?  

BERT is designed to pretrain deep bidirectional representations from
unlabeled text by jointly conditioning on both
left and right context in all layers. As a result, the pre-trained BERT model can be finetuned with just one additional output layer
to create state-of-the-art models for a wide
range of tasks, such as question answering and
language inference, without substantial taskspecific architecture modifications.<br>

DistilBERT is a small, fast, cheap and light Transformer model trained by distilling Bert base. It has 40% less parameters than bert-base-uncased, runs 60% faster while preserving over 95% of Bert’s performances as measured on the GLUE language understanding benchmark.

![Alt text](https://github.com/Yasser-shrief/DistilBERT-sentiment-analysis-huggingface-Deployment/blob/main/distilbert.png)

## What is Ktrain?

ktrain is a library to help build, train, debug, and deploy neural networks in the deep learning software framework, Keras.  

ktrain uses tf.keras in TensorFlow instead of standalone Keras.) Inspired by the fastai library, with only a few lines of code, ktrain allows you to easily:

*   estimate an optimal learning rate for your model given your data using a learning rate finder
*   employ learning rate schedules such as the triangular learning rate policy, 1cycle policy, and SGDR to more effectively train your model
*   employ fast and easy-to-use pre-canned models for both text classification (e.g., NBSVM, fastText, GRU with pretrained word embeddings) and image classification (e.g., ResNet, Wide Residual Networks, Inception)
*   load and preprocess text and image data from a variety of formats

*   inspect data points that were misclassified to help improve your model
*   leverage a simple prediction API for saving and deploying both models and data-preprocessing steps to make predictions on new raw data

ktrain GitHub: https://github.com/amaiya/ktrain



