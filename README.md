> **If you use the resources (algorithm, code and dataset) presented in this repository, please cite our paper.**  
*The BibTeX entry is provided at the bottom of this page. 

# RUP: Large Room Utilisation Prediction with Carbon Dioxide Sensor
Human occupancy information is crucial for any modern Building Management System (BMS). Implementing pervasive sensing and leveraging Carbon Dioxide data from BMS sensor, we present large Room Utilisation Prediction with carbon dioxide sensor (RUP), a novel way to estimate the number of people within a closed space from a single carbon dioxide sensor. RUP de-noises and pre-processes the carbon dioxide and indoor human occupancy data. We utilise both seasonal-trend decomposition based on Loess and seasonal-trend decomposition with moving average to factorise both datasets. For each trend, seasonal and irregular component, we model different regression algorithms to predict each respective human occupancy component value. We propose a zero pattern adjustment model to increase the accuracy and finally, we use additive decomposition to reconstruct the prediction value. We run our model in two different locations that have different contexts. The first location is an academic staff room and the second is a cinema theatre with up to 300 people. Our results show an average of 4.33% increment in accuracy for the small room with 94.68% indoor human occupancy counting and 8.46% increase for the cinema theatre in comparison to the accuracy of the baseline method, support vector regression.

![alt text](https://github.com/cruiseresearchgroup/RUP-Large-Room-Utilisation-Prediction/blob/master/images/rup.jpg)

This repository contains resources developed within the following paper:

	Arief-Ang, I.B., Salim, F.D. and Hamilton, M., 2018. RUP: Large Room Utilisation Prediction with carbon dioxide sensor. 
	Pervasive and Mobile Computing, 46, pp.49-72. 

You can find the [paper](https://github.com/cruiseresearchgroup/RUP-Large-Room-Utilisation-Prediction/blob/master/paper/ariefang2018rup.pdf) in this repository. 

Alternative link: https://www.sciencedirect.com/science/article/pii/S1574119217303930

## Contents of the repository
This repository contains resources used and described in the paper.

The repository is structured as follows:

- `code/`: Code implementation and evaluation of RUP.  
- `data/`: Preprocessed dataset used for this paper. 
- `paper/`: Formal description of the algorithm and evaluation result. 

## Possible Applications

## Citation
If you use the resources presented in this repository, please cite (using the following BibTeX entry):
```
@article{ariefang2018rup,
title = "RUP: Large Room Utilisation Prediction with carbon dioxide sensor",
journal = "Pervasive and Mobile Computing",
volume = "46",
pages = "49 - 72",
year = "2018",
issn = "1574-1192",
doi = "https://doi.org/10.1016/j.pmcj.2018.03.001",
url = "http://www.sciencedirect.com/science/article/pii/S1574119217303930",
author = "Irvan B. Arief-Ang and Margaret Hamilton and Flora D. Salim",
keywords = "Ambient sensing, Building occupancy, Presence detection, Number estimation, Cross-space modelling, Contextual information, Human occupancy detection, Carbon dioxide"
}
```
