# Brain-Tumor-Prediction-Computer-Vision-
A computer vision project designed to identify the type of brain tumor in a user-provided image, using a model trained on a large dataset.


# Features
- Upload and process images directly in Google Colab
- Use a pre-trained model to classify brain tumor images
- Automatically log predictions and confidence scores to Google Sheets
- Visual feedback for each uploaded image


# Requirements
Make sure the following libraries are available in your Colab environment:
- `numpy`
- `gspread`
- `google-auth`
- `cv2` (OpenCV)
- `google.colab` (for authentication and file upload)
- A pre-trained model assigned to the variable `model`
- Defined global variables:
- `categories`: list of class names (e.g., `['glioma_tumor', 'meningioma_tumor', 'pituitary_tumor', 'normal']`)
- `IMG_SIZE`: the expected size for input images (e.g., 224)
- `files`: from `google.colab import files`
- `IPyImage`: from `IPython.display import Image as IPyImage`


# The Dataset Link: 
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
