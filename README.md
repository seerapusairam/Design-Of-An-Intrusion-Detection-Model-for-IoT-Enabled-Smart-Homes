# Intrusion Detection Model for IoT-Enabled Smart Homes  

## Project Overview  
This project focuses on developing an **Intrusion Detection System (IDS)** using **Machine Learning (ML) and Deep Learning (DL)** techniques to identify malicious network traffic in IoT-enabled smart homes. Since IoT devices often lack traditional security solutions, this IDS aims to enhance security by analyzing network packets and detecting potential threats.  

## Features  
- **Dataset**: Kaggle IoT Wireshark dataset for training and evaluation.  
- **Feature Selection**: Uses **Maximal Information Coefficient (MIC)** for selecting the most relevant features.  
- **Dimensionality Reduction**: Implements **Principal Component Analysis (PCA)** to reduce dataset complexity.  
- **Machine Learning Models**: Random Forest, SVM.  
- **Deep Learning Models**: LSTM, CNN-2D (best performer).  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score.  

## 📁 Folder Structure

```
📦IoT-IDS-ML-DL
 ┣ 📁Dataset
 ┣ 📁model
 ┣ 📄main.py
 ┣ 📄predict.py
 ┣ 📄README.md
 ┗ 📄requirements.txt
```

## 🔧 Installation & Setup  
1. **Clone the repository**  
   ```sh
   git clone https://github.com/seerapusairam/Intrusion-Detection-Model-for-IoT-Enabled-Smart-Homes.git
   cd Intrusion-Detection-Model-for-IoT-Enabled-Smart-Homes

2. **Create and activate the conda environment**
   ```bash
   conda create -n py37env python=3.7
   conda activate py37env
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt

4. **Launch the Jupyter Notebook**
   ```bash
   jupyter notebook IOTIntrusionDetection.ipynb
   ```
5. **Run the Notebook**

- Load and preprocess the dataset
- Train each model
- Evaluate performance
- Visualize results
- Perform prediction on new test data

> All operations are done within the notebook. No separate scripts are needed.

## 📦 Models

Trained models are automatically saved under the `/model` directory:

- `cnn_weights.hdf5`
- `lstm_weights.hdf5`

If these files exist, they will be loaded instead of retraining.

## 🤝 Contributors

- **Sai Rohit Kumar Yedla - Y00867742**  
- **Naga Sai Shivani Datla - Y00860597** 
- **Sairam Seerapu - Y00872154** 
- Faculty Guide: **Robert A. Gilliland, PhD**

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.