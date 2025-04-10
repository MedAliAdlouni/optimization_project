# **Optimization Project: Gradient and Stochastic Gradient Methods for LASSO**

## **Project Overview**

This project implements the **gradient descent** and **stochastic gradient descent (SGD)** optimization methods for the **LASSO (Least Absolute Shrinkage and Selection Operator)** problem. The goal is to numerically study the effect of different hyperparameters (such as the step size and mini-batch size) on the convergence of these optimization algorithms.

### **Key Features:**
- **Gradient Descent Method**: A standard optimization algorithm used for minimizing the objective function in LASSO.
- **Stochastic Gradient Descent (SGD)**: A variant of gradient descent that updates the model parameters using only a subset (mini-batch) of the training data at each iteration.
- **Step Size Effect**: Analyzing how varying the learning rate (step size) impacts convergence speed and stability.
- **Mini-Batch Size Effect**: Investigating how the choice of mini-batch size influences the convergence behavior of SGD.


# How to Set Up the Project

Follow these steps to set up and run the project locally after you have cloned the repository.

---

## 1. Clone the Repository

Start by cloning the repository to your local machine. Run the following command in your terminal or Git Bash:

```bash
git clone https://github.com/MedAliAdlouni/optimization_project

```
After cloning, navigate into the project folder:

```bash
cd optimization_project
```

## 2. Set Up a Virtual Environment

It is highly recommended to use a virtual environment to manage the dependencies for this project.

Using `pip`:
### 1. Install virtualenv (if you don't have it already):

```bash
pip install virtualenv
```
### 2. Create a new virtual environment:

```bash
python -m venv venv
```

### 3. Activate the virtual environment:
On Windows:

```bash
venv\Scripts\activate
```

On macOS/Linux:

```bash
source venv/bin/activate
```

## 3. Install the Dependencies

Once the virtual environment is activated, you need to install the necessary Python dependencies. You can do this by using the requirements.txt file included in the project.

Run the following command to install the dependencies via pip:

```bash
pip install -r requirements.txt
```

## 4. Run the Project

After the setup is complete, you can start running your the Jupyter notebook.

If you're working with a Jupyter notebook, you can open it using:

```bash
jupyter notebook
```

This will open the notebook in your default browser, and you can start working with the code.

