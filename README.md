# Cats and Dogs Image Classifier

This notebook classifies images of cats and dogs using machine learning techniques. Below are the steps, operations, and libraries involved.

## Libraries Used
- `os`: To interact with the file system and directories.
- `pandas`: For organizing and manipulating image data.
- `numpy`: For handling numerical data and arrays.
- `matplotlib`: For visualizing images and results.
- `cv2` (OpenCV): For image processing tasks like loading and resizing images.
- `sklearn`: For preprocessing and training data.

## Project Workflow

### 1. Reading Images
The images are stored in a local folder, and the notebook loads them. The images are divided into two classes based on their file names: `cat` and `dog`.

### 2. Classifying Images
Using the file names, images are categorized into two lists: one for cats and one for dogs. A sample of 1500 images from each category is selected for further analysis.

### 3. Organizing Data
A `pandas` DataFrame is created, containing the image file names and their corresponding class labels (`cat` or `dog`).

### 4. Loading and Preprocessing Images
The images are loaded using the `cv2` library and prepared for machine learning model input. Common preprocessing steps might include:
- Resizing images to a fixed size.
- Normalizing pixel values.
- Splitting data into training and testing sets.

### 5. Model Training
A supervised machine learning model (SVC) is used to classify the images. 

### 6. Model Evaluation
The model's performance is evaluated using various metrics such as accuracy, precision, and recall.

### 7. Visualization
The notebook includes visualizations of:
- Sample images from the dataset.
- Training progress, including accuracy and loss graphs.
- Performance metrics and predictions on sample images.

## How to Run the Notebook
1. Ensure the required libraries (`pandas`, `numpy`, `matplotlib`, `opencv-python`) are installed.
2. Place the cat and dog images in the appropriate folder (`./train`).
3. Run the notebook step-by-step to process the images, train the model, and evaluate performance.

## Results
The notebook outputs the classification accuracy of the model and visualizes predictions on a subset of the images.

---
**You can find the full dataset (images) in this link** [Cats and Dogs classifier](https://www.kaggle.com/c/dogs-vs-cats/data?select=train.zip)