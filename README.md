# Plant_Leaf_Segmentation
# 🌿 Plant Leaf Segmentation

## Overview

This repository contains a **deep learning-based segmentation model** for accurately detecting and segmenting plant leaves. The model is trained on a custom dataset in **LabelMe JSON format** and leverages **U-Net architecture** for pixel-wise classification.

## Features

✅ **High-precision segmentation** using U-Net  
✅ **Supports LabelMe JSON dataset format**  
✅ **Optimized training pipeline** with PyTorch  
✅ **Custom preprocessing & augmentation**  
✅ **Visualization tools for evaluation**  

## Installation

```bash
# Clone the repository
git clone https://github.com/your-username/plant-leaf-segmentation.git
cd plant-leaf-segmentation

# Install dependencies
pip install -r requirements.txt
```

## Usage

### 1️⃣ Train the Model

```bash
python train.py --epochs 50 --batch_size 16 --lr 0.001
```

### 2️⃣ Test the Model

```bash
python test.py --checkpoint best_model.pth
```

### 3️⃣ Inference on Custom Images

```bash
python infer.py --image path/to/image.jpg --checkpoint best_model.pth
```

## Dataset

The dataset follows the **LabelMe JSON** structure:

```
Plant_Unet_Dataset1/
 ├── images/       # Original images
 ├── JSON_Files/   # JSON annotation files (LabelMe format)
 ├── masks/        # Segmentation masks
```

## Results

📊 **IoU Score**: 0.85+  
🖼️ Sample Predictions:

## Contributing

Contributions are welcome! Feel free to **fork**, **submit issues**, and **pull requests**.

## License

📜 MIT License

---

🚀 **Developed with PyTorch for robust plant leaf segmentation!**

