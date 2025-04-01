# 🖼️ Text Behind Image WebApp

> An AI-powered web application that allows users to put text *behind* objects in an image automatically using AI segmentation.

---

## ✨ Features

- Upload any image
- Automatically detect foreground objects using AI (SAM or U2-Net)
- Place text *behind* objects like people, trees, buildings, etc.
- Manual brush tool for fine-tuning masks
- Download the final composited image
- Smooth text blending & adjustment (opacity, shadow, depth)
- Built with **ReactJS + TypeScript + NestJS + FastAPI (AI Service)**

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | ReactJS + TypeScript + Canvas (react-konva / fabric.js) |
| Backend | NestJS (REST APIs, file handling) |
| AI Service | Python + FastAPI + Segment Anything Model (SAM) |
| Image Processing | OpenCV + Pillow |
| Deployment | Docker / Docker Compose |

---

## 📂 Monorepo Structure

