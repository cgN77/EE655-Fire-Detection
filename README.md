# Fire Detection using Deep Learning

This project implements two deep learning models for fire detection in images:

1. A baseline CNN model
2. A flicker-based model with attention mechanisms

## Project Structure

```
fire-detection/
├── data/
│   ├── fire_images/          # Fire image dataset
│   └── non_fire_images/      # Non-fire image dataset
├── models/
│   ├── baseline_model.h5     # Trained baseline model
│   └── flicker_model.h5      # Trained flicker model
├── fire-detection.ipynb      # Main notebook with implementation
└── README.md                 # Project documentation
```

## Dataset

The project uses a custom dataset of fire and non-fire images. The dataset is split into:

- Training set: 80% of images
- Validation set: 20% of images

## Models

### 1. Baseline Model

A simple CNN architecture with:

- 3 convolutional layers
- Max pooling
- Dropout for regularization
- Dense layers for classification

### 2. Flicker Model

An advanced architecture that:

- Uses attention mechanisms
- Implements flicker detection
- Combines spatial and temporal features
- Uses residual connections

## Results

The models are evaluated using:

- Accuracy
- Confusion matrices
- Classification reports
- Training/validation curves

## Requirements

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn

## Usage

1. Clone the repository
2. Install dependencies
3. Run the Jupyter notebook `fire-detection.ipynb`

## License

MIT License
