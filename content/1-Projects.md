---
title: Projects
nav: Projects
layout: default
---

The projects below are a high level scoping of some of the projects we have completed and are listed chronologically(ish).

## Data Product Invention, Planning, Deployment, and Thought Leadership
#### Clients  
Northern Miner, Mining Intelligence, CostMine  

#### Objective  
Combine CostMine and Mining Intelligence data, invent new products, design product interface, migrate the 
products and users to a cloud based solution.  

#### Context  
The Northern Miner has been publishing mining industry news since 1915. Since then it has collected data on all aspects of mining
including mining cost models, labor costs, electric development, equipment, power, energy, materials, reagents, smelting and 
liberation facilities, taxes, transportation, commodity pricing, and ESG modelling.  

The data is used for Business Development, Market Assessment, Project and Company Evaluation, Due Diligence, and Academic Research.
For the most part, the data is trapped in TIFFs (digital image of news print), MS Word documents, MS Excel, and SQL data bases. 
To prevent data theft, the primary products delivered to clients are paper or pdf documents - limited or no access is permitted to 
the data. The data products are also somewhat disconnected and also repeat over the three different platforms, and very little of it is 
available on the cloud.  


## 90 Days Cumulative Gas to Liquids Ratio Production Forecaster 
#### Clients  
Price Waterhouse and TAQA  

#### Objectives  
Use geologic models, reservoir engineering data, completions data, and production data to build a prediction model 
for development planning, budget building, and well location selection.  

#### Context    
Production prediction for budgeting, or motivating a new well program is difficult. The difficulty is becuase there more than 
150 different features to consider when predicting how a new well might perform. Industrial Data Science designed, managed, 
and delivered a LGR IP90 prediction tool for TAQA and PWC. The project to identified drilling and completion practices 
that maximize probability of success on an unconventional asset. Over 1000 wells, and 150 features, and over 1000 wells.
Constructed data model, and after the Gradient Boost based model interrogation, the effective feature set contained 17 
essential features. Used an interactive Jupyter Notebooks as a deliverable for development planning.  


## Frozen Transmitter Detection Algorithms
#### Client  
Canadian Natural Resources

#### Objective  
Design supervised and unsupervised algorithms that agnostically identify transmitters that are entering a state that
would cause a process upset or facility shutdown. The transmitters could be pressure, flow, or level transmitters.  

#### Context  
Supervised data volumes (also called training data) have the transmitter signal and the companion operating state of the transmitter classified as normal, upset,
or frozen. Unsupervised data volumes have only transmitters signal data. Typical data science workflow is to train a model on 
the supervised data and apply the trained model to the unsupervised data volumes. Unfortunately, this generalized approach could not
be applied:

1. Every processing train presented a different transmitter signal, there are hundreds of processing trains, thousands of 
transmitters, and the data is collected by the second. 

2. Building supervised signal and operating state data volumes is hard. Somebody has to review the data, find an anomolous signal, 
and classify the operating state. This process has to be completed thousands of times to build a reliable library of data for training. 

Ideally a two stage algorithm would be applied where a first pass would identify anomolous signals, and a second pass would self train 
the training set. A short project turnaround time prevented investigating this solution. Instead a signal sensing algorithm was devised
that detected anomolous signals on unsupervised data in a streaming fashion. 


## Use Variable Frequency Drive Data to Predict Water Cut
#### Client  
Private

#### Objective  
Write up to be completed

#### Context  
Write up to be completed


## Prevent Rotor Failures on Variable Frequency Drive Managed Production Pumps 
#### Client  
TransGlobe Energy

#### Objective  
Write up to be completed

#### Context  
Write up to be completed


## Experimental Design Driven Development, Drilling, and Completion Program 
#### Client  
TransGlobe Energy

#### Objective  
Write up to be completed

#### Context  
Write up to be completed

