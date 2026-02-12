# ShilpSutra - AI Based Handicraft Authentication System

## Project Overview

ShilpSutra is an AI-powered web application designed to identify whether a handicraft product is **real (authentic)** or **fake (mass-produced imitation)** using deep learning.

The system uses a trained ResNet18 model to analyze uploaded images and classify them into:
- Real Handicrafts
- Fake Handicrafts

This solution aims to support artisans, buyers, and cultural preservation efforts by promoting authenticity in handicraft markets.

---

## Tech Stack

### Backend
- FastAPI
- PyTorch
- Torchvision
- Uvicorn
- CNN

### Frontend
- HTML
- CSS
- JavaScript

### Model
- ResNet18 (Custom trained)
- 2-class image classification
- Model size: ~42MB

---

## Setup Instructions

### 1️. Clone the Repository

```
git clone https://github.com/mahipandey18/ShilpSutra.git
cd ShilpSutra/ShilpSutra_backend
```
### 2. Install Dependencies

```
pip install -r requirements.txt
```
### 3. Run Backend Server

```
uvicorn app:app --reload
```
### 4. Run Frontend
