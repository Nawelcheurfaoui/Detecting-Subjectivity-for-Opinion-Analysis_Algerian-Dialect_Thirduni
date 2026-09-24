# NLP Project — Algerian Facebook Posts

This repository contains my Master's project in **Web Technology and Information Systems** at University of Oran 1.

The project is about applying Natural Language Processing techniques to Facebook posts written in an Algerian context.

I originally worked on this project during my Master's degree. I'm now going back to the original notebook and updating the code so that it works with current versions of Python and the libraries used in the project.

## About the project

The dataset contains around 600 Facebook posts.

The posts are not written in one language. They can contain:

* Arabic
* Algerian Darija
* French
* Arabizi
* a mixture of several of these in the same post

For example, a single post can contain French, Arabic, numbers and Algerian expressions at the same time.

This was one of the main challenges of the project.

## What I worked on

The notebook goes through the different stages of the project:

1. Loading the data
2. Cleaning the text
3. Tokenization
4. Preprocessing Arabic / French / Arabizi text
5. Preparing the data for the model
6. Training a neural network
7. Evaluating the results
8. Testing the model on new input

The project uses techniques such as **TF-IDF and neural-network-based classification**.

## Updating the old code

The original notebook was written several years ago, so some of the libraries and functions it used are now outdated.

I'm currently going through the notebook and fixing these compatibility issues one by one.

For example, some old Keras imports no longer work with current versions of TensorFlow/Keras, and some o
