# Multi-Stage-Classification-of-Retinal-OCT-using-Multi-Scale-Ensemble-Deep-Architecture
This work proposes a multi-stage classification network built on multi-scale (pyramidal) feature ensemble architecture for retinal image classification using optical coherence tomography (OCT) images.

https://www.mdpi.com/2381154

The work has been published via https://www.mdpi.com/2381154

Citing this work
If you use our implementation for academic research, you are highly encouraged to cite our paper.

@Article{bioengineering10070823,
AUTHOR = {Akinniyi, Oluwatunmise and Rahman, Md Mahmudur and Sandhu, Harpal Singh and El-Baz, Ayman and Khalifa, Fahmi},
TITLE = {Multi-Stage Classification of Retinal OCT Using Multi-Scale Ensemble Deep Architecture},
JOURNAL = {Bioengineering},
VOLUME = {10},
YEAR = {2023},
NUMBER = {7},
ARTICLE-NUMBER = {823},
URL = {https://www.mdpi.com/2306-5354/10/7/823},
PubMedID = {37508850},
ISSN = {2306-5354},
ABSTRACT = {Accurate noninvasive diagnosis of retinal disorders is required for appropriate treatment or precision medicine. This work proposes a multi-stage classification network built on a multi-scale (pyramidal) feature ensemble architecture for retinal image classification using optical coherence tomography (OCT) images. First, a scale-adaptive neural network is developed to produce multi-scale inputs for feature extraction and ensemble learning. The larger input sizes yield more global information, while the smaller input sizes focus on local details. Then, a feature-rich pyramidal architecture is designed to extract multi-scale features as inputs using DenseNet as the backbone. The advantage of the hierarchical structure is that it allows the system to extract multi-scale, information-rich features for the accurate classification of retinal disorders. Evaluation on two public OCT datasets containing normal and abnormal retinas (e.g., diabetic macular edema (DME), choroidal neovascularization (CNV), age-related macular degeneration (AMD), and Drusen) and comparison against recent networks demonstrates the advantages of the proposed architecture’s ability to produce feature-rich classification with average accuracy of 97.78%, 96.83%, and 94.26% for the first (binary) stage, second (three-class) stage, and all-at-once (four-class) classification, respectively, using cross-validation experiments using the first dataset. In the second dataset, our system showed an overall accuracy, sensitivity, and specificity of 99.69%, 99.71%, and 99.87%, respectively. Overall, the tangible advantages of the proposed network for enhanced feature learning might be used in various medical image classification tasks where scale-invariant features are crucial for precise diagnosis.},
DOI = {10.3390/bioengineering10070823}
}

The work has been funded by CEAMLS Morgan State University
