# COVID-19_Radiography_Dataset-with-interface
# 🩻 COVID-19 Detection from Chest X-rays using CNN & Grad-CAM

This project implements a Convolutional Neural Network (CNN) to detect **COVID-19, Normal, Lung Opacity, and Viral Pneumonia** from chest X-ray images. It also provides a **Grad-CAM heatmap** visualization to highlight regions in the X-ray image that contributed most to the prediction.

---

## 📌 Features

- **COVID-19 Detection**: Detects if a chest X-ray is COVID-19 positive or falls under other classes like Normal, Lung Opacity, or Viral Pneumonia.
- **Grad-CAM Heatmap**: Highlights important regions in the X-ray influencing the model's decision.
- **Interactive Web Interface**: Built using [Gradio](https://gradio.app) for easy image upload or webcam capture.
- **Download Results**: Save the heatmap overlay for offline use.

---

## 🧰 Technologies & Libraries Used

- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy
- Gradio

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/covid-cnn-gradcam.git
cd covid-cnn-gradcam
