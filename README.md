# InceptionV2 in Java (MNIST)

This project implements the InceptionV2 deep learning architecture for image classification from scratch in Java, specifically targeting the well-known MNIST handwritten digit dataset. Here's a breakdown of the key aspects:

**Key Features:**

- **Pure Java Implementation:** This project avoids using external deep learning libraries, showcasing a custom Java implementation of InceptionV2.
- **MNIST Dataset:** The model is trained and evaluated on the MNIST dataset, a standard benchmark for handwritten digit classification.
- **86% Accuracy:** The achieved accuracy of 86% demonstrates a successful implementation of InceptionV2.

**Regularization Techniques (Scope):**

This README highlights the project's potential for exploration with regularization techniques, which can further improve performance and prevent overfitting. Some possible methods include:

- **Dropout:** Randomly dropping out neurons during training to encourage weight distribution and prevent overreliance on specific features.
- **L1/L2 Regularization:** Penalizing the cost function based on the L1 or L2 norm of the model weights, promoting sparsity and reducing complexity.
- **Data Augmentation:** Artificially increasing the size and diversity of the training dataset through techniques like random cropping, rotation, and flipping.

**Project Structure (Potential):**

While the specific structure might vary, here's a possible organization for your project:

```
inceptionv2-mnist/
├── build/
│   ├── UTIL/
│   │   └── mat.class
│   ├── classes/
│   │   ├── testing/
|   │   │   ├── 0/
|   │   │   ├── 1/
|   │   │   ├── 2/
|   │   │   ├── 3/
|   │   │   ├── 4/
|   │   │   ├── 5/
|   │   │   ├── 6/
|   │   │   ├── 7/
|   │   │   ├── 8/
|   │   │   └── 9/
│   │   ├── training/
|   │   │   ├── 0/
|   │   │   ├── 1/
|   │   │   ├── 2/
|   │   │   ├── 3/
|   │   │   ├── 4/
|   │   │   ├── 5/
|   │   │   ├── 6/
|   │   │   ├── 7/
|   │   │   ├── 8/
|   │   │   └── 9/
│   ├── lib/
│   │   ├── CopyLibs/
|   │   │   ├── org-netbeans-modules-java-j2seproject-copylibstask.jar
│   │   └── nblibraries.properties
├── out/
|   ├── production/
|   │   ├── CNN-MASTER/
|   │   │   ├── UTIL/
|   |   │   │   ├── Mat.class
|   |   │   │   └── output
|   │   │   ├── cnn/
|   |   │   │   ├── CNN.class
|   |   │   │   ├── Convolution1x1.class
|   |   │   │   ├── Convolution3x3.class
|   |   │   │   ├── Convolution5x5.class
|   |   │   │   ├── MaxPool.class
|   |   │   │   └── SoftMax.class
├── src/
│   │   ├── UTIL/
|   │   │   ├── Mat.java
│   │   ├── cnn/
|   │   │   ├── CNN.java
|   │   │   ├── Convolution1x1.java
|   │   │   ├── Convolution3x3.java
|   │   │   ├── Convolution5x5.java
|   │   │   ├── MaxPool.java
|   │   │   └── SoftMax.java
├── CNN-master.iml
├── README.md  (This file)
├── build.xml  
└── manifest.mf  
```

**Building and Running (Potential):**

The instructions for building and running the project might depend on your specific setup. However, here's a general outline:

1. **Prerequisites:**
   - Java Development Kit (JDK)
   - Build tool (e.g., Maven, Gradle - if applicable)

2. **Build (if using a build tool):**
   - Follow the build instructions in your project's build script (e.g., `mvn clean install` or `gradle build`).

3. **Run:**
   - Open a terminal or command prompt and navigate to the project directory.\
   - Type (`cd src\cnn`)
   - Run the main program using Java (e.g., `java cnn.java`).

**Further Considerations:**

- **Documentation:** Consider adding detailed comments to your code to enhance understanding and maintainability.
- **Modular Design:** Strive for a modular design to allow for easier development, maintenance, and potential extension for other datasets.
- **Regularization Exploration:** Implement the scoped regularization techniques (e.g., Dropout, L1/L2) and compare their impact on accuracy and model complexity.

**Disclaimer:**
