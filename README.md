# Face-Mask-Detector
![image alt](https://github.com/singh-rounak/Face-Mask-Detector/blob/develop/images/Face%20Mask%20Detection.png?raw=true)
## OVERVIEW:
This project implements a deep learning model to detect whether individuals are wearing face masks. Utilizing computer vision techniques, the system processes images or video streams to identify faces and classify them as either "Mask" or "No Mask".

REFERENCE:
[1] Lippert, Christoph, and Benjamin Bergner. "Face Mask Detector."
[2] Das, Arjya, Mohammad Wasif Ansari, and Rohini Basak. "Covid-19 Face Mask
Detection Using TensorFlow, Keras and OpenCV. 

## FEATURES:
Real-Time Detection: Processes live video streams to detect face masks in real-time.
Deep Learning Model: Employs a Convolutional Neural Network (CNN) trained on a dataset of masked and unmasked faces.
User-Friendly Interface: Displays detection results with bounding boxes and labels on the video feed.

## PREREQUISITES
Ensure you have the following installed:

Python 3.x

TensorFlow

Keras

OpenCV

NumPy

Matplotlib

You can install the required packages using pip:

```python
pip install tensorflow keras opencv-python numpy matplotlib
```

## INSTALLATION:

1. Clone the repository:

```bash
git clone https://github.com/singh-rounak/Face-Mask-Detector.git
cd Face-Mask-Detector
```

3. Extract the dataset:

Unzip the datafm.rar file to access the dataset.

5. Run the Jupyter Notebook:
Open and execute the Face Mask Detector.ipynb notebook to train the model and perform detections.

## USAGE
1. Training the Model:

The notebook guides you through loading the dataset, preprocessing images, and training the CNN model.
Dataset:
![image alt](https://github.com/singh-rounak/Face-Mask-Detector/blob/develop/images/Mask_NoMask_Dataset.png?raw=true)

Methodoly:
![image alt](https://github.com/singh-rounak/Face-Mask-Detector/blob/develop/images/FaceMask%20Methodology.png?raw=true)

2. Real-Time Detection:

After training, the model can process live video feeds from your webcam to detect face masks.
Live Feed: Initial Face detection using Haar Cascade Classifier
![image alt](https://github.com/singh-rounak/Face-Mask-Detector/blob/develop/Face%20Capture.PNG?raw=true)

Model Results
The model achieves high accuracy in distinguishing between masked and unmasked faces. Sample outputs are provided in the repository images.

Accuracy and Model Loss:
![image alt](https://github.com/singh-rounak/Face-Mask-Detector/blob/develop/images/FaceMask%20results.png?raw=true)


Results:

1. Identifying No Mask
![image alt](https://github.com/singh-rounak/Face-Mask-Detector/blob/develop/images/No%20Mask.png?raw=true)
2. Identifying Mask
![image alt](https://github.com/singh-rounak/Face-Mask-Detector/blob/develop/images/Mask.png?raw=true)

## REPORT:
For an in-depth understanding of the project's methodology, refer to the Final Report.pdf, which covers:

Data collection and preprocessing
Model architecture and training
Evaluation metrics
Challenges and future work

## CONTRIBUTING:
Contributions are welcome! If you'd like to enhance the model or add new features, feel free to fork the repository and submit a pull request.

## License

[MIT](https://choosealicense.com/licenses/mit/)
