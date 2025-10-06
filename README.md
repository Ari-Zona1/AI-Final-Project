# AI-Final-Project
Course: CS 440 — Introduction to Artificial Intelligence, Rutgers University
Technologies: Python, NumPy, PyTorch, Neural Networks, Perceptron, Image Processing

Overview
This project implements and compares multiple machine learning algorithms — a Perceptron classifier and two versions of a three-layer Neural Network — to classify handwritten digits (0–9) and detect faces from edge-detected images. It provides hands-on experience with neural network design, backpropagation, feature extraction, and experimental analysis.

Objectives
- Build two classifiers from scratch:
- Perceptron model for linear classification
- Custom three-layer Neural Network implementing forward propagation, backpropagation, and weight updates
- Develop a PyTorch-based neural network to validate results and compare performance against manual implementation
Train and evaluate models on:
- A dataset of scanned handwritten digits
- A dataset of pre-processed facial edge images
- Measure model performance using:
- Training time vs. number of samples (10–100% of training data)
- Prediction error rate and standard deviation across random sampling trials

Key Features
- From-Scratch Implementation: Core neural and perceptron algorithms coded without using any ML frameworks (except PyTorch for part C).
- Learning Curves: Automated experiments across incremental training sizes to visualize convergence and overfitting behavior.
- Performance Evaluation: Statistical analysis of accuracy and runtime scalability.
- Data Handling: Custom image parsing logic for text-based datasets; binary pixel encoding for model features.
- Experimental Rigor: Controlled random sampling and cross-validation to ensure fair comparison.

Results
- Achieved high classification accuracy (≥70%) using simple pixel-based features.
- Observed significant improvement in both models as training data increased — validating data-driven learning trends.
- Found that the neural network outperformed the perceptron in both accuracy and consistency, particularly for non-linear patterns in face detection.
- Verified that PyTorch implementation produced similar results with faster convergence and more efficient training.

Skills Demonstrated
- Neural Network architecture design and optimization
- Gradient descent and backpropagation implementation
- Performance benchmarking and visualization
- Data preprocessing and feature engineering
- Experimental reproducibility and statistical validation

Applications - 
This project demonstrates strong fundamentals in:
- Computer Vision and Image Classification
- Neural Network Design and Optimization
- Statistical Evaluation of Machine Learning Models
