# Optimal CNN Architecture for Emotion Detection

## Introduction

Convolutional neural networks (CNNs) have been pivotal in image classification since the 1980s. Originally using kernels to detect patterns through convolutions, modern CNNs have evolved into specialized sub-architectures like Channel Boosted, SE Net, and ResNet families. This report assesses these modern CNN families through a literature review and application to the "Facial Recognition Dataset" from Kaggle. It concludes that channel learning is crucial for image classification.

**Research Questions:**
1. What are the strengths and weaknesses of each sub-CNN architecture?
2. Which architecture performs best in image recognition and why?
3. What factors contribute to the best architecture's performance (e.g., accuracy, runtime)?
4. When are other architectures suitable besides the top performer?
5. Can combining these architectures yield superior performance?

## Background and Related Work

Convolutional Neural Networks (CNNs) have revolutionized the field of computer vision, particularly in emotion detection from facial expressions. Originally developed in the 1980s, CNNs have evolved from simple kernel-based image classifiers to sophisticated architectures capable of capturing complex features crucial for accurate emotion recognition. This section explores how CNNs have been applied specifically to emotion detection tasks, highlighting their effectiveness in interpreting facial expressions and the evolution towards specialized architectures like DenseNet, ResNet, Channel Boosting, and SE-Net. Various studies and applications in this domain illustrate the advancements and challenges in leveraging CNNs for emotion detection tasks.

## Methods

Implemented methods:
- DenseNet
- ResNet
- Channel Boosting
- SE Net

## Results and Conclusion

From the evaluation of several sub-CNN architectures:
1. **ResNet**: Mitigates depth using residual blocks.
2. **SE-Net**: Enhances width through cross-channel learning.
3. **Channel Boosting**: Utilizes transfer learning for additional channels.

Width-wise learning, as demonstrated by SE-Net, proves essential for effective image classification. However, limitations such as varying model quality and dataset simplicity impact findings. Future research should explore more complex datasets and newer CNN architectures to validate these conclusions.

## Team Members:

1. Bhavesh Rajesh Talreja
2. Matthew Horowitz
3. Oladapo Oggunaike

## References

1. Dataset: [Facial Recognition Dataset (kaggle.com)](https://www.kaggle.com), Carrier, P-C. and Courville, A. (2020), "Facial Recognition Dataset", Kaggle.
2. Albraikan, A. et al. (2022), "Intelligent facial expression recognition and classification using optimal deep transfer learning model", Image and Vision Computing.
3. Akhand, M. et al. (2021), "Facial recognition using transfer learning in the deep CNN", Electronics.
4. Chauhan, T. et al. (2021), "Optimization and fine-tuning of DenseNet model for classification of COVID-19 cases in medical imaging", International Journal of Information Management Data Insights.
5. Dai, Z. and Heckel, R. (2019), "Channel Normalization in Convolutional Neural Networks avoids Vanishing Gradients".
6. Goodfellow, I. et al. (2016), Deep Learning, MIT Press.
7. Guo, P. and Song, C. (2022), "Facial Recognition with Squeeze-and-Excitation Network", 2022 7th International Conference on Intelligent Computing and Signal Processing.
8. He, K. et al. (2015), "Deep Residual Learning for Image Recognition", Microsoft Research.
9. Hu, J. et al. (2019), "Squeeze-and-Excitation Networks".
10. Huang, G. et al. (2018), "Densely Connected Convolution Networks".
11. Xu, W. and Cloutier, R. (2022), "A facial expression recognizer using modified ResNet-152", EAI Endorsed Transaction on Internet of Things.
12. PyTorch (n.d.), "densenet 161", Available at: [Torchvision main documentation](https://pytorch.org)
13. PyTorch (n.d.), "Models and Pre-Trained Weights", Available at: [Torchvision 0.16 documentation](https://pytorch.org)
14. PyTorch (n.d.), "ResNet", Available at: [ResNet | PyTorch](https://pytorch.org)
15. PyTorch (n.d.), "ResNet 18", Available at: [Torchvision main documentation](https://pytorch.org)
16. Raschka, S. et al. (2022), "Machine Learning with PyTorch and Sikit-Learn", Packt, Birmingham, UK.
