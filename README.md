In this case study, we will assume that you work as an AI/ML consultant and you have been hired by a medical diagnosis company in NYC.
• You have been tasked to improve the speed and accuracy of detecting and localizing brain tumors based on MRI scans.
• This would drastically reduce the cost of cancer diagnosis & help in early diagnosis of tumors which would essentially be a
life saver.
• The team has collected brain MRI scans and have approached you to develop a model that could detect and localize tumors.
• You have been provided with 3929 Brain MRI scans along with
their brain tumour location.

![image](https://user-images.githubusercontent.com/38830335/205977854-f6ec9892-f0b5-42a7-9e92-93aa0a229cc6.png)

RESNET (RESIDUAL NETWORK) (REVIEW) :
• As CNNs grow deeper, vanishing gradient tend to occur which negatively impact network performance.
• Vanishing gradient problem occurs when the gradient is back propagated to earlier layers which results in a very small
gradient.
• Residual Neural Network includes “skip connection” feature which enables training of 152 layers without vanishing gradient
issues.
• Resnet works by adding “identity mappings” on top of the CNN.
• ImageNet contains 11 million images and 11,000 categories.
• ImageNet is used to train ResNet deep network.

TRANSFER LEARNING:
• Transfer learning is a machine learning technique in which a network that has been trained to perform a specific task is being reused (repurposed) as a starting point for another similar task.
• Transfer learning is widely used since starting from a pre trained models can dramatically reduce the computational time required if training is performed from scratch. 

![image](https://user-images.githubusercontent.com/38830335/205978204-fd21bd6e-eee9-4286-ae15-7f95d523fd81.png)

WHAT IS IMAGE SEGMENTATION?
• The goal of image segmentation is to understand and extract information from images at the pixel
-level.
• Image Segmentation can be used for object recognition and localization which offers tremendous value in many applications
such as medical imaging and self -driving cars etc.
• The goal of image segmentation is to train a neural network to produce pixel
-wise mask of the image.
• Modern image segmentation techniques are based on deep learning approach which makes use of common architectures such as CNN, FCNs (Fully Convolution Networks) and Deep Encoders-Decoders.
• We going use ResUNet architecture to solve the current task.

![image](https://user-images.githubusercontent.com/38830335/205978568-e09c4c70-ec7a-4583-a9ca-052edc34ba65.png)
