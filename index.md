<p align="center">
  <img width="50%" height="auto" src="resources/fig1.png">
</p>
<p align="center">
In applications such as weather forecasting and the prevention of natural disasters, the analysis of meteorological data is critical. In this work, given a large amount of continuous meteorological data from neighbouring regions, we transform the data analysis into an anomaly detection task. We utilize past data from neighbouring sites to predict the target site's current weather data, and then a framework is constructed for analysis and locating the outliers. 
</p>


# Overview

<p align="center">
  <img width="70%" height="auto" src="resources/fig4.png">
</p>
<p align="center">
In applications such as weather forecasting and the prevention of natural disasters, the analysis of meteorological data is critical. In this work, given a large amount of continuous meteorological data from neighbouring regions, we transform the data analysis into an anomaly detection task. We utilize past data from neighbouring sites to predict the target site's current weather data, and then a framework is constructed for analysis and locating the outliers. 
</p>


<p align="center">
  <img width="50%" height="auto" src="resources/fig5.png">
</p>
<p align="center">
In applications such as weather forecasting and the prevention of natural disasters, the analysis of meteorological data is critical. In this work, given a large amount of continuous meteorological data from neighbouring regions, we transform the data analysis into an anomaly detection task. We utilize past data from neighbouring sites to predict the target site's current weather data, and then a framework is constructed for analysis and locating the outliers. 
</p>

In this paper, we propose a novel unsupervised domain adaptation based segmentation network for COVID-19 CT infection segmentation task. The contributions of this paper can be summarized as follows: (1) we propose to make full use of synthetic data and limited unlabeled real COVID-19 CT images to jointly train the segmentation network, so as to introduce richer diversity; (2) we design a domain adaptation module to align the two domains and overcome the domain shift. It effectively improves the generalization capability of segmentation network; (3) we propose an unsupervised adversarial training scheme, in which the cross-domain adversarial loss will guide the segmentation network to learn domain-invariant feature, thus improving the segmentation performance. In the meanwhile, our training scheme is very flexible, as it can be arbitrarily combined with any segmentation network with encoder-decoder structure.

# COVID-19 CT Infection Segmentation Results
<p align="center">
  <img width="80%" height="auto" src="resources/fig2.png">
</p>
<p align="center">
Qualitative results for two-class segmentation task. Columns 1 and 2 present the input real COVID-19 CT images and corresponding ground truth, while Column 6 is the segmentation result of our proposed method. The first to last rows are the results when taking ground-glass opacity (a), consolidation (b), infection (c) and the lung (d) as the segmentation object, respectively.
</p>

<p align="center">
  <img width="80%" height="auto" src="resources/fig3.png">
</p>
<p align="center">
Qualitative results for multi-class segmentation task. Columns 1 and 2 show the input real COVID-19 CT images and corresponding ground truth, in which the ground-glass opacity is marked in blue, consolidation is marked in green, and the lung is marked in red. Columns 7 is the segmentation result for our proposed method.
</p>

# Acknowlegements
This research work is supported by the Air Force Office of Scientific Research (award number FA2386-19-1-4001).

# Citation
```
@article{chen2022unsupervised,
  title={Unsupervised domain adaptation based COVID-19 CT infection segmentation network},
  author={Chen, Han and Jiang, Yifan and Loew, Murray and Ko, Hanseok},
  journal={Applied Intelligence},
  volume={52},
  number={6},
  pages={6340--6353},
  year={2022},
  publisher={Springer}
}
```
