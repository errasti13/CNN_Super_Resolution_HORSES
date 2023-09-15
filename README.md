# Super Resolution CNN

## Introduction

 This repository contains an implementation of the Super-Resolution Convolutional Neural Network (SRCNN) method for generating high-order solutions from low-order simulations.

## Table of Contents

 - Introduction
 - Getting Started
 - Usage
 - Results
 - License

## Getting Started

### Prerequisites

Before running the code, make sure you have the following prerequisites installed:

- Python 3.x
- TensorFlow
- Keras
- SciPy
- Matplotlib

You can install these dependencies using pip:

```bash
 pip install tensorflow keras scipy matplotlib
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/srcnn-high-order-solutions.git
```

2. Change to the project directory:

```bash
 cd srcnn-high-order-solutions
```

3. Set up the necessary configurations in the `NEURALNET/config_nn.dat` file.

## Usage
To use the SRCNN method to generate high-order solutions:

1. Run the `main.py` script:

```bash
python main.py
```

This script will perform the following steps:
- Solve the high-order (HO) and low-order (LO) solutions if not already solved.
- Load or create training data for the SRCNN model.
- Create and train the SRCNN model.
- Generate high-order solutions using the trained model.
- Save the results in the `RESULTS` directory.

### Results

The generated high-order solutions and associated error information can be found in the `RESULTS` directory. You can visualize the results using the provided scripts or analyze them as needed for your specific application.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

