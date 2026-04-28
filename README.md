# 📌 Intrusion Detection System using BiGRU + Attention (CIC-IDS-2018)

This project implements a deep learning–based Intrusion Detection System (IDS) using the CIC-IDS-2018 dataset, focusing on detecting malicious network traffic through sequential modeling.

# 🚀 Key Features

🔁 Sequence Modeling with BiGRU
Captures forward and backward temporal dependencies in network traffic.

🎯 Multi-Head Attention Mechanism
Enhances model focus on critical parts of traffic sequences for better classification.

📊 Large-Scale Data Handling
Uses memory mapping (NumPy memmap) to efficiently process millions of samples without memory overflow.

⚙️ Custom Data Pipeline
Sliding window sequence generation
Stratified train-test split
Batch-wise data loading with TensorFlow Sequence

⚡ Performance Optimization
GPU memory growth configuration
XLA JIT compilation
Early stopping & learning rate scheduling

🧠 Multi-Class Classification
Detects various attack types (e.g., DoS, DDoS, brute force, etc.) from real-world traffic data.

# 🛠️ Tech Stack
Python, TensorFlow / Keras
NumPy, Pandas, Scikit-learn
Matplotlib, Seaborn

# 📈 Workflow
Load and merge CIC-IDS-2018 dataset (multiple CSV files)
Preprocess data (scaling, encoding)
Generate sequential windows for time-series modeling
Train BiGRU + Attention model
Evaluate using classification metrics and confusion matrix

🎯 Goal

To build a scalable and efficient IDS capable of learning complex traffic patterns and improving detection accuracy using deep learning.
