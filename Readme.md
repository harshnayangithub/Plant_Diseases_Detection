# Plant Disease Detection using Machine Learning

This project aims to detect plant diseases using machine learning techniques. It uses a Convolutional Neural Network (CNN) model trained on a dataset of plant images to classify images into healthy or diseased plants.

## Features

- **Web Interface**: Provides a user-friendly web interface for users to upload images of plants for disease detection.
- **Real-time Detection**: Utilizes a trained CNN model to detect diseases in plants with high accuracy.
- **Disease Classification**: Classifies detected diseases into various categories for easy identification.

## Technologies Used

- **Flask**: Web framework used to develop the web application.
- **Python**: Programming language used for the backend logic and machine learning model.
- **PyTorch**: Deep learning framework used to build and train the CNN model.
- **HTML/CSS**: Frontend technologies used for designing the web interface.
  
## Usage

1. Install the required dependencies using `pip install -r requirements.txt`.
2. Run the Flask application using `python app.py`.
3. Access the web interface in your browser at `http://localhost:5000`.
4. Upload an image of a plant to detect diseases.


## Model Training

The CNN model was trained using PyTorch on a dataset of plant images. The training code can be found in the `train_model.ipynb` Jupyter notebook.
