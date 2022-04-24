# CSE541-Computer-Vision-2022-FantasticFour

## Real Time Face Recognition

### Project Introduction
Face recognition is a method of recognizing an individual using their face. Face recognition systems can be used to identify individuals in photos, videos, or in real-time. The main motivation behind building a real-time face recognition system is to enable faster processing and seamless integration in various real-world applications such as public safety systems, authentication systems, retail-store systems, etc. 

During the initial days, the speed of recognition of human faces in machines was slow and the accuracy seemed to be lower than manual recognition. However, with the development of deep learning and the increased application of Convolution Neural Network (CNN), the accuracy and speed of human-face recognition by machines are greatly improved.

We have tried to build a real-time face recognition system using the MobileNet and SqueezeNet models which are capable of detecting and recognizing images from cameras (mobile or laptop) accurately. In real-time, based on these models, we have developed and compared the face recognition systems in order to make an accurate facial recognition system. 

### Results
#### MobilenetV2 Statistics
<img src="https://github.com/Jimmy290901/CSE541-Computer-Vision-2022-FantasticFour/blob/main/Results/MobilenetV2%20Accuracy.png">
<img src="https://github.com/Jimmy290901/CSE541-Computer-Vision-2022-FantasticFour/blob/main/Results/MobilenetV2%20Loss.png">

#### SqueezeNet Statistics
<img src="https://github.com/Jimmy290901/CSE541-Computer-Vision-2022-FantasticFour/blob/main/Results/Squeezenet%20Accuracy.png">
<img src="https://github.com/Jimmy290901/CSE541-Computer-Vision-2022-FantasticFour/blob/main/Results/Squeezenet%20Loss.png">

#### Real Time Face Recognition using MobilenetV2
<img src="https://github.com/Jimmy290901/CSE541-Computer-Vision-2022-FantasticFour/blob/main/Results/MobilenetV2%20Recognition.png">

#### Real Time Face Recognition using Squeezenet
<img src="https://github.com/Jimmy290901/CSE541-Computer-Vision-2022-FantasticFour/blob/main/Results/Squeezenet%20Recognition.png">

### References
1. Simon Low, “SqueezeNet and MobileNet: Deep learning models for mobile phones, 03-May-2018, AI in Practice. Available: https://aiinpractice.com/squeezenet-mobilenet/#:~:text=Furthermore%2C%20MobileNet%20achieves%20really%20good,using%20transfer%20learning%20or%20distillation
2. A. Michele, V. Colin, and D. D. Santika, “MobileNet convolutional neural networks and support vector machines for Palmprint recognition,” Procedia Computer Science, 01-Oct-2019. [Online]. Available: https://www.sciencedirect.com/science/article/pii/S1877050919310658. [Accessed: 24-Apr-2022].
3. S.-H. Tsang, “Review: MOBILENETV2 - light weight model (image classification),” Medium, 01-Aug-2019. [Online]. Available: https://towardsdatascience.com/review-mobilenetv2-light-weight-model-image-classification-8febb490e61c#:~:text=MobileNetV2%20Overall%20Architecture&text=In%20typical%2C%20the%20primary%20network,and%20uses%203.4%20million%20parameters. [Accessed: 24-Apr-2022]. 
4. F. N. Iandola, S. Han, M. W. Moskewicz, K. Ashraf, W. J. Dally, and K. Keutzer, “Squeezenet: Alexnet-level accuracy with 50X ... - arxiv.org,” SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and &lt;0.5MB model size, 2017. [Online]. Available: https://arxiv.org/pdf/1602.07360v3.pdf. [Accessed: 24-Apr-2022].
5. S.-H. Tsang, “Review: SqueezeNet (image classification),” Medium, 22-Apr-2019. [Online]. Available: https://towardsdatascience.com/review-squeezenet-image-classification-e7414825581a. [Accessed: 24-Apr-2022].
