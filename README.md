# Tamil-sign-language-to-Text-and-Voice-converter
An AI-powered Tamil Sign Language Recognition System that converts hand gestures into readable Tamil text and voice output using computer vision and deep learning. Designed to bridge communication gaps and make everyday interactions more accessible for the hearing and speech-impaired community.

# 🤟 Tamil Sign Language to Text and Voice Converter

### Bridging Communication Through Artificial Intelligence

## 📌 About the Project

The **Tamil Sign Language to Text and Voice Converter** is an AI and Machine Learning-based project designed to make communication easier between people who use sign language and those who may not understand it.

The system recognizes Tamil sign language hand gestures using computer vision and deep learning techniques and converts the recognized gestures into corresponding Tamil text and voice output.

The primary objective is to reduce communication barriers and create a more inclusive environment for the hearing and speech-impaired community.

By combining computer vision, image processing, and machine learning, this project explores how artificial intelligence can be used to develop accessible communication solutions.

## 🎯 Objectives

- Recognize Tamil sign language hand gestures using computer vision.
- Convert recognized gestures into corresponding Tamil characters.
- Generate readable Tamil text from hand gestures.
- Provide voice output to make communication easier.
- Explore and compare different deep learning architectures for gesture recognition.
- Develop an accessible and user-friendly communication solution.

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| OpenCV | Image processing and camera integration |
| MediaPipe | Hand landmark detection and tracking |
| Teachable Machine | Initial gesture recognition experimentation |
| TensorFlow / Keras | Deep learning model development |
| VGG16 | Gesture classification experimentation |
| VGG19 | Gesture classification experimentation |
| ResNet50 | Deep learning model experimentation |
| EfficientNet | Efficient image classification experimentation |
| MLP | Gesture classification using extracted features |

## 🧠 Model Development

Different machine learning and deep learning architectures were explored to identify an effective approach for Tamil sign language recognition.

### Models Experimented With

1. **VGG16:** A convolutional neural network used for image feature extraction and classification.
2. **VGG19:** A deeper CNN architecture explored for gesture recognition.
3. **ResNet50:** A residual neural network investigated for learning complex visual features.
4. **EfficientNet:** Explored for efficient feature extraction and image classification.
5. **MLP (Multi-Layer Perceptron):** Used for classification based on extracted gesture features.

### Initial Development

The initial prototype used Teachable Machine, MediaPipe and OpenCV to detect and recognize hand gestures.

Further experimentation involved training and evaluating multiple deep learning architectures to improve recognition performance.

The MLP-based approach achieved promising results in Tamil character recognition during experimentation.

## 🔄 How It Works

The system follows a gesture-to-communication pipeline:

1. **Video Capture:** Captures hand gestures through a webcam.
2. **Hand Detection:** MediaPipe identifies and tracks hand landmarks.
3. **Image Processing:** OpenCV processes the captured frames.
4. **Gesture Recognition:** The trained machine learning model classifies the detected gesture.
5. **Text Conversion:** The recognized gesture is mapped to its corresponding Tamil character.
6. **Voice Generation:** The recognized Tamil text is converted into speech output.

## 🏗️ System Architecture

```text
       User Performs Hand Gesture
                  |
                  v
           Webcam Capture
                  |
                  v
          OpenCV Processing
                  |
                  v
       MediaPipe Hand Detection
                  |
                  v
         Feature Extraction
                  |
                  v
        Trained ML/DL Model
                  |
                  v
         Gesture Recognition
                  |
                  v
       Tamil Character Mapping
                  |
             +----+----+
             |         |
             v         v
         Tamil Text  Voice Output
             |         |
             v         v
         Display    Audio Output
```

## ✨ Key Features

- Real-time hand gesture recognition (prototype capability).
- Tamil character recognition.
- Gesture-to-text conversion.
- Text-to-voice conversion.
- Computer vision-based hand tracking.
- Experimentation with multiple deep learning architectures.
- Accessibility-focused application of AI and ML.

## 🌍 Real-World Applications

- Communication assistance for hearing and speech-impaired individuals.
- Educational tools for learning Tamil sign language.
- Accessible communication systems in public places.
- Assistive technology for hospitals and institutions.
- Development of inclusive human-computer interaction systems.

## 🚀 Future Enhancements

- Expand recognition from individual Tamil characters to complete words and sentences.
- Build a larger and more diverse Tamil sign language dataset.
- Improve recognition accuracy under different lighting conditions and hand orientations.
- Implement continuous gesture recognition.
- Add support for multiple sign languages.
- Develop a mobile application.
- Integrate the system with real-time communication platforms.
- Improve voice generation with natural Tamil speech output.

## 💡 Project Impact

This project demonstrates how AI and computer vision can be applied to address real-world accessibility challenges.

Rather than focusing only on technological advancement, the project aims to use artificial intelligence to create meaningful social impact by making communication more inclusive.

## 👩‍💻 Contributors

Developed as an AI & ML project by students of Computer Science and Engineering.

**Domain:** Artificial Intelligence and Machine Learning

**Focus Areas:** Computer Vision | Deep Learning | Image Processing | Assistive Technology

## ⭐ Acknowledgement

We acknowledge the open-source communities and resources that supported the development and experimentation of this project, particularly Python, OpenCV, MediaPipe, TensorFlow and related machine learning technologies.

