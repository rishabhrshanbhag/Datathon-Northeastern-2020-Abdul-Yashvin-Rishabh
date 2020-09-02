SIR Model for New York COVID-19 Pandemic. (Datathon-Northeastern-2020-Abdul-Yashvin-And-Rishabh)
====================================================

 In this Repository we try to fit a set of equations to the Coronavirus data to retrieve the factors affecting the rate of death and recovery in New York.
 
 The parameters affecting the rate of change of deaths and recovery.
 
Rate of change from Exposed to Infected: 0.49 <br />
Rate of change from Infected to Recovered: 0.19 <br />
Rate of change from Infected to Critical: 0.076-0.099 <br />
Rate of change from Critical to Recovered: 0.125-0.19 <br />
Rate of change from Critical to Death: 0.16 <br />
Probability from Infected to Critical: 0.09 <br />
Probability from Critical to Death: 0.79 <br />
Probability from Infected to Recovered: 0.91 <br />
Probability from Critical to Recovered: 0.21 <br />

To Run the code use Anaconda Jupyter Notebook

EDA.ipynb contains the EDA performed on a few datasets we downloaded to explore and analyse data to get project ideas.

SIR.ipynb contains the main code with the derived equations. <br />
in this we have written equations which will be made to fit the curve of the real data to find out the parameters affecting the impact of this pandemic.

We have referred to the following article to help us understand SIR models and implement it. <br />
https://towardsdatascience.com/infectious-disease-modelling-part-i-understanding-sir-28d60e29fdfc
