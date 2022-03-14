# ML_Crypto_Investments

This Python application is to analyze cryptocurrency investments via Machine Learning (ML). This program runs within Jupyter Lab.
It performs investment planning analysis and is developed to assemble investment portfolios based on cryptocurrency. Using ML, 
it enables the investigation of other factors that might impact the crypto market.

Line and Scatter Plots are created to visualize the information for better understanding and decision making.


## Technologies

This application incorportates the following required 6 dependancies to run:

*import pandas as pd*
*import hvplot.pandas*
*from path import Path*
*from sklearn.cluster import KMeans*
*from sklearn.decomposition import PCA*
*from sklearn.preprocessing import StandardScaler*


## Installation Guide

The following installation must be performed before running the program. It include:


**Installations:**

scikit-learn: check to verify installation using `conda list scikit-learn`. Otherwise,
`install scikit-learn`

hvplot: check to verify installation using `conda list hvplot`. Otherwise,
`install hvplot`


## Usage

To run this application, create a clone on the local desktop. Then, initiate your conda environment and 
open file in Jupyter Lab.

Resources folder contains `Crypto Market Data` as a CSV file.

This plot "Crypto Market Price Change Percentage by Time Periods" illustrates the data within the DataFrame.

<img width="740" alt="Crypto Market Data Plot" src="https://user-images.githubusercontent.com/93550651/157989807-7270a485-e52e-45be-a7df-87bac97d0347.png">


The "Elbow Curve" line plots shows the best values for 'k' and compares between the Original Data and the Primary Component Analysis data.
<img width="1294" alt="Elbow Curves" src="https://user-images.githubusercontent.com/93550651/157989948-658d9e8e-7a92-42e1-be02-89ee51191555.png">


These Scatter plots give a visual analysis of data point for the Original Data and PCA data. 
<img width="1294" alt="Elbow Curves" src="https://user-images.githubusercontent.com/93550651/157990065-8a6f4724-33e1-4e0a-a6c3-890210d2f16f.png">


## Contributors

Contributor: John Batarse  

Email: jbatarse@hotmail.com

LinkedIn: [Find me on LinkedIn](<https://www.linkedin.com/in/john-a-batarse-760a26116/>)


## License

Trilogy Education LLC. and UC Berkeley
