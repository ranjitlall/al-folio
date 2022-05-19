---
layout: page
permalink: /software/
title: software
description:
nav: true
---

**[MIDASverse](https://github.com/MIDASverse): fast and accurate missing-data imputation with deep learning**

The MIDASverse, developed with Thomas Robinson and Alex Stenlake, is a suite of software packages for efficiently imputing missing data using deep learning methods in Python (**MIDASpy**) and R (**rMIDAS**). The packages implement a recently developed approach to multiple imputation known as MIDAS, which involves introducing additional missing values into the dataset, attempting to reconstruct these values with a type of unsupervised neural network known as a denoising autoencoder, and using the resulting model to draw imputations of originally missing data. These steps are executed by a fast and flexible algorithm that offers significant accuracy and efficiency advantages over other multiple imputation strategies, particularly when applied to large datasets with complex features.

On the method underlying the software, see:

Lall, Ranjit, and Thomas Robinson. 2022. "[The MIDAS Touch: Accurate and Scalable Missing-Data Imputation with Deep Learning](https://ranjitlall.github.io/assets/pdf/Lall%20and%20Robinson%202022%20PA.pdf)." Political Analysis 30, no. 2: 179-196.
