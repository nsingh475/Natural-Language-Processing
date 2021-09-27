# Named-Entity-Recognition
Named-entity recognition (NER) is a form of natural language processing that tries to locate and classify named entities mentioned in unstructured text into pre-defined categories such as name of a person, organizations, locations, time etc.
For Eg: In the senntence - "I hear Delhi is wonderful in winters." NER identifies that Delhi is a place and winter is some time of a year.
It does not evaluate wheather or not a given text is true or logical. 

Named entity recognition is not only a standalone tool for information extraction, but it also an invaluable preprocessing step for many downstream natural language processing applications like machine translation, question answering, and text summarization. 


### How does NER work
It involves two steps:
1. Detection of a named entity 
2. Categorization of the entity

To learn what is and is not a relevant entity and how to categorize them, a model requires training data. For this, we have to define our entities and our categories. Once this is done, we can use these to label data and create a training dataset. We then use this training dataset to train an algorithm to label your text predictively.



### Project implementation and workflow
Following are the subtasks of the project:
1. Import Modules
2. Load and Explore the NER Dataset
3. Retrieve Sentences and Corresponding Tags
4. Define Mappings between Sentences and Tags
5. Padding Input Sentences and Creating Train/Test Splits
6. Build and Compile a Bidirectional LSTM Model
7. Train the Model
8. Evaluate Named Entity Recognition Model

I am using the Keras API with TensorFlow as its backend to build and train a bidirectional LSTM neural network model to recognize named entities in text data.
