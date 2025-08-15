# 📄 AI-Powered Document Scanner

<img width="1112" height="626" alt="image" src="https://github.com/user-attachments/assets/9fb86beb-48e4-4cd2-ab7d-abc907611f25" />


A smart Python tool that automatically detects a document within an image, corrects its perspective, and produces a clean, top-down "scanned" view. This project was developed as a capstone for my internship, showcasing skills in computer vision and image processing.

---
## ✨ Key Features

* **Automatic Edge Detection:** Intelligently finds the four corners of a document using OpenCV's Canny edge detection and contour analysis.
* **Perspective Correction:** Applies a perspective transform to "un-skew" the document, creating a perfectly rectangular, top-down image.
* **Image Enhancement:** Improves the final output with adaptive thresholding to create a high-contrast, black-and-white scan.
* **Simple & Efficient:** Built with a streamlined pipeline using industry-standard libraries.

---
## 🛠️ Technologies Used

* **Python**
* **OpenCV**
* **NumPy**
* **Matplotlib**
* **Google Colab / Jupyter Lab**

---
## 🚀 How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/KBarathraj/AI-Document-Scanner.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd AI-Document-Scanner
    ```

3.  **Run the script in your environment (e.g., Google Colab):**
    Open the `.ipynb` file and upload an image of a document to be scanned. The notebook will process the image and display the final scanned output.

---
