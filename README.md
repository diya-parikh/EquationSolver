# Deep Learning Based Handwritten Mathematical Equation Solver

## Overview  
This project develops a robust system to recognize and solve handwritten mathematical equations using deep learning. Combining Convolutional Neural Networks (CNN) for spatial feature extraction and Recurrent Neural Networks (RNN) for sequence modeling, the system accurately interprets handwritten math expressions despite diverse handwriting styles and complex symbol arrangements. It supports real-time input through an interactive interface, enabling seamless human-computer interaction for education, assistive technology, and scientific computing.

## Main Features  
- **Accurate Symbol Recognition:** CNN-based classification of individual handwritten math symbols.  
- **Sequence Interpretation:** RNNs maintain contextual relationships between symbols for correct equation parsing.  
- **Advanced Preprocessing:** Image processing techniques like bounding box extraction, contour detection, and grayscale conversion to enhance input quality.  
- **Real-time Interface:** User-friendly frontend to draw or upload handwritten equations and receive immediate solutions.  
- **Scalable & Efficient:** Designed to handle varied handwriting and complex equations for practical applications.

## Tech Stack  
- Python, TensorFlow/Keras  
- OpenCV (image preprocessing)  
- Flask / React (web interface)  
- NumPy, Pandas (data handling)  
- GPU acceleration (optional)

## Results  
- High accuracy in character-level recognition across diverse handwriting samples.  
- Effective sequence modeling enabling correct interpretation of complex mathematical expressions.  
- Real-time equation solving demonstrated through an interactive web interface.  
- Scalable performance supporting varied equation complexities and handwriting styles.
