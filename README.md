# 🛡️ Real-Time Machine Learning System for Network Anomaly Detection

A hybrid **C++** and **Python** system that uses **real-time packet inspection** and **machine learning** to detect network anomalies across distributed nodes. Combines raw socket programming with asynchronous ML inference for high-performance network intrusion detection.

## 🚀 Features

- **Raw Packet Capture in Linux**: Built with C++ using raw sockets for efficient TCP/IP packet inspection.
- **ML Pipeline**: Autoencoders and Decision Trees used for anomaly detection with 95% accuracy.
- **Asynchronous Inference Queues**: Python multiprocessing handles concurrent inference across distributed systems.
- **Real-time Detection**: System optimized for sub-second response latency.
- **Distributed Execution**: Deployable across multiple nodes with independent data ingestion.

## 📦 Architecture Overview

- **Packet Sniffer (C++)**: Captures TCP/IP traffic using raw sockets.
- **Preprocessor (Python)**: Extracts and normalizes features from packets.
- **ML Engine (Python)**: Trained on historical traffic to detect anomalies.
- **Async Queue System**: Decouples capture and inference for performance.

## 🛠️ Tech Stack

- C++, Python  
- Raw Socket Programming (Linux)  
- Scikit-learn, Keras (Autoencoder)  
- TCP/IP Networking  
- Multiprocessing, Queues


