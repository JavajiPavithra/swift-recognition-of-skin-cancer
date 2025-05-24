# swift-recognition-of-skin-cancer
This project is a web-based image classification system designed to assist in the identification and diagnosis of skin conditions, specifically skin cancer. It uses deep learning models built with TensorFlow/Keras and is deployed through a Flask web application.

To run the code "python main.py"

Download images for online and upload it.

How It Works
User uploads an image.

The app uses model1 to determine if the image is of human skin.

If it's a skin image, it uses model2 to predict whether the skin has cancer.

If cancer is detected, model3 is used to classify as benign or malignant.

The result is displayed on the screen, and optionally redirects to different HTML pages (Benign.html, Malignant.html).

