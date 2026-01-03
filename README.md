# Machine Learning Playground

Welcome to the Machine Learning Playground! This repository serves as a personal space for experimenting with machine learning and artificial intelligence, as well as documenting the setup and configurations used.

## Check Your Python Version

Before diving into machine learning, ensure that Python is installed on your machine. Python is essential for running the notebooks.

**Note:**  
Some projects may require Python 3.10, while others may need the latest version. It is recommended to install Python 3.10 for compatibility with various dependencies, especially if you plan to use PyTorch.

To check your Python version, run one of the following commands in your terminal:

```bash
python --version
```
or
```bash
python -V
```
or
```bash
py --version
```
or
```bash
py -V
```

## Setup

Here’s a basic setup guide for your machine learning journey!

### Create a Virtual Environment

Creating a virtual environment is a good practice for managing dependencies. To create a `.venv` file, run:

```bash
python -m venv .venv
```

If you specifically want to use Python 3.10, you can create the virtual environment with:

```bash
python -3.10 -m venv .venv
```

### Activate the Virtual Environment

To activate the virtual environment, run:

```bash
.venv/Scripts/activate
```

If you encounter any issues, you may need to adjust your execution policy by running:

```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

After adjusting, activate the virtual environment again.

#### Expected Output

Upon successful activation, your terminal should display something like this:

```bash
(.venv) PS C:\Users\Document> 
```

### Install Dependencies

Once the virtual environment is activated, you can install the necessary dependencies. Use one of the following commands:

To install specific dependencies:

```bash
pip install <dependencies>
```

Or, if you have a `requirements.txt` file, install all dependencies listed in it:

```bash
pip install -r requirements.txt
```

### Create a requirements.txt File

If you want to save your installed dependencies for future use, you can create a `requirements.txt` file by running:

```bash
pip freeze > requirements.txt
```

## Local Machine Setup (RTX/GTX)

To leverage GPU capabilities, download and install the following:

- **CUDA 11.2**
- **cuDNN 8.1**

You're all set to start your machine learning journey! Enjoy experimenting and learning!