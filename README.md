# Live-face-recognition-using-custom-CNN-for-predicting-age-gender-and-emotion


### Overview
This project implements a live face recognition system capable of detecting emotions, predicting gender, and estimating age simultaneously. It integrates three custom CNN models for real-time performance, demonstrated effectively in a live setup.

### Features
- **Age Prediction**: Achieved a Mean Absolute Error (MAE) of **4.21**.
- **Gender Detection**: Achieved **98% training accuracy** and **75.55% validation accuracy**.
- **Emotion Recognition**: Achieved **75% training accuracy** and **62.5% validation accuracy**.
- **Real-Time Demo**: Integrated and demonstrated all three models in a live face recognition system using VS Code.

### Implementation
1. **Custom CNN Models**:
   - Designed separate CNN architectures for age prediction, gender detection, and emotion recognition.
2. **Integration**:
   - Combined all three models into a unified pipeline for live face recognition.
3. **Real-Time Performance**:
   - Demonstrated using a live camera feed processed in real-time.


### Tools and Technologies
- Python, TensorFlow/Keras
- OpenCV for live video feed
- VS Code for live demonstration
### Steps to run the project
1. Run the Colab notebook and adjust the epochs, learning rate and other hyperparameters according to the computing resources available to you.
2. Load .h5 trained model files of all 3 models and update the path in **integration.py**

