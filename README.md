# 🖼️ Image Resizing Script (50% Smaller)
This Python script resizes the first 10 images from a folder to 50% of their original dimensions using OpenCV. It’s helpful for reducing image sizes in bulk while maintaining aspect ratio.

## ✅ Features
- 📂 Processes up to 10 images automatically

- 📏 Resizes each image to 50% of its width and height

- 💾 Saves resized images to a separate output folder

- 🖼️ Supports common formats: `.jpg`, `.jpeg`, `.png`, `.webp`

## 🧠 What This Script Does
1. Reads images from an input folder (`input_images/`)

2. Calculates new size (half the original width and height)

3. Uses `cv2.resize()` to resize each image

4. Saves results to `resized_images/` folder

## 🛠️ Requirements
- Python 3.x

- OpenCV (install via pip):

      pip install opencv-python

## 🚀 How to Use
1. Create a folder called `input_images/` in the same directory as your script.

2. Add at least 10 images to that folder.

3. Run the script:

       python resize_script.py
   
4. Check the `resized_images/` folder for the resized images.

## 🧪 Example Output
If your original image was `1000x800` pixels, the resized image will be:
  
    500x400
