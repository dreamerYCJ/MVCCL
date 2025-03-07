# MVCCL
A multi-view cooperative-consistency contrastive learning framework for Birdsong Classification

# Abstract

Birdsong recognition plays a vital role in biodiversity research and conservation. Traditional classification model training relies on large amounts of labeled data, and annotating the recordings is labor-intensive and time-consuming, which poses a significant challenge for large-scale data applications. In this case, multi-view contrastive learning(MVCL) provides a solution by extracting informative features from existing data, reducing the number of labels required for downstream tasks. However, most existing MVCL methods are only used for self-learning within a view, focusing on a single level of contrast. To address the challenges, this paper proposes a multi-view cooperative-consistency contrastive learning framework (MVCCL) for birdsong recognition. Firstly, three kinds of spectrum features are extracted, including wavelet transform(WT) spectrogram, short-time Fourier spectrogram transform(STFT), and Hilbert–Huang transform(HHT) spectrogram, and each type of spectral feature is regarded as a view. Then, instance-level contrastive learning, cross-view cooperative contrastive learning, and cluster-level consistency contrastive learning are designed to strengthen discriminative features within each view, promote cooperative learning across views, and ensure the consistency of multi-view feature representations, respectively. The experiments are conducted on a self-built dataset and a public dataset, Birdsdata. The experimental results obtain classification accuracy of 97.19\% and 96.55\%, respectively for the two datasets, which are better than the existing methods. Notably, MVCCL achieved performances of 75.65\% and 70.10\% with only 5\% labeled data, verifying its effectiveness in low-sample scenarios. In conclusion, MVCCL can successfully capture rich cross-view common features and spectrogram details, provide a robust pre-training model, improves birdsong recognition, thereby supporting ecological research and biodiversity monitoring.

# Dataset

| Dataset Name | Link |
|------------|------|
| BirdData    | [Click to Access](https://pan.baidu.com/s/1mumSwDIu7RBDVVtoucZDpw?pwd=h23b) |

