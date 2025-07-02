# 🧠 Object Boundary Segmentation using BASNet

This project uses the Boundary-Aware Salient Object Detection Network (BASNet) for highly accurate object segmentation. BASNet refines object boundaries and produces detailed binary masks, useful in applications like medical imaging, saliency detection, and photo editing.

---

## 📊 Overview

- Uses pretrained BASNet model for salient object segmentation  
- Applies segmentation on test images and saves binary mask predictions  
- Visual comparison of original image, predicted mask, and output  
- Supports batch processing of image folders

---

## 📁 Files Included

- `BASNet.ipynb` — Full implementation and visual result generation  
- `requirements.txt` — Required Python packages  

---

## 🛠️ Techniques Used

- Deep Convolutional Encoder-Decoder  
- Salient Object Detection  
- Binary Mask Generation  
- PyTorch-based inference pipeline  
- Pretrained model loading from official BASNet repo

---

## 📦 Data

This project uses test images provided locally.  
Predictions are generated for all images in the test directory.

> ⚠️ The dataset is not included. You may use standard saliency datasets such as DUTS, ECSSD, or your own test set.


---

## 👩‍💻 Author

**Wajeeha Sajid**  
Electrical and Computer Engineering  
[GitHub Profile](https://github.com/wajeeha-sajid)

