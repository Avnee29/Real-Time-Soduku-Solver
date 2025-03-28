# Real-Time Sudoku Solver

## Overview
**Real-Time Sudoku Solver** is an application that identifies and solves standard Sudoku puzzles in real-time using **Image Processing** and **Machine Learning (CNN)**. The application captures video, detects the Sudoku board, computes the solution, and overlays the solved puzzle onto the original board.

## Demonstration
![Demo GIF](https://github.com/Avnee29/Real-Time-Soduku-Solver/blob/main/Demo/example.gif)

## Features
- **Real-Time Processing**: Detects and solves Sudoku puzzles from a live camera feed.
- **Computer Vision**: Uses OpenCV to detect and process the Sudoku grid.
- **Machine Learning (CNN)**: Recognizes digits using a Convolutional Neural Network trained on the MNIST dataset.
- **Overlay Solution**: Displays the computed solution on the detected board.
- **Python & Deep Learning**: Implements TensorFlow and Keras for digit recognition.

## Technologies Used
- **Python**: Primary programming language.
- **OpenCV**: Used for image processing and Sudoku board detection.
- **TensorFlow & Keras**: Used to train and deploy the Convolutional Neural Network (CNN) for digit recognition.
- **MNIST Dataset**: Provides training data for recognizing handwritten digits.
- **NumPy & Matplotlib**: Used for numerical operations and visualizing results.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Avnee29/Real-Time-Soduku-Solver.git
   cd Real-Time-Soduku-Solver
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## How It Works
1. Captures a video frame using OpenCV.
2. Detects the Sudoku board and extracts the grid.
3. Preprocesses the grid and recognizes digits using a trained CNN.
4. Solves the Sudoku puzzle using **Best-First Search**.
5. Overlays the solution back onto the original board in real time.

## Contribution
Feel free to contribute by submitting pull requests or reporting issues.

## License
This project is licensed under the **MIT License**.

