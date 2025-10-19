🚗 Autonomous Vehicle Navigation System Using Deep Learning and Computer Vision
🧠 Overview

This project presents an Autonomous Vehicle Navigation System that leverages Deep Learning and Computer Vision to enable real-time object detection and navigation for self-driving vehicles. Using advanced models like YOLO and Faster R-CNN, the system detects vehicles, pedestrians, traffic signs, and other objects in a video feed — enabling intelligent navigation decisions.

The system demonstrates how AI-powered perception can contribute to the development of low-cost, vision-based autonomous vehicles without the need for expensive LiDAR sensors.

⚙️ Key Features

🚘 Real-time Object Detection using YOLOv4

🧩 Comparison of Models: YOLO vs Faster R-CNN

🧭 Autonomous Navigation Modules: Sensor input, motion planning, and control system integration

📊 Performance Metrics: Evaluates mean Average Precision (mAP) and Frames Per Second (FPS)

🌦️ Adaptability: Handles multiple road and environmental conditions

🔍 Real-world Dataset: Trained on the Berkeley Deep Drive (BDD100K) dataset

🧰 Tech Stack

Languages & Frameworks:

Python 3.12

TensorFlow & Keras

OpenCV

NumPy, Pandas, Matplotlib, Scikit-learn

YOLOv4, Faster R-CNN

Tools & Platforms:

Google Colab

Jupyter Notebook

NVIDIA GPU for training

🧠 Methodology

Data Preprocessing: Prepared and annotated traffic data from the BDD100K dataset.

Model Training:

Trained YOLOv4 for high-speed real-time detection.

Trained Faster R-CNN for higher precision on complex scenes.

System Integration: Combined detection, navigation, and decision-making modules.

Evaluation: Compared both models on metrics such as mAP and FPS.

📈 Results
Model	mAP	FPS
YOLOv4	18.6	212
Faster R-CNN	41.8	17.1
Hybrid Incremental Net	45.7	N/A

YOLO: Real-time performance, lower accuracy.

Faster R-CNN: Higher accuracy, lower speed.

🔬 Experimental Insights

YOLO achieved faster detections, suitable for real-time use.

Faster R-CNN provided better precision for object classification.

Integration of both approaches demonstrated the trade-off between speed and accuracy in autonomous systems.

🚀 Future Enhancements

Integration of LiDAR and radar for better depth estimation.

Enhancement for low-light and adverse weather conditions.

Development of multi-sensor fusion models for greater autonomy.

Deployment on embedded systems (like Jetson Nano or Raspberry Pi).

📚 References

Redmon et al., “You Only Look Once (YOLO)” (2015)

Ren et al., “Faster R-CNN: Towards Real-Time Object Detection”

Berkeley Deep Drive (BDD100K) Dataset

🏁 Conclusion

This project successfully demonstrates the potential of deep learning–based computer vision systems in achieving autonomous vehicle perception and decision-making. By combining real-time speed (YOLO) and high precision (Faster R-CNN), it lays the groundwork for future research in safe and efficient self-driving technologies.