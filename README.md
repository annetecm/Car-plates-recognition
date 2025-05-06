# License Plate Text Recognition

This project uses **Python**, **OpenCV**, and **EasyOCR** to detect and extract text from license plates.

## Sample Input

The system works with images like the following:

- Decorative license plates with custom text (e.g., "JALISCO", "TU-TEXTO")
- Images in JPG format taken with a smartphone or downloaded from the web

## Technologies Used

- [Python 3](https://www.python.org/)
- [OpenCV](https://opencv.org/)
- [EasyOCR](https://github.com/JaidedAI/EasyOCR)
- [NumPy](https://numpy.org/)
- [Matplotlib (for display)](https://matplotlib.org/)

## What the project does

1. Loads an image of a license plate
2. Applies preprocessing to highlight dark text over light background
3. Extracts text using EasyOCR
4. Displays the image and prints detected text

## 🚀 How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/annetecm/Car-plates-recognition.git
    cd Car-plates-recognition
    ```

2. Install the required packages:
    ```bash
    pip install opencv-python numpy easyocr matplotlib
    ```

Make sure your image (e.g. `placa_q.jpg` or `placa_4.jpg`) is in the same folder.

## Example Output
![Sample Plate](placaFiltrada.jpg)
Jaltsci (confianza: 0.36)



