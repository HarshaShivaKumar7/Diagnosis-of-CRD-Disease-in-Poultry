# CRD Disease Detection in Poultry Diagnostics 🐣🐓

This Streamlit web application is designed for detecting CRD (Chronic Respiratory Disease) in poultry diagnostics. It employs a pre-trained TensorFlow model based on MobileNetV2 for classification tasks.

## Usage
1. **Upload Image**: Users can upload an image file (JPEG, JPG, or PNG) containing a chicken for disease stage detection.
2. **Detection**: The app processes the uploaded image and predicts the disease stage as one of the following categories:
   - Early stage
   - Middle stage
   - Later stage
   - Healthy Poultry
   - Other Disease

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
   ```
   git clone https://github.com/HarshaShivaKumar7/Diagnosis-of-CRD-Disease-in-Poultry.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

## Model
The model used for disease detection is MobileNetV2, fine-tuned for poultry disease classification. The trained model file (`new_mobilenetv2_ft.h5`) is located in the `./model/mobilenetV2/` directory.

## Credits
- TensorFlow: https://www.tensorflow.org/
- Streamlit: https://streamlit.io/
- OpenAI for AI language model support

## Disclaimer
This project is for educational and demonstration purposes only. It is not intended for medical diagnosis or treatment. Consult a veterinarian or poultry expert for accurate disease diagnosis and management.

Feel free to contribute to the project by providing feedback, reporting issues, or submitting pull requests. Happy coding! 🚀
