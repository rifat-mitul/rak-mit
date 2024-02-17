# Introduction to Convolutional Neural Networks (CNNs)


## What are Convolutional Neural Networks?

Convolutional Neural Networks, or CNNs, are a class of deep learning models primarily used for processing and analyzing visual data, such as images and videos. They are inspired by the human visual system and have revolutionized various computer vision tasks.

## Why CNNs?

CNNs have become the de facto standard for image recognition, object detection, image segmentation, and many other computer vision tasks due to their ability to automatically learn hierarchical representations directly from raw pixel data.

## Key Components of CNNs:

### 1. Convolutional Layers:

- Convolutional layers apply convolution operations to input images, extracting features such as edges, textures, and patterns.
- These layers consist of learnable filters (kernels) that slide over the input image to perform convolution operations.
- The output of convolutional layers is passed through activation functions (e.g., ReLU) to introduce non-linearity.

### 2. Pooling Layers:

- Pooling layers downsample feature maps, reducing their spatial dimensions while retaining important information.
- Common pooling operations include max pooling and average pooling, which extract the maximum or average value from a local neighborhood, respectively.

### 3. Fully Connected Layers:

- Fully connected layers are traditional neural network layers that connect every neuron from the previous layer to every neuron in the subsequent layer.
- They integrate high-level features learned by convolutional layers and make final predictions based on these features.

## CNN Architectures:

### 1. LeNet-5:

- LeNet-5, proposed by Yann LeCun in 1998, is one of the earliest CNN architectures.
- It consists of convolutional layers, pooling layers, and fully connected layers and was primarily used for handwritten digit recognition.

### 2. AlexNet:

- AlexNet, developed by Alex Krizhevsky et al. in 2012, is a pioneering CNN architecture that significantly advanced the field of computer vision.
- It won the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) in 2012 by achieving state-of-the-art performance in image classification.

### 3. VGGNet:

- VGGNet, proposed by the Visual Geometry Group at the University of Oxford in 2014, is known for its simplicity and uniform architecture.
- It consists of multiple convolutional layers with small 3x3 filters followed by max-pooling layers.

### 4. ResNet:

- ResNet (Residual Neural Network), introduced by Kaiming He et al. in 2015, addressed the vanishing gradient problem in deep neural networks.
- It introduced skip connections that allow gradients to flow more efficiently during training, enabling the training of very deep networks (e.g., hundreds of layers).

## Applications of CNNs:

- **Image Classification**: CNNs can classify images into predefined categories, such as identifying objects in photographs.
- **Object Detection**: CNNs can detect and localize objects within images, enabling applications like autonomous driving and surveillance.
- **Image Segmentation**: CNNs can segment images into semantically meaningful regions, useful for medical imaging and scene understanding.
- **Face Recognition**: CNNs can recognize and verify human faces, enabling biometric authentication and surveillance systems.
- **Artistic Style Transfer**: CNNs can transfer artistic styles from one image to another, creating visually appealing artworks.

>> *To be added more as learning progresses*


