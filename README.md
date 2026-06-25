# Brain Tumor Detection using CNN

A Streamlit web application that classifies brain MRI images using a trained Convolutional Neural Network model. The app loads a saved Keras model (`brain_tumor.h5`) and predicts one of four classes:

- Glioma
- Meningioma
- No Tumor
- Pituitary

## Features

- Upload MRI images in JPG, JPEG, or PNG format
- Display the uploaded MRI image
- Classify the image using a CNN model
- Show the predicted tumor class
- Display confidence score and class-wise prediction probabilities

## Project Structure

```text
Brain-Tumor-Detection-using-CNN-main/
├── brain_tumor_app.py      # Streamlit application
├── brain_tumor.h5          # Trained CNN model
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

## Requirements

- Python 3.8 or above
- pip

Install the required packages:

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Brain-Tumor-Detection-using-CNN.git
cd Brain-Tumor-Detection-using-CNN
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Streamlit app:

```bash
streamlit run brain_tumor_app.py
```

4. Open the local URL shown in the terminal, usually:

```text
http://localhost:8501
```

## Usage

1. Launch the Streamlit app.
2. Upload a brain MRI image in JPG, JPEG, or PNG format.
3. The app displays the uploaded image.
4. The trained CNN model predicts the class.
5. The prediction, confidence score, and probability for each class are displayed.

## Model Details

The application uses a trained Keras model saved as `brain_tumor.h5`. Uploaded images are converted to RGB, resized to `128x128`, and passed to the model for classification.

## Dependencies

The main libraries used in this project are:

- Streamlit
- TensorFlow
- NumPy
- Pillow
- h5py

## Important Note

This project is intended for educational and research purposes only. It should not be used as a substitute for professional medical diagnosis. Always consult qualified medical professionals for clinical decisions.


