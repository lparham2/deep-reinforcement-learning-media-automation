# Deep RL Media Automation

## Project Description
This project explores how deep learning and reinforcement learning can automate media content creation and optimize interactive system behaviors. Built for **MSA 8600: Deep Learning and Generative AI** at **Georgia State University**, part of the **Master of Science in Data Science & Analytics** program, under **Professor Yanqing Wang**.

## Project Overview
We developed a complete AI-driven pipeline integrating:
- **Image Generation**: Using a Variational Autoencoder (VAE) trained on a subset of 5,000 MS COCO images.
- **Object Detection**: Applying a pre-trained Faster R-CNN with ResNet-50 FPN backbone for recognizing objects in generated images.
- **Image Captioning**: Utilizing a BLIP (Bootstrapped Language Image Pretraining) vision-language transformer model to generate descriptive captions.
- **Reinforcement Learning Design**: Designing a DQN-based RL strategy for an arcade-style game "Box Stack" to optimize gameplay behaviors through reward-driven learning.

## Technologies Used
- **Deep Learning Frameworks**: TensorFlow (VAE), PyTorch (Object Detection, Captioning)
- **Models**: VAE, Faster R-CNN, BLIP Transformer
- **Dataset**: MS COCO (5,000 images sampled)
- **Visualization**: Matplotlib for results visualization

## Key Components
- **VAE**: Generates reconstructed images from latent representations.
- **Faster R-CNN**: Detects and labels objects with bounding boxes.
- **BLIP**: Generates natural language captions for images.
- **Reinforcement Learning**: Designs a reward-based strategy using DQN to optimize decision-making in dynamic environments.

## Results
- Successfully reconstructed visual features from the COCO dataset.
- Detected multiple object categories in generated images.
- Generated coherent captions that matched visual content.
- Developed a full reinforcement learning strategy design to optimize interactive behaviors.

## Deployment
- This project was developed for academic purposes and has no live deployment. It focuses on the theoretical design and experimental outcomes.

## Authors
- Lilly Parham
- Khang Do
- Dorothy "Gracie" Rehberg

## Acknowledgments
- **Georgia State University** — Master of Science in Data Science & Analytics
- **Professor Yanqing Wang** — Instructor for MSA 8600

---

*Note: This project was completed as part of MSA 8600: Deep Learning and Generative AI, Spring 2025 semester.*
