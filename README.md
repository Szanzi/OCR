# Handwritten Digit Recognizer AI 

A machine learning application built entirely from scratch in Python that recognizes handwritten digits in real-time. 

## About the Project
This project implements custom **k-Nearest Neighbors (kNN)** and **Centroid-based** classification algorithms without relying on external machine learning libraries like `scikit-learn` or `TensorFlow`. The models were trained on the Optical Recognition of Handwritten Digits dataset.

The application includes a custom Tkinter-based graphical user interface (GUI) with an interactive drawing canvas. It performs real-time image preprocessing (grayscale conversion, inversion, bounding-box cropping, and padding) to match the exact mathematical format of the training dataset.

> **Note on Source Code:** Due to strict university academic integrity policies regarding ongoing assignments, the `.py` source code is temporarily closed-source. However, a fully compiled, standalone executable is provided for testing!

## How to Run 
You don't need Python installed to test the AI! 
1. Open the `dist` folder.
2. Ensure `optdigits.tra` (training data) is in the same folder as the executable.
3. Run `rajz.exe`.
4. Draw a digit (0-9) on the canvas and click "Recognize" to see the AI's prediction in the console!

## Features
* **Zero-Dependency ML:** Distance calculations and classifications written in pure Python.
* **Smart Preprocessing:** Uses `Pillow` to dynamically crop and pad drawings to fix aspect ratio distortions.
* **Interactive UI:** A minimal, easy-to-use digital canvas.
