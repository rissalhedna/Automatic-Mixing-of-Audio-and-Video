# Automatic Mixing of Audio and Video

## 📖 Introduction

Video-formatted content has become increasingly vital for communication due to its ability to convey ideas in an entertaining manner. With advancements in streaming technology and sharing techniques, video recording and sharing have become faster and more convenient. The availability of user-friendly video and audio recording tools, such as smartphone cameras, has contributed to the widespread use of video content. Additionally, AI-driven video editing tools have automated the editing process, making it more accessible to users. However, existing tools often overlook the importance of short-form videos that combine short clips and music, which have gained popularity on social media platforms. This project proposes a system that explores the relationship between audio and video in short-form videos and suggests automated edits based on the chosen music.

## 🎯 Objectives

The main objective of this project is to develop a system that enhances the process of editing short-form videos by considering the influence of music. Specifically, we aim to:

1. **Analyze the relationship between audio and video in short-form videos:** Investigate how music affects the emotional impact and focus of short-form videos, recognizing the importance of audio-visual synchronization.
2. **Develop an automated video editing system:** Leverage AI techniques, such as deep learning models like LSTM and GRU, to automatically analyze the beat and rhythm of a chosen song and synchronize it with video clips, suggesting optimal cuts and edits.
3. **Improve user experience and accessibility:** Make video editing more user-friendly by automating the process, enabling a broader range of users to create compelling short-form videos without extensive manual intervention.
4. **Explore the potential for broader applications:** Extend the system's underlying principles to other video formats, offering a versatile solution for content creators in various domains.

By achieving these objectives, we seek to contribute to the field of AI video editing and provide content creators with a more efficient and intuitive tool for enhancing their short-form video content.

## 🗒️ Repository Contents

This repository contains two Jupyter notebooks that demonstrate the functionality and implementation of the automated audio-video mixing system:

1. **`Beat_Detector.ipynb`**: Handles the pre-processing logic of videos and their associated audios from scratch.
2. **`NN_Model.ipynb`**: Implements and trains the deep learning models (LSTM and GRU) used for analyzing and synchronizing audio beats with video clips.

## 📄 Publication

For a comprehensive understanding of the system and its capabilities, please refer to our published paper:

**Automatic Mixing of Audio and Video**  
Rissal Hedna  
[https://ieeexplore.ieee.org/document/10337600](https://ieeexplore.ieee.org/document/10337600)

## 🚀 Getting Started

### Prerequisites

- **Operating System:** Windows, macOS, or Linux
- **Python Version:** 3.7 or higher

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/rissalhedna/Automatic-Mixing-of-Audio-and-Video
   cd Automatic-Mixing-of-Audio-and-Video
