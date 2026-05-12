# AI-Yoga-Mentor
#TAKE DATASET ON YOUR OWN, for Sample 2-3 images are provided , but the dataset of 82 classes of yoga poses are needed to be downloaded
An application that helps you with your dialy yoga poses , helping in detection and correction of the poses .
AI Yoga Mentor 🧘‍♀️🤖

An AI-powered Yoga Pose Detection and Posture Correction System that helps users practice yoga with real-time feedback and posture improvement suggestions using Computer Vision and Machine Learning.

📌 Project Overview

AI Yoga Mentor is an intelligent fitness assistant that analyzes yoga poses through:

🎥 Live Webcam Feed
🖼 Uploaded Images
🎬 Uploaded Videos
▶️ YouTube Video URLs

The system detects body landmarks, identifies yoga poses, evaluates posture accuracy, and provides personalized suggestions to improve alignment and form.

This project acts as a virtual yoga trainer that helps users perform yoga safely and correctly from anywhere.

🚀 Features
✅ Real-Time Pose Detection

Detects yoga poses instantly using live webcam input.

✅ Image Pose Analysis

Upload images to analyze posture and pose accuracy.

✅ Video Pose Detection

Analyze pre-recorded yoga videos frame-by-frame.

✅ YouTube URL Support

Paste a YouTube yoga video URL and let the system analyze poses automatically.

✅ AI-Based Posture Correction

Provides suggestions such as:

Straighten your back
Raise your arms higher
Maintain body alignment
Bend your knee correctly
✅ Modern GUI

Beautiful and responsive interface built using CustomTkinter.

✅ Multi-Threaded Processing

Smooth webcam and video processing without freezing the GUI.

🧠 Technologies Used
Technology	Purpose
Python	Core Programming Language
OpenCV	Video & Image Processing
MediaPipe / Pose Detection	Body Landmark Detection
CustomTkinter	Modern GUI Design
Pillow (PIL)	Image Handling
Threading	Background Processing
NumPy	Mathematical Operations
📂 Project Structure
AI-Yoga-Mentor/
│
├── main.py                 # Main application file
├── detector.py             # Pose detection logic
├── poses.py                # Yoga pose definitions & matching
├── assets/                 # Icons, images, UI assets
├── videos/                 # Sample yoga videos
├── requirements.txt        # Required libraries
└── README.md               # Project documentation
⚙️ How the System Works
Input Source
(Webcam / Image / Video / YouTube)
            ↓
Frame Extraction using OpenCV
            ↓
Body Landmark Detection
            ↓
Angle Calculation
            ↓
Yoga Pose Recognition
            ↓
Posture Accuracy Evaluation
            ↓
Improvement Suggestions
            ↓
Display Results on GUI
🖥️ Installation
Step 1: Clone the Repository
git clone https://github.com/diyarathor3112/AI-Yoga-Mentor.git
cd AI-Yoga-Mentor
Step 2: Install Dependencies
pip install -r requirements.txt
Step 3: Run the Application
python gui.py
📦 Required Libraries
pip install customtkinter
pip install opencv-python
pip install pillow
pip install mediapipe
pip install numpy
📸 Supported Input Modes
Mode	Description
Webcam	Real-time yoga monitoring
Image Upload	Analyze single yoga posture
Video Upload	Detect poses from recorded videos
YouTube URL	Analyze online yoga videos
🧘 Supported Yoga Poses

Some example poses include:

Mountain Pose
Tree Pose
Warrior Pose
Cobra Pose
Downward Dog
Chair Pose

(Can be extended further.)

🎯 Objectives
Make yoga training accessible remotely
Improve posture accuracy using AI
Reduce risk of incorrect yoga practice
Provide a virtual fitness assistant experience
Combine Computer Vision with Healthcare & Fitness
🔍 Future Enhancements
Voice-based guidance
Rep counting
Personalized workout plans
Progress tracking dashboard
Mobile application integration
Advanced AI pose classification
Calories burned estimation
📊 Applications
Home fitness training
Online yoga coaching
Smart healthcare systems
Fitness monitoring
Rehabilitation assistance
👨‍💻 Team / Contributors
Diya Rathor
Team Members (if applicable)
📜 License

This project is developed for educational and research purposes.

💡 Conclusion

AI Yoga Mentor combines Artificial Intelligence, Computer Vision, and Fitness Technology to create an interactive and intelligent yoga training system. By providing real-time posture analysis and correction suggestions, the system enhances the yoga learning experience and promotes healthy exercise habits.

⭐ If you like this project

Give it a ⭐ on GitHub and support the project!
