# Gesture Recognition for Smart TV Control
## Project Overview

This project presents a deep learning-based gesture recognition system designed to enable intuitive, touch-free interaction with smart televisions. The system detects and classifies hand gestures in real time, allowing users to control TV functions without relying on traditional remote controls.

The solution leverages computer vision and deep learning techniques to improve user experience and modernize smart TV interaction paradigms.

## Business Context

  * Traditional TV interaction methods—primarily remote controls—face several usability challenges such as:

  * Misplacement or damage

  * Battery dependency

  * Limited accessibility

  * While alternatives like voice control and touchscreens exist, they are often unreliable (due to noise or accents) or impractical (for wall-mounted TVs).

  * This project addresses these limitations by introducing gesture-based control, enhancing both usability and product innovation.

## Objectives

The primary goal of this project is to design and implement a robust deep learning framework capable of recognizing hand gestures from video input in real time.

## Supported Gestures
### Gesture	Action
👍 Thumbs Up	Increase volume
👎 Thumbs Down	Decrease volume
👈 Left Swipe	Rewind 10 seconds
👉 Right Swipe	Forward 10 seconds
✋ Stop	Pause playback

## Research Question

How can a robust and efficient algorithm be developed to accurately detect and classify multiple hand gestures from real-time video streams?

## Dataset Description

  * Source: Kaggle dataset

  * Structure:

    * train/ and val/ directories

    * Each contains:

      * CSV files for metadata

      * Subfolders for each gesture class

  * Each gesture sample:

    * A video represented as 30 sequential frames

## Methodology
### Models Implemented

  1. CNN (Convolutional Neural Network)

  * Processes spatial features from individual frames

  * Simpler architecture with strong baseline performance

  2. CNN + RNN (Hybrid Model)

  * CNN extracts spatial features

  * RNN captures temporal dependencies across frames

  * Designed for sequence-based video classification
