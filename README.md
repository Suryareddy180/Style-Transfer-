# Style-Transfer-
This project applies artistic style transfer to each frame of a video using a style image, powered by TensorFlow Hub's Magenta model. It processes videos frame-by-frame with OpenCV and saves the output as a stylized .mp4 file, allowing users to create creative, AI-enhanced video content.

# 🎨 Video Style Transfer using TensorFlow Hub

This project performs **style transfer** on a video by applying the artistic style of a given image frame-by-frame using a pre-trained model from TensorFlow Hub.

---

## 📌 Features

- Applies **artistic style** from an image to each frame of a video.
- Uses **TensorFlow Hub**'s Magenta model: `arbitrary-image-stylization-v1-256`.
- Efficient frame processing using **OpenCV** and **NumPy**.
- Outputs a stylized video in `.mp4` format.

---

## 🧰 Requirements

Install dependencies using pip:

```bash
pip install tensorflow tensorflow_hub opencv-python numpy
