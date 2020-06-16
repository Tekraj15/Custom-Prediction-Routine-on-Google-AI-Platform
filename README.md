# Custom-Prediction-Routine-on-Google-AI-Platform
# Project Overview
This peoject's objective is to deploy, and use a model on Google’s AI Platform. Normally, any model trained with the TensorFlow framework is quite easy to deploy, and you can simply upload a Saved Model on Google Storage, and create an AI Platform model with it. But, in practice, we may not always use TensorFlow. Fortunately, the AI Platform allows for custom prediction routines as well and that’s what we are going to focus on. Instead of converting a Keras model to a TensorFlow Saved Model, we will use the h5 ﬁle as is. Additionally, since we will be working with image data, we will use this opportunity to look at encoding and decoding of byte data into string for data transmission and then encoding of the received data in our custom prediction routine on the AI Platform before using it with our model.  

#Implementation Guideline

