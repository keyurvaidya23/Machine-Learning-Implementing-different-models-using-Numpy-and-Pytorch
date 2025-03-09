Machine Learning Models: Linear Regression & Neural Networks
Overview
This repository contains implementations of Linear Regression and Neural Networks using NumPy and PyTorch. These models are implemented from scratch to help understand how they work at a fundamental level.

Implemented Models:
Linear Regression (NumPy & PyTorch)
Neural Networks (NumPy & PyTorch)

 Installation
1️⃣ Clone the Repository

git clone https://github.com/keyurvaidya23/Machine-Learning-Implementing-different-models-using-Numpy-and-Pytorch.git

cd Machine-Learning-Implementing-different-models-using-Numpy-and-Pytorch

2️⃣ Create a Virtual Environment (Recommended)

python -m venv venv
source venv/bin/activate  # MacOS/Linux
venv\Scripts\activate     # Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

All required dependencies are listed in requirements.txt.

Implemented Models

Linear Regression

Objective: Implement Linear Regression using NumPy and PyTorch to predict values based on given inputs.

Implementation:

NumPy: Implements gradient descent from scratch.

PyTorch: Uses torch.nn.Linear() to define the model.

Full implementation available in Linear_Regression.ipynb

Neural Networks

Objective: Implement Artificial Neural Networks (ANNs) using NumPy and PyTorch.

Implementation:

NumPy: Implements a simple fully connected neural network from scratch using forward and backward propagation.

PyTorch: Uses torch.nn.Linear(), torch.nn.ReLU(), and torch.optim.Adam() for optimization.

Full implementation available in Neural_Network_NumPy.ipynb

How to Run

Run Linear Regression Notebook

jupyter notebook Linear_Regression.ipynb

Run NumPy-based Neural Network

jupyter notebook Neural_Network_NumPy.ipynb

Run PyTorch-based Neural Network

jupyter notebook Neural_Network_PyTorch.ipynb

Contributing

Contributions are welcome! If you'd like to improve this project:

Fork the repository.

Create a new branch (feature-improvement).

Commit your changes (git commit -m "Add feature").

Push to your branch (git push origin feature-improvement).

Create a Pull Request.



