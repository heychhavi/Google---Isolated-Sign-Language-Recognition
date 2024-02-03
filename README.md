# Sign Language Recognition

### Project Overview
This project focuses on recognizing sign language through advanced machine learning models, leveraging landmark data extracted from sign language videos. Our goal is to accurately interpret sign language, thereby enhancing communication accessibility.

### Data Description
We use video data that includes landmarks extracted using the MediaPipe holistic model. Each frame's data contains various attributes such as frame number, landmark type, and spatial coordinates.

(Include more details about the data as previously described.)

### Models Used
In this project, several neural network architectures were implemented and evaluated for their effectiveness in sign language recognition. The models include:

1. LSTM Neural Network: A basic LSTM model to capture temporal dependencies in sequential data.
2. LSTM with Dropout: An LSTM model with dropout layers to prevent overfitting.
3. Convolutional Neural Network (CNN): A standard CNN architecture to capture spatial relationships.
4. CNN with More Layers: An advanced CNN model with additional layers to enhance feature extraction.
5. CNN with Learning Rate Scheduler: A CNN model augmented with a learning rate scheduler to optimize the training process.
6. CNN with Regularization: Incorporating regularization techniques in CNN to improve generalization.
7. Transformer Model: Utilization of the Transformer architecture, known for its effectiveness in handling sequential data.
Each model was carefully crafted and tuned to interpret the complex patterns in sign language data.

<img width="1054" alt="Screenshot 2024-01-05 at 1 05 02 AM" src="https://github.com/heychhavi/Google---Isolated-Sign-Language-Recognition/assets/28872896/d0888c7f-53b8-480f-b65e-afc02bc0a7a7">


