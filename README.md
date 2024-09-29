# ECE535-Project

Group Members: David Nguyen, Jonathan Wang, Truong Son Vu

Project Choice #5 Federated Learning on Heterogeneous Sensor Data

Motivation: 
* We are motivated to gain an intuition about the impacts of data on machine learning from understanding how data heterogeneity affects federated learning
* Has a security component (performing adversarial attacks) which is interesting

Design goal:
* Characterize the impact of heterogeneity on FL. Then doing the same characterization under adversarial conditions.

Deliverables::
* Implementations of FL with different datasets and different levels of heterogeneity and characterizing them
* Characterization of FL after some adversarial attacks
* Comparisons between the adversarial vs non-adversarial settings and the impact of heterogeneity on them

System blocks:
![Untitled presentation (2)-1](https://github.com/user-attachments/assets/2ed4ae24-417d-4f5c-8096-4d6f97d6d430)

HW requirement:
* Computer with CUDA-enabled GPU/ Google Collab

SW requirement:
* Python, Jupyter Notebook

Team Member lead roles:
* David: software, algorithm design
* Jonathan: setup, writing
* Truong: research

Team member responsibilities:
* Jonathan - (1)(5)
* Sam - (4)(5)
* David - (2)(3)

* Work to be done:
  * Research types of adversarial attacks (1)
  * Implement FL with different datasets (2)
  * Feed the FL with different levels of heterogeneity (3)
  * Characterize each FL model after each test (4)
  * Compare each test (5)

References:
* Communication-Efficient learning of deep networks from decentralized data (http://
proceedings.mlr.press/v54/mcmahan17a/mcmahan17a.pdf)

* Example codes for different data partionings https://github.com/SMILELab-FL/FedLab/tree/master/tutorials/
Datasets-DataPartitioner-tutorials ( https://arxiv.org/pdf/2303.17580)
