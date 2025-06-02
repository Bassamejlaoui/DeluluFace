# 🎭 DeluluFace: Face Swapping with DeepSwapFace

**DeluluFace** is a high-quality face swapping application powered by deep learning. It leverages PyTorch and Hugging Face Spaces to deliver realistic, fast, and user-friendly face swapping experiences directly on Google Colab.

![image](https://github.com/user-attachments/assets/aa5bdfb3-f1d5-4626-a8e2-27794d5eed1c)


[![DeluluFace](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/victorgeel/FaceSwapNoNfsw/blob/main/SwapFace.ipynb#scrollTo=386ajdZ0ixQ0)


---

## 📌 Overview

- **Project Type**: Face Swapping / Deep Learning  
- **Tech Stack**: Python, PyTorch, CUDA, Gradio  
- **Environment**: Google Colab (GPU-enabled)  
- **License**: For research and educational use only

---

## ⚙️ Setup Instructions (Google Colab)

### ✅ Step 1: Install Git LFS
```bash
!git lfs install
````

### ✅ Step 2: Clone the Repository

```bash
!git clone https://huggingface.co/spaces/victorisgeek/DeepSwapFace
```

### ✅ Step 3: Navigate to the Project Folder

```python
%cd /content/DeepSwapFace
```

### ✅ Step 4: Install Dependencies

```bash
!pip install -r requirements.txt -q
!pip install gdown
```

---

## 🚀 Run the Application

```python
default_output_path = "/content/DeepSwapFace"
command = f"python app.py --cuda --colab --out_dir {default_output_path}"
!{command}
```

> 💡 The app runs in command-line mode optimized for Google Colab. CUDA acceleration is used by default.

---

## 📂 Project Structure

```
DeluluFace/
├── app.py                  # Main application script
├── requirements.txt        # Python dependencies
├── models/                 # Pretrained models (via Git LFS)
├── utils/                  # Utility functions
└── outputs/                # Face swapped results
```

---

## 🧠 Features

* ✅ Real-time face swapping
* ✅ CUDA-accelerated processing
* ✅ Google Colab friendly setup
* ✅ CLI and Gradio-ready interfaces
* ✅ Based on DeepSwapFace with minimal changes

---

## 📸 Example Use Cases

* 🎬 Creative media and content generation
* 👤 Avatar creation and digital identity prototyping
* 🤖 AI training data generation
* 🛡️ Anonymization and privacy-preserving technologies

---

## ⚠️ Disclaimer

This tool is intended **strictly for research and educational purposes**. Misuse for identity fraud, impersonation, or any unethical activity is strictly prohibited. Always comply with relevant laws and terms of service.

---

## 📥 Credits

* Based on: [DeepSwapFace by victorisgeek](https://huggingface.co/spaces/victorisgeek/DeepSwapFace)
* Adaptation & Documentation by: \[[@Bassamejlaoui](https://github.com/Bassamejlaoui/)]

---

## 🧪 Status

**Under continuous testing and experimentation. Contributions welcome.**

---

## 🌐 Connect

For questions, feedback, or collaboration opportunities, feel free to open an issue or reach out.

---
