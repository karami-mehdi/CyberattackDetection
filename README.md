# 🌐 Cyberattack Detection and Anomalous Behavior Analysis Using Recurrent Neural Networks (RNN)

Cybersecurity is a critical domain as network attacks increasingly threaten systems worldwide. Detecting cyberattacks and analyzing anomalous behaviors in network traffic is essential for securing digital environments. This project leverages **Recurrent Neural Network (RNN)**, technically **Long Short-Term Memory (LSTM)**, to identify abnormal patterns in network traffic that signal potential cyberattacks, such as DDoS, port scanning, and brute-force attacks.

## Dataset
The project utilizes the **[CIC-IDS2017 Dataset](https://www.unb.ca/cic/datasets/ids-2017.html)**, developed by the [Canadian Institute for Cybersecurity](https://www.unb.ca). It is widely used for intrusion detection system evaluation and contains real-world attack simulations, including:

- **DDoS attacks**
- **Brute force attacks**
- **SQL injection**
- **Port scanning**
- **Botnet activities**

The dataset is suitable for RNN-based methods due to its sequential nature, allowing temporal dependencies in network traffic to be analyzed effectively.

For easier access, we used the [Network Intrusion Dataset on Kaggle](https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset).

## How to Run

1. To run this project, clone the repository and navigate to the project directory:
```bash
git clone https://github.com/nsswifter/CyberattackDetection.git
cd CyberattackDetection
```

2. Ensure you have `Python 3.11.1+` and the required libraries installed. Use the command below to install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:
```bash
jupyter notebook cyberattack_detection.ipynb
```

4. Execute the notebook cells sequentially to preprocess data, train the model, and evaluate results.

## Results
The RNN model effectively detects cyberattacks with competitive accuracy, leveraging temporal patterns in the data. Detailed evaluation metrics and visualizations are included in the notebook.

## License
This project is licensed under the [MIT License](LICENSE).
