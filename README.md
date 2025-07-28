# 🎨 STYLE TRANSFER USING PRE-TRAINED MODEL 🎬

This project applies **artistic style transfer** to videos using TensorFlow Hub's **Magenta style transfer model**, enhanced with **sharpening filters**, **frame upscaling**, and **original audio retention**. It processes videos frame-by-frame using OpenCV and TensorFlow, resulting in a **visually stunning and AI-enhanced output video**.

---

## 🚀 Features

- 🎨 **Style Transfer**: Applies the visual style of any image to each frame of a video.
- 📈 **Super High Visual Clarity**: Uses 512x512 frame processing, sharpening filters, and optional super-resolution.
- 🔊 **Audio Preservation**: Retains the original audio using MoviePy.
- ⚡ **Efficient Frame-by-Frame Processing**: Combines the power of TensorFlow, OpenCV, and NumPy.
- 📦 **Export in High Bitrate**: Ensures crisp quality output using `libx264` codec at 5000 kbps.

---

## 📦 Dependencies

Install required packages using pip:

```bash
pip install tensorflow tensorflow_hub opencv-python moviepy numpy
```

## 🧠 How It Works
- Loads the TensorFlow Hub model: magenta/arbitrary-image-stylization-v1-256.
- Resizes each frame to 512x512 and applies style transfer.
- Applies advanced sharpening filters for enhanced clarity.
- Reconstructs the video in original resolution and re-attaches the original audio.

## 🧪 Example Usage
``` bash
input_video_path = '/content/stock3.mp4'
style_image_path = '/content/scene9.jpg'
output_video_path = '/content/output_super_high_quality.mp4'

style_transfer_video(input_video_path, style_image_path, output_video_path)
```
## 🎯 Output
- Format: .mp4

- Codec: libx264

- Audio: Original input audio preserved

- Bitrate: 5000 kbps (for better visual quality)

## 📸 Preview
Stylize your own videos with just a few lines of code and bring static art to life in motion! Whether you're an artist, content creator, or developer — this tool helps you build stunning visual stories with AI.

