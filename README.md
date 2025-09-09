# 🎨 Neural Style Transfer Project

## 📖 Overview
This project implements **Neural Style Transfer (NST)** using pretrained **VGG19** from PyTorch.  
NST blends the **content** of one image with the **style** of another by optimizing the input image to match content and style features extracted from a deep CNN.  

---

## ✨ Features
- Uses **pretrained VGG19** for feature extraction.
- Combines **content and style** images into a new artistic output.
- Adjustable parameters:
  - 🖼️ Image size
  - 🔁 Number of iterations
  - ⚖️ Style weight / Content weight
  - 🎨 Total Variation loss for smoother results
- Live **progress preview** during optimization.
- Option to **download the final stylized image**.
- Deployable via **Streamlit** (local or cloud).

---

# The Gwely`s Neural Style Transfer Explorer :

<p align="center">
  <img src="Screenshot 2025-09-08 212907.png" alt="NST Streamlit App UI" width="500"/>
</p>

---

## 🖼️ Example

### Content Image
<p align="center">
  <img src="content.jpg" alt="Content Image" width="400"/>
</p>


<p align="center">
  <img src="Screenshot 2025-09-08 212832.png" alt="Style Image" width="400"/>
</p>

---

### Style Image

### Stylized Output
<p align="center">
  <img src="pngtree-a-majestic-blue-whale-glides-through-starry-cosmic-backdrop-showcasing-its-image_17223334.jpg" alt="Stylized Output" width="500"/>
</p>

---

<p align="center">
  <img src="image (6).webp" alt="Stylized Output" width="500"/>
</p>


<p align="center">
  <img src="image (7).webp" alt="Stylized Output" width="500"/>
</p>





## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/neural-style-transfer.git
   cd neural-style-transfer
   ```


