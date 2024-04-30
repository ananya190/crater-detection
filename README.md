# Deep Learning for Crater Detection

Finetuning PyTorch object detection models for the task of crater detection.

## How to use this code

* The notebooks under the `training/` directory can either be uploaded to
Google Colab, or run locally, in which case, ignore the Colab specific
commands, and ensure the required packages are installed.
* The predictor notebook requires makes use of `pillow`, `opencv-python`,
`matplotlib`, `numpy`, `torchvision`, `pytorch` and `ultralytics`.
* Provide the paths to the models and images on which you want to predict in
`predictor.ipynb`. The models can either be trained using the `training/`
notebooks, or can be downloaded from Releases.
