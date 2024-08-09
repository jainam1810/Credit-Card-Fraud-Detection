# Credit-Card-Fraud-Detection Using Autoencoder and Restricted Boltzmann Machine (RBM)

## Overview

Credit card fraud is a persistent and evolving threat in the financial sector, necessitating the development of sophisticated detection techniques. This project explores the use of deep learning models—Autoencoder and Restricted Boltzmann Machine (RBM)—to enhance the detection of fraudulent credit card transactions.

Autoencoders are employed for their ability to learn efficient representations of data, enabling the detection of anomalies that may indicate fraud. RBMs, known for their powerful unsupervised learning capabilities, are utilized to model complex relationships within transaction data, further aiding in the identification of suspicious activities.

## Features

- **Autoencoder Implementation**: Utilize Autoencoders to reconstruct input data, capturing underlying patterns and detecting anomalies indicative of fraudulent transactions.
  
- **RBM Implementation**: Employ Restricted Boltzmann Machines to model the complex relationships within credit card transaction data and identify irregularities.

- **Model Optimization**: Experiment with various architectures, hyperparameters, and training strategies to optimize the performance of both Autoencoder and RBM models.

- **Integration with Traditional Algorithms**: Combine the strengths of deep learning models with traditional fraud detection algorithms and ensemble methods to enhance detection accuracy.

- **Comprehensive Evaluation**: Conduct detailed analysis and evaluation of model performance, discussing challenges, limitations, and potential future advancements.


## Getting Started

### Prerequisites

- Python 3.7+
- Required Python packages

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/kartikeyadangat/Credit-Card-Fraud-Detection
    cd credit-card-fraud-detection
    ```

2. Install the necessary dependencies:

### Usage

1. Prepare the dataset:
   - Place your credit card transaction dataset in the `data/` directory.
   - Ensure the dataset is preprocessed as required by the models.

2. Train the Autoencoder model:

3. Train the RBM model:

4. Evaluate the models and visualize results:


## Future Work

- **Hyperparameter Tuning**: Further optimize model parameters to improve detection accuracy.
- **Hybrid Approaches**: Explore the integration of Autoencoder and RBM models with other machine learning techniques.
- **Real-Time Detection**: Investigate the feasibility of deploying these models for real-time fraud detection in financial systems.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to create a pull request or open an issue.

## Acknowledgements

- The dataset used in this project is sourced from [Kaggle].
- Inspiration for the project is drawn from various research papers and articles on credit card fraud detection using deep learning techniques.
