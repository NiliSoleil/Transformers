# Transformers
**ECG signal classification with Transformers**

This repository contains a deep learning project that implements and trains **a Transformer network** for the classification of Electrocardiogram (ECG) signals. This class project uses the 5000ECG dataset, which includes five different classes of heart activity, from normal signals to various anomalies.

**Project Objectives**

The main goals of this project were to:

  **Dataset Preparation:** 📊 To load and prepare the 5000ECG dataset for use with a Transformer model.
  
  **Model Implementation:** 🧠 To build a custom Transformer network and implement positional encoding for time series data.
  
  **Architectural Experimentation:** ⚙️ To experiment with different architectural components, such as adding convolutional layers, to see their effect on model performance.
  
**Key Project Steps**

The project was completed in the following stages:

**1. Dataset Preparation**

  📚 The dataset was loaded from the dataset folder. It is pre-split into a training set (500 samples) and a test set (4500 samples).
  
  📏 The data size, the number of samples per class, and the labels were checked. The key dimensions L (sequence length) and F (number of features) were identified.
  
  📈 A sample data point was plotted to visualize the ECG signal.
  
  📦 A DataLoader was used for creating mini-batches.

**2. Transformer Model Definition**
  
  **Transformer Network:** 🧠 A Transformer network with a custom number of layers was built.
  
  **Positional Encoding:** 📐 Since the input feature size is 1, a change was implemented to increase it. A provided Positional Encoding class was integrated into the model architecture.
  
  **CNN Integration (Optional):** 💡 The option to add one or more convolutional and pooling layers at the beginning of the network (before the Transformer) was explored to see if it improved the results.

**Key Focus:** The main goal of this project was not to achieve extremely high accuracy, but to learn how to code and implement different models for this type of data. 

**How to Run the Code**

  **Prerequisites:** 🛠️ Make sure you have the necessary libraries, such as PyTorch, installed.
  
  **Run the Notebook:** 🖥️ The code is available here: 
  
  You can run it in Google Colab or any Jupyter environment.

Niloufar Soleil
