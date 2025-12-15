## Installation & Setup

# Prerequisites

Python 3.8 or higher
pip package manager
Optional: CUDA-enabled GPU for faster training

## Install Dependencies

Using pip:
pip install torch torchvision numpy matplotlib tqdm

## Requirements

torch version 2.0.0 or higher
torchvision version 0.15.0 or higher
numpy version 1.24.0 or higher
matplotlib version 3.7.0 or higher
tqdm version 4.65.0 or higher

## How to Run

Clone or download this repository
Install the required dependencies listed above
Open the Jupyter Notebook included in the repository
Run all cells sequentially (Cell → Run All)
Training takes approximately 5 to 15 minutes depending on the hardware used

## Outputs

The notebook generates the following outputs:
best_model.pth – trained model weights
training_curves.png – visualization of training metrics
error_analysis.png – error distribution analysis
prediction_samples.png – sample model predictions
additional analysis and visualization outputs

## Hardware Requirements

CPU: Supported (training time approximately 15 minutes)
GPU: Recommended (training time approximately 5 minutes)
RAM: Minimum 4 GB
Storage: Approximately 100 MB for datasets and generated outputs
