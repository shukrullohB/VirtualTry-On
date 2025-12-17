# 👕 VirtualFit: AI-Powered Virtual Try-On

**Central Asian University (CAU)** *Computer Vision Final Project*

![Banner](assets/result_example.png)

## 📌 Project Overview
VirtualFit is a virtual try-on application that allows users to upload a photo of themselves and a garment to realistically visualize how it looks on their body. [cite_start]By leveraging the **IDM-VTON** model and a custom **HTML/Gradio** interface, we aim to solve the problem of online return rates and enhance the e-commerce experience[cite: 13, 14, 24].

## 👥 Team Members (VirtualFit)
* [cite_start]**Shukrullo Baxtiyorov** (ID: 220411) - Backend & AI Model Implementation [cite: 6, 7]
* [cite_start]**Akmaljon Polatjonov** (ID: 220484) - Data Preparation & Frontend [cite: 8]
* [cite_start]**Sirojiddin Khaydarov** (ID: 220673) - Testing, Documentation & QA [cite: 9]

## 🚀 Key Features
* **Photorealistic Try-On:** Uses advanced diffusion models for texture preservation.
* **Auto-Masking:** Automatically detects body and clothing shapes.
* **User-Friendly Interface:** Modern web UI with Dark Mode support.
* **Google Colab Integration:** Runs on free GPU resources via Gradio tunneling.

## 🛠️ Tech Stack
* **Model:** IDM-VTON (Diffusion-based Inpainting)
* **Backend:** Python, PyTorch, Diffusers, Gradio
* **Frontend:** HTML5, CSS3 (Glassmorphism Design)
* **Platform:** Google Colab (T4 GPU)

## 💻 How to Run
1. Open the notebook in `notebooks/VirtualFit_Inference.ipynb` via Google Colab.
2. Run all cells to install dependencies and start the Gradio server.
3. Copy the public link (e.g., `https://xxxx.gradio.live`).
4. Open `web/index.html` on your local machine.
5. Paste the link into the code (or use the direct Gradio interface).

## 📊 Results
Here is a comparison of our output:
| Original Person | Target Cloth | Virtual Try-On Result |
|:---:|:---:|:---:|
| ![Person]()<img width="459" height="389" alt="Person" src="https://github.com/user-attachments/assets/12687edc-5c38-49d6-bfc2-b252f0a5ca42" />
| ![Cloth]<img width="441" height="381" alt="Clothe" src="https://github.com/user-attachments/assets/d1ea3aa3-1357-4994-9489-e7af3a26d7cd" />
| ![Result]<img width="429" height="575" alt="Result" src="https://github.com/user-attachments/assets/450ee9d7-5fe9-4b2b-af7a-0a80a81568b6" />


## 📜 References
* [cite_start]VITON-HD Dataset [cite: 34]
* IDM-VTON Paper & Repository
* [cite_start]VirtualFit Proposal [cite: 2]
