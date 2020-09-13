# Deep Anomaly Detection in Hyperspectral Images Based on Membership Maps and Object Area Filtering

In this paper, we propose a novel framework for transferred deep learning-based anomaly detection in hyperspectral images. The proposed framework includes five main steps. First, the image’s spectral dimension is reduced by applying the principal component analysis (PCA). A convolutional neural network (CNN)-like deep network is then trained using only one image to learn the pixels’ similarities in a picture. This learned is applied to extract objects in the image using connected component filtering. Next, irrelevant objects are removed by comparing their area to an acceptable anomaly area range. The final result is obtained by multiplying the network output and binary map of anomalies. Extensive experimental evaluations demonstrate that the proposed framework substantially outperforms a significant number of comparable state-of-the-art methods. Finally, we empirically verify that the deep network exhibits excellent domain adaptability.

------------

For dataset you can contact me by E-mail: mahdi.yousofun@gmail.com
