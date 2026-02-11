# AI-Fitness-Coach-using-Pose-Estimation
AI Fitness Coach using Pose Estimation
This project presents an AI-powered gym trainer system that generates a skeletal representation of the human body to assist in postural analysis using advanced human pose estimation techniques.We integrated both Opencv and Mediapipe,that makes it easy to learn and adapt faster.
Building an AI Fitness Coach using OpenCV and MediaPipe is a popular and effective application of Computer Vision.
By leveraging MediaPipe's BlazePose model, the system can track 33 body landmarks in real-time to analyze form, count repetitions, and provide corrective feedback
OpenCV (The "Eyes" & "Artist"):
OpenCV handles the "heavy lifting" of video processing:
Frame Handling: Reading the video stream and writing the output.
Visual Feedback: Drawing circles on joints and connecting them with lines to visualize the "skeleton."
UI Elements: Rendering the rep counter, progress bars, and "Correct/Incorrect Form" text on the screen.
MediaPipe:
It offers a straightforward, well-documented API with pre-built solutions (BlazePose) that work immediately with only a few lines of code. It handles webcam input and rendering with minimal configuration.
It has 33 landmarks numbered from 0 to 32 representing different parts of human hody
