# ADC-AE: A Hybrid Remaining Useful Life Prediction Method Combining Asymmetric Dual-Channel  Autoencoder  Networks and Nonlinear Stochastic Process
This is an open source repository of code for our Reliability Engineering & System Safety (RESS) submission.

Greetings, dear colleagues, we are conducting a research on a hybrid remaining useful life prediction model combining a novel autoencoder and the nonlinear Wiener process. This is my last research work during my doctoral studies. For me and my supervisor (Prof. Honghui Li), this research work is important. First of all, it is the result of my research work in which I spent two years at the Shuohuang railway site for data collection, problem formulation, solution development and algorithm implementation. In addition, the proposed model will be deployed and applied in a real railroad scenario. This is of very great practical and theoretical value for data-driven train wheel condition monitoring and health management. We sincerely hope that our manuscript will be noticed and recognized by the reviewers and the engineering community.

## Research Content
Inspired by the field of natural language process (NLP), this paper makes use of advanced semantic feature extraction structures combined with widely used long-dependency feature extraction structures on the encoding side of the autoencoder. Also, a novel autoencoder is proposed for the construction and acquisition of unsupervised health indicators.

In addition, to improve the reliability of the neural network prediction results (point estimation), we used the nonlinear Wiener process sequentially combined with the proposed autoencoder to achieve the estimation of the probability density distribution, i.e., the uncertainty measure, for mechanical parts.

## Research Results
To illustrate the effectiveness and accuracy of the proposed hybrid scheme, we conducted experiments on a private dataset (Railway wheel wear data) and a public dataset (NASA milling tool data).

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

## About Implementation code. 

To promote research in the field of remaining useful life prediction, we will open source the code after the manuscript review. The open source code consists of three main parts: 1. Data preprocessing; 2. Model code implementation (autoencoder and stochastic process) 3. Evaluation metrics and results plotting.

Once again, we very sincerely hope that the proposed hybrid prediction method will be recognized and noticed by the reviewers and the engineering community. Thank you very much.

## First Author Information
Yuhang Duan. He is currently working toward the Ph.D. degree in software engineering with Beijing jiaotong University, Beijing. His main research is on the adaptive construction of health indicator sequences using unsupervised learning models combined with machine learning or mathematical methods for RUL prediction.

More research work can be found in the following link:
https://scholar.google.com.hk/citations?hl=zh-CN&pli=1&user=2YjrAuAAAAAJ
