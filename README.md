🎭 Real-time Face Swapping using Dlib & DeepFaceLive
🚀 Introduction

This project demonstrates real-time face swapping using DeepFaceLive and Dlib.
Imagine being on a video call and instantly swapping your face with your favorite celebrity —
that’s exactly what this project enables.

For example: Swap your face with Angelina Jolie live on a webcam and amaze your friends 🎬.

✨ Features

🔄 Real-time face swapping on live video streams.

🤖 Powered by DeepFaceLive and Dlib for accurate detection.

⚡ GPU acceleration with CUDA for smooth performance.

🎥 Works on webcam or video files.

🔧 Easy to run with a simple command.

🛠️ Tech Stack

Python 3.9+

DeepFaceLive

Dlib

ONNX Runtime (GPU)

PyTorch (CUDA)

OpenCV

📦 Installation
1. Clone this repository
git clone https://github.com/Zinalr44/Real-time-Face-Swapping-using-Dlib-DeepFaceLive.git
cd Real-time-Face-Swapping-using-Dlib-DeepFaceLive

2. Create & activate environment
conda create -n deepfacelive_env python=3.9
conda activate deepfacelive_env

3. Install dependencies
pip install -r requirements.txt

4. Install CUDA-supported PyTorch (if you have NVIDIA GPU)
pip install torch torchvision torchaudio --index-url https://download.pytorch.org

▶️ Usage
Run the application
python main.py run

Train (if modifying models)
python main.py train

🎬 Demo

Example:
Swap your face with Angelina Jolie in real time:

📂 Project Structure
DeepFaceLive/
│── apps/              # Application logic
│── build/             # Build scripts
│── doc/               # Documentation
│── localization/      # Multi-language support
│── modelhub/          # Pretrained models
│── resources/         # Static resources
│── scripts/           # Helper scripts
│── userdata/          # User data & configs
│── main.py            # Entry point
│── requirements.txt   # Dependencies
│── README.md          # Project documentation
│── LICENSE            # License file

⚡ Performance

Runs real-time on NVIDIA RTX 3050 Ti Laptop GPU.

Uses CUDA 12.1 + cuDNN 9.8.

Achieves smooth FPS for live webcam swapping.

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.

👨‍💻 Author

Zinal Raval

💼 AI Developer | Backend Engineer | Automation Expert

