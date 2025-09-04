# 🌍 GVI Mapper

**GVI Mapper** (Geo-Visual Intelligence Mapper) is a Computer Vision–based system that generates **depth maps** and **3D scene reconstructions** from videos.  
It uses the **Depth-Anything-V2 model** to extract RGB frames from landscape videos (≤ 30s), estimate depth, and regenerate the video with depth information.  

---

## 🚀 Features
- Upload a landscape video (max 30 seconds).
- Extracts **RGB frames** from the input video.
- Applies **Depth-Anything-V2** for high-quality depth estimation.
- Reconstructs a **depth video** from predicted depth maps.
- Provides **real-time visualization** of the depth maps.
- Jupyter Notebooks for experimentation and reproducibility.
- Architecture diagram included for better understanding.

---

## 🛠️ Project Structure
- `Final_Year_Project_GVi_Mapper.ipynb` → Main notebook for the pipeline.
- `Depth_Map_with_Depth_Anything.ipynb` → Implementation of depth estimation.
- `Depth-Anything-V2 model Architecture diagram.png` → Architecture overview.
- `GVI-MAPPER.pptx` → Project presentation slides.
- `FYP 2.pdf` & `AI_GVI mapper FYP 3 updated.pdf` → Documentation reports.
- `GVi Mapper.png` → Visual representation/logo.

---

## 📂 Workflow
1. **Upload video** → Landscape video (≤ 30s).
2. **Frame Extraction** → Split into RGB frames.
3. **Depth Estimation** → Use Depth-Anything-V2 to generate depth maps.
4. **Depth Video Reconstruction** → Recombine depth frames into video.
5. **Export** → Depth maps and reconstructed video available for download.

---

## ⚙️ Tech Stack
- **Language**: Python  
- **Frameworks/Libraries**: PyTorch, OpenCV, NumPy, Matplotlib  
- **Model**: Depth-Anything-V2  
- **Frontend**: Python-based web interface (in progress)  
- **Backend**: Google Colab (for model execution & GPU support)  

---

## 📊 Results
- High-quality **depth videos** from real-world landscape videos.
- Accurate **3D structure preservation**.
- Visual comparison between original and depth-mapped videos.

---

## 🖼️ Example Output
| Input Video (RGB) | Generated Depth Video |
|-------------------|------------------------|
| ![RGB Example](GVi%20Mapper.png) | Depth Visualization (see output video) |

---

## 📌 Future Work
- Develop a complete **web-based interface** for uploading and processing.
- Optimize for **real-time depth estimation**.
- Integrate **3D model reconstruction** for AR/VR applications.
- Add multilingual support for wider accessibility.

---

## 👨‍💻 Authors
- Muhammad Umar Riaz (Lead Developer)  
- Team Members – Final Year Project, Air University  

---

## 📜 License
This project is licensed under the **MIT License** – feel free to use and modify with attribution.

