# Dog Breed Prediction

This project is a web-based application that predicts dog breeds from an uploaded image. It is built using Python and leverages Flask for the backend, OpenCV for image processing, Keras for deep learning model handling, and Streamlit for an interactive frontend.

### Key Technologies
- **Python:** Core programming language used.
- **Flask:** Backend web framework to handle API requests and responses.
- **OpenCV:** Library for image preprocessing (e.g., resizing, conversion to arrays).
- **Keras:** Deep learning framework used for model training and prediction.
- **Streamlit:** A user-friendly framework for creating and deploying the interactive web app interface.

### Features
- Upload an image of a dog to the web app.
- The app uses a pre-trained Keras model to predict the dog's breed.
- Interactive frontend built with Streamlit to display predictions.

### Setup
1. Install dependencies: `pip install -r requirements.txt`
2. Run the Flask server: `python app.py`
3. Access the Streamlit interface: `streamlit run app.py`

This project combines machine learning, web development, and computer vision to predict dog breeds from images efficiently and interactively.
