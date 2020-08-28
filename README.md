# serialization-and-deserialization
Machine learning models Serialization and deserialization using JSON,pickle,joblib,yamel and manual methods. 
Here, will see the different ways to interact with JSON with Python, pickl, dill, joblib and yaml. 
Serialization is the process of translating data structures or object state into a format that can be stored (for example, in a file or memory buffer) or transmitted and reconstructed later. 
In serialization, an object is transformed into a format that can be stored, so as to be able to deserialize it later and recreate the original object from the serialized format in the context of data storage. 
There are a few ways to put trained machine learning (ML) models into production. The most common method is to serialize the model using some particular format after training, and deserialize that model in the production environment. 
The common methods for serializing and deserializing methods are  JSON, Pickle, Joblib. 
## Json: 
## Installation : pip insatll json
Any Python object can be serialized into JSON format and vice versa. 

## Pickle 
## Installation : pip insatll pickle
Pickling is the process whereby a Python object hierarchy is converted into a byte stream (usually not human readable) to be written to a file, this is also known as Serialization. Unpickling is the reverse operation, whereby a byte stream is converted back into a working Python object hierarchy. 

# Joblib : 
## Insatlaltion :pip install joblib
The first tool we describe is pickle the standard Python tool for object (de)serialization. Afterwards, we look at the joblib library which offers easy (de)serialization of objects containing large data arrays, and finally we present a manual approach for saving and restoring objects to/from JSON (JavaScript Object Notation). None of these approaches represents an optimal solution, but the right fit should be chosen according to the needs of your project. 

# YAML 
## Installation : pip install pyyaml
YAML is my favorite format. It is a human-friendly data serialization format. Unlike Pickle and JSON, it is not part of the Python standard library, so you need to install it 

# dill: 

The dill package extends the functionality of pickle by enabling the serialization of a much larger set of Python objects. 

# Deep larning models serialization and deserialization
pima_indian_diabets.csv used for demonstrating deep learning models using YAML and .h5  serializing deserializing models

