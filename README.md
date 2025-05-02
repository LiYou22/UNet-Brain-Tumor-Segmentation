# UNet-Brain-Tumor-Segmentation

This project focused on brain tumor segmentation task on Medical Segmentation Decathlon BraTS dataset with U-Net.

## Get Started

### Environment Setup

Set up the Python environment for the project:

```
# Create and activate conda environment
conda create -n brain_seg python==3.11
conda activate brain_seg

# Install dependencies
pip install -r requirements.txt
```

### Train & Evaluate

Run the notebook to train & evaluate the model.

## Results

### Loss & Dice over Epochs

![Training & Validation Loss & Dice](visualization/train/cross_validation_curves.png)

### Inference Examples

![example_15](visualization/evaluate/example_15.png)

![example_39](visualization/evaluate/example_39.png)

![example_84](visualization/evaluate/example_84.png)

