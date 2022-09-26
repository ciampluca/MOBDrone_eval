# MOBDrone Dataset Evaluation

Code for evaluate the MOBDrone Dataset, accepted at ICIAP 2021 [[Pre-print PDF](https://arxiv.org/pdf/2203.07973.pdf)].

The MOBDrone benchmark is a large-scale drone-view dataset suitable for detecting persons overboard. We publicly release this dataset in the Zenodo repository [[Zenodo Link](https://zenodo.org/record/5996890#.YzGj035BxhE)]. 

In this repository we provide a jupyter notebook to reproduce some results reported in our paper.
To run the code, install the required dependencies listed in the requirements.txt file, and put the json files containing the computed predictions in the 'predictions' folder (you can download the predictions [here](https://drive.google.com/file/d/1fPc8EaryKfr6nq_K_XpSgG-PJMXT7x4Z/view?usp=sharing)).

For further information about the dataset and other resources see also this [page](http://aimh.isti.cnr.it/dataset/mobdrone/).


## Reference
If you found this code useful, please cite the following paper:

> @inproceedings{MOBDrone2021,  
title={MOBDrone: {A} Drone Video Dataset for Man OverBoard Rescue},  
author={Donato Cafarelli and Luca Ciampi and Lucia Vadicamo and Claudio Gennaro and Andrea Berton and Marco Paterni and Chiara Benvenuti and Mirko Passera and Fabrizio Falchi},  
booktitle={Image Analysis and Processing - {ICIAP} 2022 - 21st International
               Conference, Lecce, Italy, May 23-27, 2022, Proceedings, Part {II}},  
series={Lecture Notes in Computer Science},  
publisher={Springer},  
year={2022},  
publisher={Springer International Publishing},  
volume={13232},  
pages={633--644},  
url={https://doi.org/10.1007/978-3-031-06430-2\_53},  
doi={10.1007/978-3-031-06430-2\_53},  
}

