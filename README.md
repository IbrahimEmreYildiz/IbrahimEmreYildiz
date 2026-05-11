# İbrahim Emre Yıldız
## Junior Computer Vision Engineer

**[iemreis803@gmail.com](mailto:iemreis803@gmail.com)** | **[LinkedIn](https://www.linkedin.com/in/ibrahim-emre-yildiz-549ab0256)** | **[GitHub](https://github.com/IbrahimEmreYildiz)**

## About Me

Senior-year Computer Engineering student at Çukurova University (English-Taught) specializing in Computer Vision and Deep Learning. Building end-to-end vision systems with PyTorch, OpenCV, and YOLO — from instance segmentation pipelines to assistive navigation systems. Focused on production-ready, modular solutions for real-world problems.

## Featured Projects

### [Crop Disease Intelligence System](https://github.com/IbrahimEmreYildiz/Plant-Disease-Detector-App)

Instance segmentation pipeline for plant disease detection and severity analysis on field crops. Fine-tuned YOLO26l-seg with class-filtering strategy and geometric mask-based severity scoring.

- **Training:** PlantSeg dataset (Wei et al. 2024) filtered from 118 → 9 high-performing classes
- **Performance:** mAP50 (Box) 0.578, mAP50 (Mask) 0.558 on train-2
- **Optimization:** Frame striding (process every 5th frame, reuse detections) → 5x video inference speedup
- **Stack:** Python, PyTorch, YOLO26l-seg, Ultralytics, OpenCV, Gradio

### Real-Time Assistive Navigation for the Visually Impaired *(Graduation Thesis — In Progress)*

YOLOv8-based real-time object detection and audio feedback system designed for visually impaired navigation. Monocular distance estimation with pinhole camera model and offline TTS.

- **Architecture:** Modular pipeline (config / detector / distance_estimator / audio_feedback / visualizer / main)
- **Detection:** YOLOv8n for real-time inference on consumer hardware
- **Distance:** Pinhole camera model for monocular distance estimation
- **Audio:** pyttsx3 offline TTS — works without internet connection
- **Stack:** Python, Ultralytics YOLOv8, OpenCV, pyttsx3, NumPy

### [AutoDamageDetection](https://github.com/IbrahimEmreYildiz/auto_damage_detection)

End-to-end car damage severity classifier with selective fine-tuning strategy and cost estimation dashboard. Built on ImageNet-pretrained EfficientNet-B1.

- **Dataset:** Kaggle Car Damage Severity (1500 images, 3 classes)
- **Strategy:** Selective fine-tuning — last 3 feature blocks + classifier head trained, rest frozen
- **Performance:** 76% test accuracy vs baseline CNN
- **Deployment:** Streamlit dashboard, SQLite prediction history, Docker → Hugging Face Spaces
- **Stack:** Python, PyTorch, EfficientNet-B1, Streamlit, SQLite, Docker

### [Career Lens](https://github.com/IbrahimEmreYildiz/Career-Lens)

Modular desktop application for job posting collection, analysis, and visualization. Full pipeline from web scraping to dual-database storage to statistical reporting.

- **Pipeline:** Selenium scraping → MongoDB raw storage → SQLite analysis layer → Matplotlib visualization
- **Architecture:** Modular OOP design (models / scraper / analyzer / GUI separated)
- **Interface:** PyQt5 desktop GUI with embedded charts
- **Stack:** Python, PyQt5, Selenium, Pandas, NumPy, SQLite, MongoDB, Matplotlib

## Tech Stack

**Computer Vision & Deep Learning:** PyTorch, Ultralytics (YOLOv8, YOLO26), OpenCV, EfficientNet, CNN, Transfer Learning, Instance Segmentation
**Data & Analysis:** NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
**Backend & Storage:** MS SQL Server, Oracle SQL, SQLite, MongoDB
**Tools & Deployment:** Git, GitHub, Docker, Streamlit, Gradio, Hugging Face Spaces, PyQt5, Jupyter, venv, Linux
**Languages:** Python, SQL, C/C++

## Experience

**Software Development Intern** | Adana Water and Sewerage Administration (ASKİ) *(Aug 2025 – Sep 2025)*

- Integrated new calculation parameter into production Water Module
- Wrote Oracle SQL reporting queries over subscriber, consumption, and billing data

**ERP Support and Hardware Intern** | Rival Yazılım *(Jul 2025 – Aug 2025)*

- Provided remote desktop support to 10+ customers across LOGO Tiger/GO/Start ERP products
- Performed database backup and data extraction on MS SQL Server

**Software Team Member** | TEKNOFEST 2023 — Combat UAV Competition *(2023)*

- Led data labeling, dataset preparation, and data augmentation for image classification model
- Contributed to YOLOv7 + DeepSORT real-time object detection and multi-object tracking pipeline

---

Open to **Junior Computer Vision Engineer** opportunities and research collaborations in Computer Vision, Deep Learning, and applied AI.
