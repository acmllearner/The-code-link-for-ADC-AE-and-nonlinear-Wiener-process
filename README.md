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

The number of model parameters, model storage space and the average time for one network training epoch are compared and listed in the Tables.

<p align="center">
<img src=".\imgs\Railway_dataset_space-time_compare.jpg" height = "300" alt="" align=center />
<br><br>
<b>Table 1.</b> Comparison of model space-time overhead for Railway wear prediciton models.
</p>

<p align="center">
<img src=".\imgs\Milling_dataset_space-time_compare.jpg" height = "180" alt="" align=center />
<br><br>
<b>Table 2.</b> Comparison of model space-time overhead for Milling tool wear prediciton models.
</p>

## For RUL prediction evaluation metircs comparison. 

The number of RMSE, Score, ACC and MAPE are compared and listed in the Tables.

<p align="center">
<img src=".\imgs\Railway_dataset_RUL_prediction_compare.jpg" height = "300" alt="" align=center />
<br><br>
<b>Table 3.</b> Comparison of model RUL predition for Railway wear prediciton models.
</p>

<p align="center">
<img src=".\imgs\Milling_dataset_RUL_prediction_compare.jpg" height = "420" alt="" align=center />
<br><br>
<b>Table 4.</b> Comparison of model RUL predition for Milling tool wear prediciton models.
</p>
