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

## Team Members

1. Bhavesh Rajesh Talreja
2. Matthew Horowitz
3. Oladapo Oggunaike

## References

### Data Set:
- Carrier, P-C and Courville, A (2020), “Facial Recognition Dataset”, Kaggle, Available at: [Facial Recognition Dataset](https://www.kaggle.com/)

### Pre-Trained Models:
- Albraikan, A; Alzahrani, J; Alshahrani, R; Yafoz, A; Alsini, R; Hilal, A; Alkhayyat, A; Gupta, D (2022), “Intelligent facial expression recognition and classification using optimal deep transfer learning model”, Image and Vision Computing, Available at: [ScienceDirect](https://www.sciencedirect.com/)
- Akhand, M; Roy, S; Siddique, N; Kamal, M; Shimamura, T (2021), “Facial recognition using transfer learning in the deep CNN”, Electronics, 2021, 10, Available at: [mdpi.com](https://www.mdpi.com/)
- PyTorch (n.d.) “densenet 161”, Available at: [PyTorch Documentation](https://pytorch.org/)
- PyTorch (n.d.), “Models and Pre-Trained Weights”, Available at: [Torchvision 0.16 Documentation](https://pytorch.org/)
- PyTorch (n.d.) “ResNet”, Available at: [PyTorch Documentation](https://pytorch.org/)
- PyTorch (n.d.), “ResNet 18”, Available at: [Torchvision Documentation](https://pytorch.org/)
- Xu, W; Cloutier, R (2022), “A facial expression recognizer using modified ResNet-152”, EAI Endorsed Transaction on Internet of Things, Available at: [eudl.eu](https://eudl.eu/)

### Programming Resource:
- Raschka, S; Liu Y; Mirjalili, V (2022), Machine Learning with PyTorch and Sikit-Learn, Packt, Birmingham: UK.

### Literature Review:
- Chauhan, T; Palivela, H; Tiwari, S (2021), “Optimization and fine-tuning of DenseNet model for classification of COVID-19 cases in medical imaging”, International Journal of Information Management Data Insights, 1, Available at: [ScienceDirect](https://www.sciencedirect.com/)
- Chen, J; Chen, T; Xiao, B; Bi, X; Wang, Y; Duan, H; Li, W; Zhang, J; Ma, D (2020), “SE-ECGNet: Multi-scale SE-Net for Multi-lead ECG Data”, Computing In Cardiology, 47, Available via IEEE Explore.
- Dai, Z; Heckel, R (2019), “Channel Normalization in Convolutional Neural Networks avoids Vanishing Gradients”, Available at: [arxiv.org](https://arxiv.org/)
- Goodfellow, I; Bengio, Y; Courville A (2016), Deep Learning, Cambridge, MA: MIT Press.
- Guo, P; Song, C (2022), “Facial Recognition with Squeeze-and-Excitation Network”, 2022 7th International Conference on Intelligent Computing and Signal Processing, Available via: IEEE Explore.
- He, K; Zhang, X; Ren, S; Sun, J (2015), “Deep Residual Learning for Image Recognition”, Microsoft Research, Available at: [arxiv.org](https://arxiv.org/)
- Hu, J; Shen, L; Albanie, S; Sun, G; Wu, E (2019), “Squeeze-and-Excitation Networks”, Available at: [arxiv.org](https://arxiv.org/)
- Huang, G; Liu, Z; van der Maaten, L; Weinberger K (2018), “Densely Connected Convolution Networks”, Available at: [arxiv.org](https://arxiv.org/)
- Jalal, AS; Sharma, DK; Sikander, B (2021), “Facial Mole Detection Approach for Suspect Face Identification using ResNeXt-50”, 2021 12th International Conference on Computing Communication and Networking Technologies (ICCCNT). Available via IEEE.
- Ju, Cheng; Bibaut, A; van der Laan, M.J (2017), “The Relative Performance of Ensemble Methods with Deep Convolutional Neural Networks for Image Classification”, Available at: [arxiv.org](https://arxiv.org/)
- Khan, A; Sohail, A; Ali, A (2018), “A New Channel Boosted Convolutional Neural Network using Transfer Learning”, Available at: [arxiv.org](https://arxiv.org/)
- Khan, A; Sohail, A.; Zahoora, U; Quershi, A.S. (2019), “A Survey of the Recent Architectures of Deep Convolutional Neural Networks”, Artificial Intelligence Review, 53, pp. 5455-5516, Available at: [arxiv.org](https://arxiv.org/)
- Kramberger, T; Cesar, I; KovaCeviC, R (2020), “Automobile Classification Using Transfer Learning on ResNet Neural Network Architecture”, Polytechnic and Design, 8(1), Available at: [researchgate.net](https://researchgate.net/)
- le Cun, Y (1989), “Generalization and Network Design Strategies”, Department of Computer Science: University of Toronto.
- Li, B; Lima, D (2021), “Facial Recognition via ResNet-50”, International Journal of Cognitive Computing In Engineering, Vol 2, Accessed via: Science Direct.
- Nguyen, L; Lin, D; Lin, Z; Cao, J (2018), “Deep CNNs for microscopic image classification by exploiting transfer learning and feature concatenation”, Available at: [researchgate.net](https://researchgate.net/)
- Podder, T; Bhattacharya, D; Majumder, P; Balas, V.E. (2023), “A feature boosted deep learning method for automatic facial expression recognition”, PeerJ Computer Science.
- Rahman, M; Prodhan, R; Shishir, Y; Ripon, S (2021), “Analyzing and Evaluation Boosting-Based CNN Algorithms for Image Classification”, 2021 International Conference on Intelligent Technologies (CONIT), Available at: [IEEE Xplore](https://ieeexplore.ieee.org/)
