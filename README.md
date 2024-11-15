The Automatic Number Plate Recognition (ANPR) system is a deep learning-based project designed to detect and recognize vehicle license plates from images or videos. This project leverages the Inception ResNet model for efficient and accurate plate recognition, making it suitable for applications like traffic monitoring, toll collection, parking management, and security systems.

Features:
End-to-End Pipeline: From image preprocessing to plate recognition.
Deep Learning Architecture: Uses the Inception ResNet model for robust recognition.
Scalability: Can be extended to support real-time video streams.
Localization: Identifies the region of the license plate in an image.
Recognition: Extracts text from the localized plate with high accuracy.


Technology Stack:
Programming Language: Python
Deep Learning Framework: TensorFlow/Keras
Model Used: Inception ResNet


Libraries:
OpenCV: For image processing
NumPy: For numerical computations
Matplotlib: For visualizing results
Tesseract OCR: (Optional) For Optical Character Recognition

Dataset:
The project uses a combination of publicly available datasets and custom-collected images to train and evaluate the model.
Datasets include diverse license plate images from different regions and conditions to ensure model robustness.

How It Works:
Input Image/Video:
The system accepts images or video streams containing vehicles.

Preprocessing:
Resizes and normalizes the input.
Detects the region of interest (license plate) using object detection techniques.

License Plate Recognition:
Extracts the license plate text using the trained Inception ResNet model.

Output:
Displays the extracted license plate number.
