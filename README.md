# Deep Learning Clothing Classification

## Project Description
A deep learning project implementing clothing classification using the Fashion MNIST dataset. The project includes model interpretation capabilities to understand and visualize model decisions.

## Project Structure
```
DEEP-LEARNING-CLOTHING-CLASSIFICATION/
├── data/                  
├── logo/                  
├── Classifier.ipynb       # Main classification notebook
├── poetry.lock          
├── pyproject.toml       
└── README.md            
```

## Features
- Fashion MNIST dataset classification into 10 clothing categories
- Model interpretation tools including:
  - Confusion matrix visualization
  - Layer activation analysis
  - Prediction confidence assessment
- Support for multiple hardware acceleration options (MPS, CUDA, CPU)

## Setup

### Prerequisites
- Python environment (version specified in pyproject.toml)
- Poetry for dependency management

### Installation
```bash
# Install poetry if not already installed
pip install poetry

# Install project dependencies
poetry install
```

## Dataset
The project uses the Fashion MNIST dataset, which includes:
- 60,000 training images
- 10,000 test images
- 10 clothing categories
- 28x28 grayscale images

## Model Architecture
Convolutional Neural Network with:
- Batch normalization for training stability
- Dropout layers for regularization
- Dense classification layers
- Configurable input channels

## Model Analysis
Includes tools for:
- Training progress visualization
- Performance metrics calculation
- Model interpretation capabilities
- Confidence analysis

## Dependencies
Core dependencies (full list in pyproject.toml):
- PyTorch
- torchvision
- torchmetrics
- captum
- matplotlib
- seaborn
- scikit-learn

## License
See LICENSE file in the repository.