---
title: Projects
nav: Projects
---

## Data Product Invention, Planning, Deployment, and Thought Leadership
** Clients ** : Northern Miner, Mining Intelligence, CostMine  
** Objectie ** : Combine CostMine and Mining Intelligence data, invent new products, design product interface, migrate the 
products and users to a cloud based solution.  

** Context **:  
The Northern Miner has been publishing mining industry news since 1915. Since then it has collected data on all aspects of mining
including mining cost models, labor costs, electric development, equipment, power, energy, materials, reagents, smelting and 
liberation facilities, taxes, transportation, commodity pricing, and ESG modelling.  

The data is used for Business Development, Market Assessment, Project and Company Evaluation, Due Diligence, and Academic Research.
For the most part, the data is trapped in TIFFs (digital image of news print), MS Word documents, MS Excel, and SQL data bases. 
To prevent data theft, the primary products delivered to clients are paper or pdf documents - limited or no access is permitted to 
the data. The data products are also somewhat disconnected and also repeat over the three different platforms, and very little of it is 
available on the cloud.

The project included create structured from unstructured


## 90 Days Cumulative Gas to Liquids Ratio Production Forecaster 
**Clients** : Price Waterhouse and TAQA  
**Objectives**: Use geologic models, reservoir engineering data, completions data, and production data to build a prediction model for development planning, budget building, and well location selection.  

**Context** :  
Production prediction for budgeting, or motivating a new well program is difficult. The difficulty is becuase there more than 150 different features to consider when predicting how a new well might perform. Industrial Data Science designed, managed, and delivered a LGR IP90 prediction tool for TAQA and PWC. The project to identified drilling and completion practices that maximize probability of success on an unconventional asset. Over 1000 wells, and 150 features, and over 1000 wells. Constructed data model, and after the Gradient Boost based model interrogation, the effective feature set contained 16 essential features. Used an interactive Jupyter Notebooks as a deliverable for development planning.  


## Failed Transmitter Detection Algorithms
**Client**: Canadian Natural Resources
**Objective**: Design an unsupervised algorithm that agnostically identifies transmitters that are entering a state that would cause a process upset or facility shutdown. 

**Context**:
Supervised ML CNRL Horizon Case: 
Process: process acting abnormally, operator notes problem, identifies and confirms the problem, solves the problem, and makes record of it.
Only a limited number of informed events available
Limited shelf life: atmospheric conditions and plant conditions are not static, they change continuously and impact operations
Has anyone matched atmospheric conditions (not just temperature) to xmitter behaviour?

UnSupervised ML CNRL Horizon Case: 
Process: process acting abnormally, operator notes problem, identifies and confirms the problem, solves the problem. No record made, no knowledge of cause.
This is the most likely case. When the plant is upset, the operators have too many issues to manage to be able to make note of problems. 
Sidebar: How many xmitters are in the plant?
The classic data science modeling approach extracts a batch of data, fits a model to the batch, apply this  for prediction using new data. This is called batch processing. 
Currently state of freeze detection algorithm uses batch approach on supervised models and unsupervised models.
This doesn’t work well with streaming data:
Operating conditions change continuously due to instrument drift, changing operating conditions
Constant cycle: remodel -> retest -> redeploy cycle. 
Tedious, and accident prone
Progressing toward a purely automated approach that recalibrates after an upset, or when drift is excessive. 


## Experimental Design Driven Development, Drilling, and COmpletion Program 
**Client**: TransGlobe Energy

## Hydrogeologic Facies Model for Contaminant Plume Modelling
** Client **:

## Cloud Base Business Development Tool. 

## Geologic Mdel

nitial The Variable Frequency Drive Project
First Project

▪	Designed, managed, and delivered a LGR IP90 prediction tool for TAQA and PWC. The project to identified drilling and completion practices that maximize probability of success on an unconventional asset. Over 1000 wells, and 150 features. Constructed data model, and after the Gradient Boost based model interrogation, the effective feature set contained 16 essential features. Used an interactive Jupyter Notebooks as a deliverable for development planning.  
▪	Built hydrogeologic models for oilsands tailing ponds and constructed contaminant plume models. 
▪	Invented and sold custom algorithms that detected and classified anomalous streaming Distributed Control System (DCS) transmitter signals and prevented plant shutdowns using algorithms included KNN, gradient boost, logistic regression, LDA, QDA, AI (keras/tensorflow). 
▪	Processed SCADA streaming data from variable frequency drive PCP pumps on a water flood project to provide water cut and power consumption using AI (Keras). 
▪	Built and sold an AWS cloud-based pipeline risk assessment and business development tool for identifying and classifying clients that risked missing production volumes, or pipeline assets by produced corrosive fluids. Python and SKLearn were used to write all the backend computational components, and Java for the front end and rendering components. 
▪	Directed the construction of a cloud-based Azure data repository for multiple clients.
▪	Built the finance and operations model to gain $63MM of support to purchase a cogeneration facility.
