# Assignment 2 — CNN with Data Augmentation

**Student:** Zehra Nisar  
**Course:** Computer Vision CA1-363

## Objective

Build a baseline CNN on 10 labeled images, apply data augmentation using scaling,
rotation, and translation, train the same CNN on the augmented dataset, and compare
the baseline and augmented models.

## Dataset

The notebook uses **CIFAR-10** and selects 10 labeled images, one image from each
of the 10 classes, as the small baseline training dataset.

- Original training images: **10** (1 per class)
- Validation images: **20** (2 per class)
- Augmented variants: **20 per original image**
- Augmented training set: **210 images** (10 originals + 200 augmented variants)

## Model

The same CNN architecture is used for both experiments:

- Conv2D: 32 filters
- Batch Normalization
- Max Pooling
- Conv2D: 64 filters
- Batch Normalization
- Max Pooling
- Conv2D: 128 filters
- Batch Normalization
- Global Average Pooling
- Dense: 64 units
- Dropout: 0.3
- Softmax output: 10 classes
- Optimizer: Adam
- Loss: Sparse Categorical Crossentropy
- Epochs: 30

## Data Augmentation

The notebook applies:

- **Scaling:** `zoom_range=0.2`
- **Rotation:** `rotation_range=25`
- **Translation:** `width_shift_range=0.15`, `height_shift_range=0.15`
- `fill_mode='nearest'`

## Comparison

The notebook compares:

1. Baseline CNN trained on the original 10 images.
2. The same CNN architecture trained on the 210-image augmented dataset.

It produces accuracy and loss comparison curves and evaluates both models on
the same validation set.

## Expected Outputs

When the notebook is run from top to bottom, it generates:

- `baseline_images.png` — the 10 original training images
- `augmented_samples.png` — sample augmented images
- `comparison_plots.png` — baseline vs augmented accuracy/loss curves
- Final validation loss and accuracy for both models
- Written interpretation in the final notebook section

## Important Note

The supplied ZIP contained the notebook and original README, but **did not contain
the three generated PNG result files**. They have therefore not been fabricated or
replaced with placeholder results. The notebook itself contains the code that saves
those images when it is executed.

## How to Run

Open `Assignment-2.ipynb` in Google Colab and run all cells from top to bottom.

No external dataset upload is required because the notebook downloads CIFAR-10
through TensorFlow.

## Conclusion

The assignment demonstrates how data augmentation can help a CNN learn from a very
small labeled dataset by introducing variation in scale, orientation, and position.
The notebook compares the baseline and augmented training behavior and explains
the effect of augmentation on validation performance and overfitting.
