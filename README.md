# 🎨 Color Compression using K-Means

This project was developed as part of the **Applied Mathematics and Statistics** course.  
It applies the **K-Means clustering algorithm** to reduce the number of colors in an image while preserving its overall appearance — demonstrating the use of unsupervised learning in image processing.

---

## 📘 Overview
The goal of this project is to compress images by grouping similar colors into clusters.  
Each pixel in the image is replaced with the color of its nearest cluster centroid, resulting in an output image with **K representative colors**.

---

## 🧠 Key Concepts
- **Unsupervised Learning** – K-Means clustering  
- **Color Quantization** and **Image Compression**  
- **Matrix Operations** using NumPy  
- Image manipulation with **PIL** and **Matplotlib**

---

## 🧩 Implementation
The implementation was done in a **Jupyter Notebook (`MSSV.ipynb`)** with the following components:
- Read and display input images  
- Reshape the image from 2D → 1D for clustering  
- Apply **K-Means** to find K color centroids  
- Reconstruct the compressed image  
- Save results in `.png` and `.pdf` formats  

---

## 🛠️ Technologies
- **Python 3**
- **NumPy**
- **PIL (Pillow)**
- **Matplotlib**

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/color-compression-kmeans.git
   cd color-compression-kmeans
