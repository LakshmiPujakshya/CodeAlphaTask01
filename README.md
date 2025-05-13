# 🧠 Face Detection on Images Using OpenCV

This project demonstrates how to detect human faces in an image using OpenCV's Haar Cascade Classifier. It displays both the original image and the image with rectangles drawn around the detected faces.

---

## 📂 Project Structure

face_detection_project/
├── face_detection.ipynb # Main Jupyter Notebook
├── haarcascade_frontalface_default.xml # Haar Cascade file
├── your_image.jpg # Input image file
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 How to Run

### 1. Install Required Libraries

Make sure you have Python and pip installed. Then run:

```bash
pip install opencv-python matplotlib
2. Download the Haar Cascade XML File
You need the file haarcascade_frontalface_default.xml. Download it from:

🔗 https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml

Place this file in the same folder as your notebook.

3. Run the Notebook
Open face_detection.ipynb using Jupyter Notebook, Google Colab, or VS Code and run all cells. The notebook will:

Display the original image.

Detect faces in the image.

Show a new image with rectangles around each detected face.

📷 Sample Output
Original Image
The input image is shown before any processing.

Detected Faces
Faces are highlighted using blue rectangles.

🛠️ Technologies Used
Python 🐍

OpenCV 📷

Matplotlib 📊

Jupyter Notebook 📓

⚠️ Limitations
Best suited for real human faces.

Might not work well on cartoon or anime faces (e.g., Doraemon characters).

Accuracy may be affected by lighting, orientation, or occlusion.


