# deep-learning-X-rays
Deep learning algorithm that can detect pneumonia from chest X-rays

Presented is a deep convolutional neural network aimed at correctly classifying pathologies
in the thorax region. Using a small dataset of 2763 chest x-rays, the purpose is to
examine whether it is achievable to reach performance close to the CheXpert paper (shorturl.at/hkDLW) using a fraction
of the dataset. Motivated by addressing the current time- and computational power consuming CNN architectures, improving the
existing foundations of CNN based on moderate size datasets is essential to be able to quantify the performances of
current CNN.


# data
For this study, a publicly available dataset from https://bit.ly/325jISB is used. Collection of the dataset was done by extracting observations
from radiology reports. The dataset contains 224,316 chest radiographs of 65,240 patients and were labelled for the
presence or absence of 14 thoracic diseases. The CheXpert dataset consist of 14 labelled observations and are not mutually
exclusive. By random sampling, a total of 2763 images are picked.


