# Generative AI Lab: Neural Network from Scratch

## Objective
The primary objective of this project is to implement a simple feedforward neural network from scratch in Python without using any in-built deep learning libraries[cite: 1]. This implementation focuses on understanding core components such as the forward pass, backward propagation (backpropagation), and training the model using gradient descent[cite: 1].

---

## Dataset & Task
* **Dataset:** Iris Dataset (loaded via `sklearn.datasets`)
* **Task:** Multi-class Classification[cite: 1]
* **Description:** The dataset contains 150 samples of iris flowers, characterized by 4 numerical features (sepal length, sepal width, petal length, and petal width). The goal is to accurately classify each flower into one of three distinct species (Setosa, Versicolor, Virginica).

---

## Methodology

### 1. Neural Network Architecture
* **Input Layer:** 4 neurons (matching the 4 input features)[cite: 1].
* **Hidden Layer:** 1 hidden layer with 5 neurons using the **Sigmoid** activation function[cite: 1].
* **Output Layer:** 3 neurons (matching the 3 target classes) using the **Softmax** activation function[cite: 1].

### 2. Forward Pass
Data moves through the network by computing the weighted sums ($Z = XW + b$) and applying the respective activation functions layer by layer[cite: 1].

### 3. Backpropagation
The error is calculated at the output layer and propagated backward to adjust the weights[cite: 1]. This is done by computing the derivatives of the loss function and activation functions using the chain rule[cite: 1].

### 4. Loss Function & Optimization
* **Loss Function:** Categorical Cross-Entropy[cite: 1].
* **Optimization:** Standard Gradient Descent is used to iteratively update the weights and minimize the loss[cite: 1].

---

## Repository Structure
* `Rushikesh_Hande_GenerativeAILabAssignment.ipynb`: The main Jupyter Notebook containing the end-to-end implementation, mathematical functions, training loop, and visualizations[cite: 1].
* `README.md`: Project documentation[cite: 1].

---

## Execution and Testing
To run this project:
1. Clone this repository to your local machine.
2. Ensure you have Python installed along with the required libraries: `numpy`, `matplotlib`, and `scikit-learn`.
3. Open the Jupyter Notebook file.
4. Execute all cells sequentially from top to bottom in a clean environment[cite: 1]. 
5. The notebook will run end-to-end without errors, outputting the training progress, final accuracies, and a loss curve visualization[cite: 1].

---

## Declaration
I, Rushikesh Hande, confirm that the work submitted in this assignment is my own and has been completed following academic integrity guidelines[cite: 1].
