# ADC-AE: A Hybrid Remaining Useful Life Prediction Method Combining Asymmetric Dual-Channel  Autoencoder  Networks and Nonlinear Stochastic Process
This is an open source repository of code for our Reliability Engineering & System Safety (RESS) submission.

We are conducting a research on a hybrid remaining useful life prediction model combining a novel autoencoder and the nonlinear Wiener process.

## Research Content
Inspired by the field of natural language, this paper makes use of advanced semantic feature extraction structures combined with widely used long-dependency feature extraction structures on the encoding side of the autoencoder. Also, a novel autoencoder is proposed for the construction and acquisition of unsupervised health indicators.

In addition, to improve the reliability of the neural network prediction results (point estimation), we used the nonlinear Wiener process sequentially combined with the proposed autoencoder to achieve the estimation of the probability density distribution, i.e., the uncertainty measure, for mechanical parts.

## Research Results
To illustrate the effectiveness and accuracy of the proposed hybrid scheme, we conducted experiments on a private dataset (Railway wheel wear data) and a public dataset (NASA milling tool data).

We performed experimental validation and comparison on two datasets.

## For space-time overhead comparison. 
<p align="center">
<img src=".\img\Railway_dataset_space-time_compare.jpg" height = "360" alt="" align=center />
<br><br>
<b>Figure 1.</b> The architecture of Informer.
</p>

The number of model parameters, model storage space and the average time for one network training epoch are compared and listed in the Tables.

## For RUL prediction evaluation metircs comparison. 

The number of RMSE, Score, ACC and MAPE are compared and listed in the Tables.
