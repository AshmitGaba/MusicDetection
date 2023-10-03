# AI/Real Music Detection App 🎵🤖
An innovative full-stack application designed to distinguish between music produced by real artists and AI-generated tunes, ensuring the integrity and authenticity of music in the industry.

# Overview 🌐
This project leverages the power of Convolutional Neural Networks (CNNs), specifically utilizing a fine-tuned ResNet-18 model, to discern subtle distinctions between spectrograms of AI and human-produced music. Developed with a stack of Python, FastAI, PyTorch, HTML, and React.js, it showcases an impressive prediction accuracy of 92% by training on thousands of hours of diverse music data.

# Features 🎉
Music Classification: Accurately identifies whether an MP3 file or a YouTube link contains music produced by AI or a real artist.
Interactive UI: A smooth, user-friendly interface crafted with React.js, allowing users to easily input MP3 files or YouTube links for prediction.
Extensive Training: Trained on a vast dataset primarily comprised of popular artists and accessible AI-generated music, ensuring reliable predictions.

# How it Works 🛠️
Data Conversion: MP3 audio files are converted into spectrogram images.
Model Training: A pretrained ResNet-18 model is fine-tuned with these spectrogram images, learning the discrepancies between AI and real music.
Prediction: New MP3 files or YouTube links are converted into spectrograms, and the model makes a prediction based on its training.

# Technical Stack 📚
Machine Learning: FastAI, PyTorch
Backend: Python
Frontend: HTML, React.js
Data Preprocessing: Various audio and image processing libraries

# Future Plans 🚀
Continual fine-tuning of the model as more AI-generated music becomes available.
Enhancing the user interface and user experience (UI/UX).
Expanding the training data to include a wider array of music genres and production styles.

# Contribute 🤝
Contributions, issues, and feature requests are welcome! Feel free to check issues page.

1. Fork the Project
   
3. Create your Feature Branch (git checkout -b feature/AmazingFeature)
   
5. Commit your Changes (git commit -m 'Add some AmazingFeature')
   
7. Push to the Branch (git push origin feature/AmazingFeature)
   
9. Open a Pull Request

# Authors
This project was created by Ashmit Gaba, Ananth Sriram, Mihir Singh, and Shriyans Sairy.
