#  American Sign Language Detection

This project detects and classifies American Sign Language (ASL) hand gestures using a Convolutional Neural Network. It supports static alphabets (A-Z) for text-based gesture recognition.

##  Problem Statement
Translate ASL hand gestures to letters using a CNN model trained on labeled images of static signs.

##  Objectives
- Build a model to classify hand gestures into alphabets (A–Z)
- Achieve high accuracy on validation data
- Enable future use in real-time applications

##  Dataset
- Static images of ASL hand signs
- Categories: A to Z (except dynamic ones like J, Z)
- Augmentation and grayscale conversion applied

## 🛠 Tools & Libraries
- Python  
- TensorFlow, Keras  
- OpenCV  
- Matplotlib, NumPy

##  Model Performance
- **Training Accuracy**: ~98%  
- **Testing Accuracy**: ~92%  
- Evaluation: Confusion matrix, accuracy graph

##  Visuals
- Predicted vs actual images  
- Model architecture summary  
- Training graphs

##  Future Work
- Integrate webcam-based real-time ASL detector  
- Extend to dynamic gestures (J, Z)  
- Convert signs to text-to-speech

