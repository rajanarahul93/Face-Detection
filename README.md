# Face Detection Project using face-api.js

This project implements real-time face detection and emotion recognition using `face-api.js` in a browser environment. The application uses the webcam to detect faces, display landmarks, and recognize facial expressions such as happiness, sadness, and neutrality.

## Features
- **Real-Time Face Detection**: Detects human faces in real-time through a webcam feed.
- **Facial Landmark Detection**: Identifies specific points on the face, such as eyes, nose, and mouth.
- **Emotion Detection**: Recognizes emotions like happiness, sadness, surprise, and more.
- **Responsive Layout**: The canvas showing detection results adjusts to the video feed size.

## Technologies Used
- **HTML5**: For structuring the web page.
- **JavaScript**: For implementing face detection and emotion recognition logic.
- **face-api.js**: A powerful machine learning library for face recognition, facial landmarks, and emotion detection.


## How to Run the Project

1. **Download/Clone the Repository**:
   ```
   git clone https://github.com/rajanarahul93 /Face-Detection.git
   cd Face-Detection-project
   ```

2. **Download the Pretrained Models**:
   - Download the necessary models for face detection and emotion recognition from the [official face-api.js GitHub](https://github.com/justadudewhohacks/face-api.js) repository.
   - Place the models inside the `models` directory.

3. **Open `index.html` in a Browser**:
   - Open the `index.html` file directly in a browser (Google Chrome is recommended).
   - Grant permission to access the webcam when prompted.

4. **View Face and Emotion Detection**:
   - The webcam feed will display real-time face detection with facial landmarks and emotion recognition.


## Usage

- **Start Detection**: The face detection will automatically start once the page is loaded and webcam access is granted.
- **Emotion Recognition**: The emotions will be displayed for each detected face, with confidence scores indicating the accuracy of the emotion prediction.

## Dependencies

- face-api.js (included in the project as `face-api.min.js`)
- A web browser with support for WebRTC (for accessing the webcam).

## Future Enhancements

- Add support for face recognition (identifying specific individuals).
- Implement an option to take snapshots of the video feed with detected faces.
- Enhance emotion detection accuracy with more advanced models.
