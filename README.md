# Image and Video Inspection using Deep Learning

This project performs image and video inspection using a pretrained ResNet-50 model.  
It classifies video frames in real time and displays predicted labels with confidence scores.

---

## 🔍 Functionality
- Image classification using ResNet-50
- Real-time video frame classification
- Frame sampling for efficiency (every 15th frame)
- Displays predictions with confidence

---

## 📦 Imports
```python
import torch
import torchvision.transforms as transforms
from torchvision import models
from PIL import Image
import tkinter as tk
from tkinter import filedialog
import os
import cv2
import numpy as np
```

---

## ▶️ Usage

### 1. Install dependencies
```bash
pip install torch torchvision opencv-python pillow numpy
```

### 2. Run the script
```bash
python your_script_name.py
```
