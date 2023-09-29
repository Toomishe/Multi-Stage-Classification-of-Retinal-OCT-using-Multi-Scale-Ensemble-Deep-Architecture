# Multi-Stage-Classification-of-Retinal-OCT-using-Multi-Scale-Ensemble-Deep-Architecture
This work proposes a multi-stage classification network built on multi-scale (pyramidal) feature ensemble architecture for retinal image classification using optical coherence tomography (OCT) images.
Accurate noninvasive diagnosis of retinal disorders is required for appropriate treatment 
or precision medicine. This work proposes a multi-stage classification network built on multi-scale 
(pyramidal) feature ensemble architecture for retinal image classification using optical coherence 
tomography (OCT) images. First, a scale adaptive neural network is developed to produce multi-scale 
inputs for feature extraction and ensemble learning. The larger input sizes give more global informa- 
tion, while the small input sizes focus on local details. Then, feature-rich pyramidal architecture is 
designed to extract features from multi-scale as inputs using DenseNet as the backbone. The advan- 
tage of the hierarchical structure is that it allows the system to extract multi-scale information-rich 
features for the accurate classification of retinal disorders. Evaluation on two public OCT data sets 
containing normal and abnormal retinas (e.g., diabetic macular edema (DME), choroidal neovascular- 
ization (CNV), age-related macular degeneration (AMD), and Drusen) and comparison against recent 
networks demonstrate the advantages of the proposed architecture’s ability to produce feature-rich 
classification with an average accuracy of 97.79%, 96.83%, and 94.26% for the first (binary) stage, 
second (3-class) stage, and all-at-once (4-class) classification, respectively using cross-validation 
experiments using the first data set. In the second data set, our system showed an overall accuracy, 
sensitivity, and specificity of 99.69%, 99.71%, and 99.87%, respectively. Overall, the tangible advan- 
tages of the proposed network for enhanced feature learning might be used for various medical 
image classification tasks where scale-invariant features are crucial for precise diagnosis.
