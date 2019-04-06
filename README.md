# ICANN2019 - On the Interpretation of Recurrent Neural Networks as Finite State Machines
## Authors:
Christian Oliva - christian.oliva@estudiante.uam.es

Luis F. Lago-Fernández - luis.lago@uam.es

*Escuela Politécnica Superior, Universidad Autónoma de Madrid. 20849 Madrid, Spain*

## Description:
This repository contains all the results of the experiments described in our paper: the results for the complete set of ***Tomita Grammars*** for all described settings, including the activation color plots, the 2-dimensional Isomap projections of the hidden layer activation space and the extracted automata.

In this repo you can find all our final training log files for each network and the datasets used for train and test.

## Abstract:
The behavior of simple recurrent neural networks trained on regular languages is analyzed in terms of accuracy and interpretability. We use controlled amounts of noise and L1 regularization to obtain stable and accurate responses that are at the same time highly interpretable. We introduce a new shocking mechanism that reactivates silent neurons when learning stops due to an excessive regularization. Proper parameter tuning allows the networks to develop a strong generalization capacity, and at the same time provides solutions that may be interpreted as finite automata. Using a diverse set of regular languages as input, we observe that the trained networks display activation patterns that automatically cluster into a set of discrete states without any need to explicitly perform quantization. Analysis of the transitions between states in response to the input symbols reveals that the networks are in fact implementing a finite state machine that in all cases matches the regular expressionsused to generate the training data.
