# Face Verification with DeepFace and OpenCV 🎥

This project is a real-time face verification system that uses **DeepFace** for facial recognition and **OpenCV** for video capture. The program compares live video frames from the webcam with a reference image to check for a face match. The result is displayed on the video feed in real-time.

---

## Features
1. **Real-time Face Verification**:
   - Captures video frames from the webcam.
   - Compares the captured face with a reference image using DeepFace.
2. **Threaded Face Matching**:
   - Uses multithreading to process face matching without affecting the real-time video feed.
3. **Visual Feedback**:
   - Displays "MATCH!" in green if a face matches the reference image.
   - Displays "NO MATCH!" in red if a face does not match.
