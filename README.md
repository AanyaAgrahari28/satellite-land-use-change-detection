# AI-Based Satellite Land Use Classification and Environmental Change Detection

This project uses Convolutional Neural Networks (CNN) to classify satellite images and detect environmental changes between two images taken at different times.

## Features
- CNN-based **satellite land type classification**
- Comparison between **baseline and improved CNN models**
- Detection of **land-use transitions** (e.g., forest → residential)
- **Risk score estimation** based on model confidence
- Interactive analysis using uploaded images

## Land Types Detected
AnnualCrop, Forest, HerbaceousVegetation, Highway, Industrial, Pasture, PermanentCrop, Residential, River, SeaLake

## Model Development
Two CNN models were developed:

- **Model A – Baseline CNN**
- **Model B – Improved CNN with dropout and optimized parameters**

Model B achieved better performance and is used for the final system.

## Environmental Change Detection
The system compares two satellite images and detects land-use transitions.

Example:
Forest → Residential
Detected Transition: Natural → Built-Up
Interpretation: Urban Expansion

## Technologies
Python, TensorFlow/Keras, CNN, Google Colab
