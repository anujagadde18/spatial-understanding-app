# 🎨 Spatial Understanding App Prototype

[![GitHub Repo Size](https://img.shields.io/github/repo-size/anujagadde18/spatial-understanding-app)](https://github.com/anujagadde18/spatial-understanding-app)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/anujagadde18/spatial-understanding-app)](https://github.com/anujagadde18/spatial-understanding-app)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

An **AI-powered interactive museum app prototype** built from the **Spatial Understanding App Template**.  
This project demonstrates real-time object detection, segmentation, and spatial analysis — enabling museum visitors to “Ask the Exhibit” and explore exhibits in an engaging way.

---

## 🚀 Features

- 🔍 **Object Detection**: Identify objects in images (e.g., pumpkins in a harvest display)  
- 🖼 **Spatial Visualization**:  
  - **2D Bounding Boxes**  
  - **Segmentation Masks**  
  - **Key Points**  
- 📝 **Dynamic Modification**: Use a natural language **Code Assistant** to change bounding box color, style, and label text without coding  
- 🌐 **Live Preview**: Immediate feedback on prompts  
- 🛠 **Rapid No-Code Prototyping**: Built from an AI template to focus on user interaction and design  

---

## 🧱 Technology Stack

| Layer                | Tools / Libraries                  |
|---------------------|-----------------------------------|
| **Frontend**        | HTML, CSS, JavaScript             |
| **App Template**    | Spatial Understanding Template     |
| **AI / ML Backend** | Pre-trained Computer Vision Models |
| **Build Tool**      | Vite (`vite.config.ts`)            |
| **Version Control** | Git & GitHub                        |
| **Platform**        | Browser-based, no-code interface  |

---

## 🖼 Sample Interaction

**Prompt:** `pumpkin`  
- **2D Bounding Boxes:** Red rectangles highlight each pumpkin  
- **Segmentation Masks:** Colored overlay across the pumpkin area  
- **Key Points:** Key points on each detected object  

Optional Code Assistant commands:
- Change bounding box to **green**, **dashed**, or **dotted**  
- Modify label text color to **white**  

---

## 💻 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/anujagadde18/spatial-understanding-app.git
cd spatial-understanding-app

# Open the app in your browser
open index.html
