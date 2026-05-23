نبـرة:



A system for analyzing Arabic speech and vocal patterns associated with anxiety indicators using Machine Learning, Deep Learning, Transformer-based models, and Clustering techniques.

⸻

Project Overview

Nabra is a graduation project that aims to analyze Arabic speech signals and detect vocal patterns related to anxiety indicators by studying speech characteristics and voice intensity levels. The project focuses on analyzing vocal and acoustic patterns rather than directly classifying emotions, using audio signal processing, machine learning, and deep learning techniques.

The project relies on cleaning audio recordings, extracting important features from speech signals, training multiple models, and comparing their performance to achieve the best possible results in analyzing Arabic anxiety-related vocal patterns.

⸻

Project Objectives
	•	Analyze vocal patterns associated with anxiety indicators in Arabic speech.
	•	Process and improve the quality of audio recordings before training.
	•	Extract important acoustic features from speech signals.
	•	Compare the performance of different machine learning and deep learning models.
	•	Evaluate the effectiveness of Transformer-based models in Arabic speech analysis.
	•	Study the differences between traditional and deep learning approaches in audio signal analysis.

⸻

Dataset

This project uses the Basic Arabic Vocal Emotions Dataset (BAVED), which is a publicly available dataset on Kaggle designed for Arabic speech and vocal emotion analysis research.

Dataset Link:
https://www.kaggle.com/datasets/a13x10/basic-arabic-vocal-emotions-dataset

The dataset contains approximately 1935 Arabic speech recordings collected from multiple speakers with different vocal styles and intensity levels. The recordings are categorized into several voice intensity levels, including:
	•	Low
	•	Neutral
	•	High

The dataset also includes various acoustic characteristics such as pitch, speech energy, tone, and temporal speech features, making it suitable for audio signal analysis and deep learning applications.

⸻

Preprocessing

Several preprocessing techniques were applied to improve the quality of the audio signals before model training, including:
	•	Resampling
	•	Noise Removal
	•	Silence Removal
	•	Audio Signal Normalization
	•	Audio Length Standardization
	•	Data Augmentation

These steps helped improve audio quality and reduce irrelevant variations between recordings.

⸻

Feature Extraction

Several techniques were used to extract acoustic and spectral features from the audio recordings, including:
	•	Log-Mel Spectrogram
	•	MFCCs
	•	Pitch
	•	Speech Energy
	•	Temporal Features

These features represent the core information used for training the models and analyzing different vocal patterns.

⸻

Implemented Models

Several models were implemented and compared throughout the project, including:

Machine Learning Models
	•	SVM
	•	K-Means Clustering

Deep Learning Models
	•	CNN
	•	LSTM
	•	BiLSTM
	•	CNN-LSTM Hybrid

Transformer-Based Models
	•	Wav2Vec2
	•	HuBERT

The performance of these models was compared to determine the most effective approach for analyzing anxiety-related vocal patterns.

⸻

Evaluation Metrics

The models were evaluated using several performance metrics, including:
	•	Accuracy
	•	Precision
	•	Recall
	•	F1-score
	•	Validation Loss
	•	Confusion Matrix

These metrics helped measure and compare the performance of the implemented models accurately.

⸻

Notebooks

The project code is divided into two main notebooks inside the notebooks folder. Each notebook contains different experiments and implementations used throughout the project.

1. GP2(BAVED_DeepLearning_Models)

This notebook includes the implementation and experimentation of multiple machine learning and deep learning models using the BAVED dataset, including:
	•	Audio preprocessing
	•	Audio signal cleaning
	•	Feature extraction
	•	Data augmentation
	•	Training CNN, LSTM, BiLSTM, and CNN-LSTM models
	•	Applying the SVM model
	•	Model evaluation
	•	Result analysis using Confusion Matrix and evaluation metrics

⸻

2. GP2(Wav2Vec2_HuBERT)

This notebook contains the implementation and training of Transformer-based speech models, including:
	•	Fine-tuning the Wav2Vec2 model
	•	Fine-tuning the HuBERT model
  • Applying K-Means Clustering
	•	Audio preprocessing for Transformer models
	•	Deep speech representation extraction
	•	Training the models on Arabic speech data
	• Evaluating and comparing model performance
  

⸻

Requirements File

A requirements.txt file was created to include all libraries and dependencies used in the project.

The file contains the requirements for the two main notebooks:
	•	GP2(BAVED_DeepLearning_Models)
	•	GP2(Wav2Vec2_HuBERT)

It includes all required libraries for running the project, such as:
	•	TensorFlow
	•	PyTorch
	•	Transformers
	•	Librosa
	•	NumPy
	•	Pandas
	•	Scikit-learn
	•	TorchAudio
	•	Matplotlib

All dependencies were organized and saved inside the requirements.txt file to simplify project execution and experiment reproducibility.

⸻

Project Execution

To run the project, the dataset should first be downloaded from Kaggle and placed inside the dataset folder. After that, the notebooks can be opened using Google Colab or Jupyter Notebook and executed sequentially to perform all project stages, starting from preprocessing and feature extraction to model training and evaluation.

⸻

Results

Several experiments were conducted to compare the performance of machine learning, deep learning, and Transformer-based models in analyzing Arabic anxiety-related vocal patterns.

The results showed that Transformer-based models such as Wav2Vec2 and HuBERT achieved the best overall performance compared to traditional machine learning and deep learning models, due to their strong ability to understand speech representations and extract more accurate and complex features from Arabic audio signals.

Deep learning models such as CNN and LSTM also achieved good results in vocal pattern analysis; however, Transformer-based models demonstrated higher efficiency and accuracy across most evaluation experiments.

Preprocessing and data augmentation techniques also contributed to improving training quality, reducing the impact of noise and irrelevant variations between recordings, and enhancing the final model performance.

The results were analyzed using several evaluation metrics and visualization methods such as the Confusion Matrix to compare the strengths and weaknesses of the different models.

⸻

Project Team

Graduation Project – Umm Al-Qura University
College of Computing
Data Science Department
Academic Year 2025 / 2026
