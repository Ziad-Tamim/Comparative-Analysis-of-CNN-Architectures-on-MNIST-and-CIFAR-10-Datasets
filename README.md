# Comparative Analysis of CNN Architectures on MNIST and CIFAR-10 Datasets
This project evaluates prominent Convolutional Neural Network (CNN) architectures: LeNet, AlexNet, Googlenet, and ResNet, each representing major advancements in deep learning for visual information processing. Our study focuses on two primary datasets:

* **MNIST**: Used for benchmarking basic model efficacy with its simple images of handwritten digits.
* **CIFAR-10**: Provides a more challenging environment with colored and varied natural images to test robustness and generalization capabilities.

Key Architectural Insights:

* **LeNet**: Pioneered the use of convolutional layers for tasks such as handwriting recognition.
* **AlexNet**: Introduced deeper layers and the ReLU activation function, significantly reducing training times and improving performance.
* **Googlenet**: Optimized design through the inception module to maintain high performance with fewer parameters.
* **ResNet**: Utilized residual learning to enable training of very deep networks without the vanishing gradient problem, achieving new standards in performance efficiency.

In addition to evaluating these models, this project explored the impact of various regularization techniques (like L2 regularization, early stopping, learning rate scheduling, and data augmentation) on ResNet. These techniques increased the validation accuracy by 10%, achieving an impressive 89.6% on the CIFAR-10 test set, thereby underlining the practical applications and performance adaptability of CNNs in real-world scenarios.

# Resuts
| Dataset    | Model     | Accuracy t1 | Accuracy t2 |
|------------|-----------|-------------|-------------|
| **MNIST**  | LeNet     | 0.9852      | 0.9849      |
|            | Alexnet   | 0.9913      | 0.9919      |
|            | Googlenet | 0.9938      | 0.9934      |
|            | Resnet    | 0.9924      | 0.9889      |
| **CIFAR**  | LeNet     | 0.5237      | 0.5166      |
|            | Alexnet   | 0.7516      | 0.7523      |
|            | Googlenet | 0.7518      | 0.7343      |
|            | Resnet    | 0.7764      | 0.7998      |
| **CIFAR (regularisation)** | ResNet | 0.8909 | 0.896 |


  
