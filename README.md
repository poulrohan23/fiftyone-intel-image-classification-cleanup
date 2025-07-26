# Image Classification Cleanup

dataset: https://www.kaggle.com/datasets/puneet6060/intel-image-classification

This repository contains a Jupyter Notebook (image_test.ipynb) for cleaning and analyzing an image classification dataset, specifically the Intel Image Classification dataset. The script identifies exact duplicates, blurry images, and wrong predictions, exporting results to CSV files for review and further processing. It uses FiftyOne for dataset management and visualization, with a focus on robustness and reusability for company datasets.

## Features





 - Exact Duplicates: Detects and tags duplicate images, exports to duplicates.csv, with optional deletion code.



 - Blurry Images: Identifies blurry images using Laplacian variance, tags them, and exports to blurry_images.csv, with optional deletion code.



 - Wrong Predictions: Applies mobilenet-v2-imagenet-torch, maps ImageNet predictions to six classes (buildings, forest, glacier, mountain, sea, street), tags mismatches, and exports to wrong_predictions.csv.



 - Visualization: Launches FiftyOne App at localhost:5151 for interactive review of tagged samples.



 - CSV Exports: Saves results for analysis or re-annotation.



 - Robustness: Includes error handling, memory management, and adaptability for other datasets.

