🧠 Computer Vision Projects

A collection of beginner-to-intermediate Computer Vision projects implemented in Python, OpenCV, and Deep Learning.
Each project includes Google Colab notebooks, Python scripts, and outputs for visualization and experimentation.

📚 Projects Included
🟩 1. 3D Projection Viewer

Tech: Python, OpenCV, Matplotlib, NumPy

Description:
Implements orthographic and perspective projection of 3D points onto a 2D plane.
Visualizes a rotating cube using mathematical projection matrices.

Key Features:

Orthographic vs. Perspective visualization

Uses cv2.projectPoints() for perspective math

Outputs comparison image

📘 Google Colab:
Open 3D Projection Viewer in Colab

🧩 Preview:

<p align="center"><img src="3D_Projection_Viewer/3d_projection_output.png" width="450"></p>
🟦 2. Face Recognition using FaceNet & DeepFace

Tech: facenet-pytorch, DeepFace, PyTorch, OpenCV, Matplotlib

Description:
Detects faces using MTCNN, generates embeddings using InceptionResnetV1 (FaceNet),
and analyzes age, gender, and emotion using DeepFace.

Key Features:

Face detection (MTCNN)

Face embeddings (FaceNet)

Demographic analysis (age, gender, emotion)

CPU/GPU friendly versions

Works in Google Colab

📘 Google Colab:
Open Face Recognition Project in Colab

🧩 Preview:

<p align="center"><img src="Face_Recognition_FaceNet/output_example.png" width="450"></p>
🚀 Setup and Usage
🖥️ Clone the Repo
git clone https://github.com/<your-username>/Computer-Vision-Projects.git
cd Computer-Vision-Projects

🧩 Run in Google Colab

Each folder contains a .ipynb file ready for Colab execution with all dependencies pre-installed.

🧰 Requirements

Python 3.8+

NumPy

OpenCV

Matplotlib

facenet-pytorch

DeepFace

torch / torchvision

You can install all using:

pip install -r requirements.txt


(You can generate requirements.txt using pip freeze > requirements.txt)

🧑‍💻 Author

Aman Verma
B.Tech CSE | SRM Institute of Science and Technology
📧 amanverma@email.com

🌐 LinkedIn

📜 License

This project is licensed under the MIT License — you are free to use, modify, and distribute.

🌟 Acknowledgements

Facenet-PyTorch (Timesler)

DeepFace

OpenCV

Matplotlib

💡 Future Additions

Real-time webcam-based face recognition

Emotion heatmaps

3D object rendering improvements
