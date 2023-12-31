Big-Data-Activity-Recognition-Classification-
![image](https://github.com/himanshusharma-30/Big-Data-Activity-Recognition-Classification-/assets/118366451/d773e095-9d59-493a-8050-0fa3d14622b8)

This project aims to tackle classification tasks by leveraging the power of predictive analysis on sensor data generated by a Wireless Sensor Network (WSN).
We will decipher and classify user activities, such as bending, sitting, cycling, from the intricate patterns embedded in the WSN data
By focusing on activity classification, pave the way for applications that transcend mere data analysis, opening avenues for personalized user experiences and optimized system responses

AReM Dataset Overview:
Purpose: Benchmark for Activity Recognition applications using a Wireless Sensor Network (WSN).
Task: Predict user activity from time-series RSS data generated by WSN nodes.
Data Source: RSS measurements from IRIS nodes (IEEE 802.15.4 standard) on the user's chest and ankles, using a modified Spin token-passing protocol.
Sampling: 5 RSS samples per epoch (20 Hz) for each of the three node pairs (Chest-Right Ankle, Chest-Left Ankle, Right Ankle-Left Ankle).
Features: Mean and standard deviation of RSS readings for each node pair.
Epoch Duration: 250 milliseconds.
Dataset Composition: 480 sequences of input RSS data, with 15 temporal sequences per activity, totaling 42240 instances.
Activities: Includes standard activities and two types of bending activities as specified in additional documentation (bendingTupe.pdf and sensorsPlacement.pdf).
Dataset Source: https://archive.ics.uci.edu/dataset/366/activity+recognition+system+based+on+multisensor+data+fusion+arem

Logical Approach
Data Acquisition with Python: Streamlining the process of sourcing and importing data.
Data Integration & Preprocessing with PySpark: Merging disparate data sources and cleaning datasets to ensure quality and consistency.
Data Visualization with PySpark: Employing graphical representations to uncover patterns and insights.
Dataset Partitioning in PySpark: Segregating data into training and test sets for model validation.
Model Development: Implementing Decision Trees, Random Forests, and Multilayer Perceptrons for classification tasks.
Pipeline Configuration in PySpark: Setting up data transformation and model training workflows.
Model Training: Fine-tuning model parameters and fitting to the training data.
Model Performance Evaluation: Assessing accuracy, precision, recall, and F1 scores.
Making Predictions: Applying trained models to test data for activity recognition.
Results Analysis & Model Comparison: Evaluating model outputs and comparing efficacy.

