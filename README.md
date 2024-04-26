# DSCI498---Final-Project
<h1>Conditional Generative Adversarial Networks (CGANs) for Hand Gesture Image Generation</h1>
The proposed project aims to develop a Conditional Generative Adversarial Network (CGAN) for synthesizing realistic hand gesture images, specifically focusing on gestures associated with the game "Rock, Paper, Scissors." Leveraging the power of deep learning and conditional information, the model will be trained on a diverse dataset of hand gesture images to generate high-fidelity images aligned with specified class labels. By incorporating class labels into the image generation process, the CGAN will enable precise control over the types of images produced, enhancing the capabilities of gesture recognition systems and supporting interactive applications such as virtual reality environments and interactive games. Through the utilization of TensorFlow and modern deep learning techniques, this project aims to contribute to advancements in computer vision and human-computer interaction domains. Additionally, I plan to utilize Plotly Dash, Streamlit, or Flask to develop an interactive web application for showcasing the generated hand gesture images and facilitating user interaction with the model.

<h2>Dataset Used</h2>:
https://www.kaggle.com/datasets/sanikamal/rock-paper-scissors-dataset/data

<h2>Methodology:</h2>
<b>Data Collection</b>: Gathered a comprehensive dataset of hand gesture images encompassing diverse poses and backgrounds, focusing on the "Rock, Paper, Scissors" gestures.

<b>Data Preprocessing</b>: Preprocessed the collected images by resizing them to a uniform size, applying normalization to standardize pixel values, and ensuring data balance through augmentation techniques.

<b>Model Architecture Design</b>: Designed a CGAN architecture comprising a generator and discriminator network, with the generator being conditioned on class labels for targeted image generation.

<b>Model Training</b>: Trained the CGAN model using the preprocessed dataset, alternating between generator and discriminator training steps to optimize image synthesis and discrimination capabilities.

<b>Performance Evaluation</b>: Evaluated the trained model's performance by assessing the quality and diversity of generated images, comparing them against real hand gesture images, and measuring the model's ability to correctly classify generated images.

<b>User Interface Development</b>: Developed an interactive web application using Plotly Dash to showcase the generated hand gesture images, allowing users to input desired class labels and visualize the corresponding synthetic images in real-time.

<h1>Generator Architecture</h1>
![generator_architecture](https://github.com/shy222/DSCI498-Final-Project/assets/111256553/c700516e-2719-4f0c-af5f-27f70ed5034e)




