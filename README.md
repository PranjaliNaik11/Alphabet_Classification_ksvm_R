# Alphabet Classification using KSVM in R with VanillaDot and RBF Kernels

This R project demonstrates alphabet classification using the KSVM (Kernel Support Vector Machine) algorithm with two different kernels: VanillaDot and RBF (Radial Basis Function). The project aims to classify alphabets into their respective categories based on their features extracted from input data.

## Overview

The KSVM algorithm is a powerful tool for classification tasks, especially when dealing with non-linear data. In this project, we utilize two different kernels to classify alphabets:
- **VanillaDot Kernel**: This kernel computes the dot product between input feature vectors, suitable for linearly separable data.
- **RBF Kernel**: The Radial Basis Function kernel is effective for handling non-linear data by transforming input features into a higher-dimensional space.

## Features

- **Alphabet Classification**: Classifies input alphabets into their respective categories.
- **KSVM Algorithm**: Utilizes the Kernel Support Vector Machine algorithm for classification.
- **VanillaDot Kernel**: Implements classification using the VanillaDot kernel for linearly separable data.
- **RBF Kernel**: Implements classification using the RBF kernel for non-linear data.
- **Performance Evaluation**: Evaluates the classification performance using appropriate metrics.

## How to Use

### Prerequisites

- R programming language installed on your system.
- Basic understanding of R programming and machine learning concepts.

### Installation

1. Clone the project repository from [GitHub](https://github.com/PranjaliNaik11/Alphabet_Classification_ksvm_R).

   ```bash
   git clone https://github.com/PranjaliNaik11/Alphabet_Classification_ksvm_R.git
   ```

2. Navigate to the project directory.

   ```bash
   cd Alphabet_Classification_ksvm_R
   ```

### Usage

1. Load the dataset containing alphabet features into R.
2. Preprocess the dataset as necessary (e.g., normalization, splitting into training and testing sets).
3. Implement the KSVM algorithm using both VanillaDot and RBF kernels for classification.
4. Evaluate the classification performance using appropriate metrics.
5. Analyze the results and fine-tune the model if necessary for better performance.

## Contribution

Contributions are welcome! If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request. Make sure to follow the existing code style and guidelines.
