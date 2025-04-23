# Crowd Density Estimation using Video Analytics (IoT Project)

This project implements a real-time **crowd density estimation system** using video analytics and deep learning. The system detects people in images or video frames using **YOLOv5** and classifies the scene as **Low, Medium, or High Density** based on the number of people detected.

---

## 🚀 Features
- Custom-trained YOLOv5 model using annotated crowd images
- Works with both **images** and **videos**
- Classifies crowd density:
  - Low (0–10 people)
  - Medium (11–25 people)
  - High (26+ people)
- Generates assignment-required graphs:
  - 📈 Time vs People Count
  - 📊 Density Category Distribution

---

## 📂 Folder Structure
crowd-density-estimation-iot/ │ ├── train.ipynb # Model training code ├── inference.ipynb # Inference + density + graphs ├── data.yaml # YOLO dataset config ├── README.md # Project description and instructions └── 📎 Graphs & Results # Screenshots or plotted output

yaml
Copy
Edit


---

## 📊 Graph Examples
- **Time vs People Count**  
- **Density Category Distribution**

<p align="center"><img src="graphs/time_vs_people.png" width="400"/></p>
<p align="center"><img src="graphs/density_distribution.png" width="400"/></p>

---

## 🔗 Important Links
- 📁 [Google Drive: Dataset + Annotations + Model](https://drive.google.com/your-public-folder-link)
- 💻 [YOLOv5 GitHub](https://github.com/ultralytics/yolov5)

---

## 👨‍💻 Built With
- Python
- YOLOv5
- OpenCV
- Google Colab
- Matplotlib
