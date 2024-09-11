## **PyTorch GoogLeNet Implementation**

### **Introduction**
This repository provides a PyTorch implementation of the GoogLeNet (Inception-v1) architecture from scratch. The goal is to offer a clear and detailed understanding of the network's structure, components, and how it works.

### **Key Features**
* **Pure PyTorch:** The implementation relies solely on PyTorch's core functionalities, avoiding external libraries or pre-trained models.
* **Modularity:** The code is organized into well-defined modules, making it easy to understand and modify.
* **Detailed Documentation:** Comments and explanations are provided throughout the code to clarify the purpose of different parts.
* **Customizability:** The implementation can be easily adapted to different use cases by modifying hyperparameters or adding custom layers.

### **Usage**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Dikashmashree/Pytorch_GoogLeNet-InceptionNet_from_scratch.git
   ```
2. **Install Dependencies:**
   Ensure you have PyTorch and its dependencies installed. You can install them using pip:
   ```bash
   pip install torch torchvision
   ```
3. **Run the Code:**
   
   You may need to adjust the hyperparameters in the script to suit your specific dataset and requirements.

### **Architecture Overview**
The GoogLeNet architecture is based on the Inception module, which consists of multiple convolutional layers with different kernel sizes. These layers are concatenated along the depth dimension, allowing the network to learn features at different scales. The overall architecture is composed of several Inception modules stacked together, along with pooling layers to reduce the spatial dimensions.

### **Customization**
You can customize the implementation by:
* **Modifying Hyperparameters:** Experiment with different learning rates, batch sizes, and other hyperparameters to optimize performance.
* **Adding Custom Layers:** Incorporate additional layers (e.g., dropout, batch normalization) to improve regularization or performance.
* **Changing the Dataset:** Adapt the code to work with different datasets by modifying the data loading and preprocessing steps.

### **Contributing**
Contributions are welcome! Feel free to submit pull requests or open issues if you have any suggestions, bug reports, or feature requests.

### **Reference**
## **Research Paper: Going Deeper with Convolutions**

**Authors:** Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan, Vincent Vanhoucke, Andrew Rabinovich

**Publication:** Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2015

**Abstract:**

This paper introduces a deep convolutional neural network architecture codenamed "Inception," which achieved state-of-the-art performance in the ImageNet Large-Scale Visual Recognition Challenge 2014. The Inception module, a key component of the architecture, consists of multiple convolutional layers with different kernel sizes. This allows the network to extract features at different scales, improving its efficiency and accuracy. The GoogLeNet, an incarnation of the Inception architecture, is a 22-layer deep network that demonstrates superior performance in both classification and detection tasks.

**Key Contributions:**

* **Inception Module:** The Inception module's ability to process features at multiple scales is a novel approach that enhances the network's capacity to learn complex patterns.
* **Efficient Architecture:** The GoogLeNet architecture is designed to be computationally efficient, making it suitable for deployment on resource-constrained devices.
* **State-of-the-Art Performance:** The GoogLeNet achieved top-tier results in the ImageNet classification and detection challenges, demonstrating the effectiveness of the Inception module.

**You can find the paper here:** [http://ieeexplore.ieee.org/document/7298594](http://ieeexplore.ieee.org/document/7298594)

**Note:** This paper is a seminal work in the field of deep learning, providing a significant contribution to the development of convolutional neural networks. It has been widely cited and has influenced subsequent research in computer vision and related areas.

