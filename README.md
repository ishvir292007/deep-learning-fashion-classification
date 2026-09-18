
# Deep Learning Fashion Image Classification

A practical deep learning project that uses TensorFlow and Keras to classify fashion product images into 10 categories using the Fashion MNIST dataset. This project demonstrates neural network architecture, model training, evaluation, and the application of image classification in e-commerce.

## Project Overview

E-commerce platforms process thousands of product images, making automated product categorization valuable for catalog management and operational efficiency.

This project develops a simple Artificial Neural Network (ANN) that learns from labeled fashion images and predicts the corresponding product category.

### Business Use Case

**Industry:** E-commerce & Retail Technology

**Problem:** Manual classification of fashion product images can require significant time and operational effort.

**Proposed Solution:** Use a deep learning-based image classification model to automate product category prediction.

**Input:** Fashion product image

**Output:** Predicted product category

## Objectives

- Understand image classification using deep learning.
- Build an Artificial Neural Network using TensorFlow/Keras.
- Explore input, hidden, and output layers.
- Train a model using the Fashion MNIST dataset.
- Evaluate classification performance.
- Predict fashion product categories.
- Connect machine learning concepts with e-commerce applications.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| TensorFlow | Deep learning framework |
| Keras | Neural network development |
| NumPy | Numerical operations |
| Matplotlib | Image visualization |
| Google Colab | Development environment |

## Dataset

This project uses the **Fashion MNIST** dataset, containing grayscale images of fashion products.

| Dataset Split | Images |
|---|---:|
| Training | 60,000 |
| Testing | 10,000 |
| Image Resolution | 28 × 28 pixels |
| Number of Classes | 10 |

### Fashion Categories

1. T-shirt/Top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

## Model Architecture

The project implements a basic feedforward neural network using TensorFlow/Keras.

```text
Input Image (28 × 28)
        │
        ▼
Flatten Layer
        │
        ▼
Dense Layer (64 Neurons)
Activation: ReLU
        │
        ▼
Output Layer (10 Neurons)
Activation: Softmax
        │
        ▼
Predicted Fashion Category
```

### Architecture Components

- **Flatten:** Converts the 28 × 28 image into a 784-element vector.
- **Dense (64):** Learns patterns from the input features.
- **ReLU:** Activation function used in the hidden layer.
- **Softmax:** Produces probability values across the 10 output classes.

## Workflow

1. Import required libraries.
2. Load the Fashion MNIST dataset.
3. Define product categories.
4. Visualize fashion images.
5. Normalize image pixel values.
6. Build the neural network.
7. Compile the model.
8. Train the model.
9. Evaluate test performance.
10. Generate product category predictions.

## Model Training

The model is compiled using:

- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Crossentropy
- **Evaluation Metric:** Accuracy
- **Training Duration:** 3 epochs

## Results

The notebook records the following evaluation result:

| Metric | Result |
|---|---:|
| Test Accuracy | 85.67% |
| Training Epochs | 3 |
| Output Categories | 10 |

> Note: The reported accuracy is specific to the recorded notebook execution and should not be interpreted as a guaranteed result for future runs.

## Business Applications

This project demonstrates potential applications in:

- Automated fashion product categorization.
- E-commerce catalog organization.
- Product image tagging.
- Retail inventory workflows.
- Machine learning education and experimentation.

The current model is a practical educational prototype and is not a production-ready retail classification system.

## Project Structure

```text
deep-learning-fashion-classification/
│
├── Deep_Learning_Fashion_Image_Classification_BBA.ipynb
├── README.md
└── requirements.txt (optional)
```

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/deep-learning-fashion-classification.git
```

### 2. Open the Notebook

Launch the notebook using Google Colab or Jupyter Notebook.

### 3. Install Dependencies

```bash
pip install tensorflow numpy matplotlib
```

### 4. Execute the Notebook

Run the cells sequentially to:

- Download the dataset.
- Prepare the images.
- Train the neural network.
- Evaluate model accuracy.
- Generate predictions.

## Learning Outcomes

Through this project, learners gain practical exposure to:

- Image-based machine learning.
- Artificial Neural Networks.
- Classification workflows.
- Model evaluation.
- Business applications of AI in retail.

## Future Enhancements

- Implement Convolutional Neural Networks (CNNs).
- Add confusion matrix and classification reports.
- Introduce data augmentation.
- Build a web-based image prediction interface.
- Improve model generalization.
- Deploy the trained model through an API.

## Author

**Ishvir Singh Matharoo**

BBA FinTech & AI

Chitkara University

## License

This project is intended for educational and portfolio purposes.
