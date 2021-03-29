# Supplementary material for the paper "Dynamical Aspect-Based Sentiment Analysis (DABSA) using SHAP values: Application to Macroeconomics"

You will find jupyter notebooks containing all the scripts used to get the results in the paper. 
The news article dataset can be downloaded from this Google drive link : [LeMondeNewsDataset](https://drive.google.com/file/d/12HAUtawOLkxfmWkrSbkXA6yn0195anV1/view?usp=sharing).

## Abstract

	Real-time information about the state of the economy is crucial for any economic agent, including governments, businesses and even households, that need to make rational decisions. 
	Several indexes reflecting the business cycle (BC) have emerged to provide timely information about the state of the economy, but they generally suffer from delays in survey data. 
	New approaches based on sentiment extracted from textual information from the internet, Twitter, or news agencies, for example, flourished to obtain real time economic indicators. 
	However, sentiment indicators are often opaque and difficult to interpret. In this paper, I propose the Dynamical Aspect-Based Sentiment Analysis (DABSA) algorithm, which rests on the sequential decomposition of global sentiment across several dimensions. 
	The decomposition is conducted using SHapley Additive exPlanations (SHAP) values, an implementation of Shapley values whose properties are aligned with this goal.  
	The advantage of DABSA is the construction of target-driven sequential sentiment indicators and clearer insight on what sentiment indicators are really capturing. 
	In my application, I used approximately 600,000 French news articles to build sentiment indicators associated with different aspects (dimensions) of the economy. 
	The decomposition provided seems to be consistent with empirical observations, making it an interesting tool for decision makers seeking early nowcasting of economic indicators. 
	Though I have focused on the application of DABSA to macroeconomics, the DABSA method is not domain-specific. It can be used whenever a sequential decomposition of a sentiment series is needed.

Submitted to the [18th International Conference on Principles of Knowledge Representation and Reasoning](https://kr2021.kbsg.rwth-aachen.de/).

## 1 [Sup] Simulations.ipynb: script for the Monte Carlo simulation
## 2 [Sup] LDA Aspect finding.ipynb: script for aspect identification
## 3 [Sup] Sentiment decomposition.ipynb: script for sentiment decomposition 
## 4 [Sup] Additional Graphics.ipynb : script for some graphics presented in the paper