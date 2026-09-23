# Deep Learning Intrusion Detection System

A deep learning-based Intrusion Detection System (IDS) developed as part of a Master's thesis project.

The project investigates and compares four deep learning approaches for network intrusion detection using the CICIDS2017 dataset:

* CNN
* DNN
* RNN
* Transformer + AutoEncoder

Each approach is implemented and evaluated in a separate Jupyter Notebook.

## Dataset

The models were developed and evaluated using the **CICIDS2017** dataset, a network traffic dataset designed for intrusion detection research.

The dataset contains network traffic representing both benign activity and different types of attacks.

> The CICIDS2017 dataset is not included in this repository due to its size.

## Deep Learning Approaches

The IDS was developed using four deep learning approaches:

### 1. CNN

A Convolutional Neural Network (CNN) approach for learning patterns from network traffic features.

### 2. DNN

A Deep Neural Network (DNN) approach for classifying network traffic.

### 3. RNN

A Recurrent Neural Network (RNN) approach for learning sequential patterns in network traffic.

### 4. Transformer + AutoEncoder

A combined Transformer and AutoEncoder architecture designed to learn meaningful representations of network traffic for intrusion detection.

Each approach is implemented in a separate notebook located in the `notebooks/` directory.

## Project Structure

```text
deep-learning-intrusion-detection-system/
│
├── notebooks/
│   ├── CNN.ipynb
│   ├── DNN.ipynb
│   ├── RNN.ipynb
│   ├── Transformer_AutoEncoder.ipynb
│   └── CourbeComparatif.ipynb
│
└── README.md
```

## Results and Evaluation

Each deep learning approach includes a training and evaluation process in its corresponding notebook.

The notebooks contain visualizations of the model performance, including training and evaluation curves generated during execution.

A separate comparison notebook is provided to analyze and compare the results obtained from the four approaches:

* CNN
* DNN
* RNN
* Transformer + AutoEncoder

The comparison is based on the experimental results obtained during the project and is discussed in the context of network intrusion detection using the CICIDS2017 dataset.

The individual notebooks contain the implementation and training process of each deep learning approach, including the resulting training and evaluation curves.

The comparison notebook is dedicated to comparing the performance of the four approaches.

## Technologies Used

* Python
* Google Colab
* Deep Learning
* Intrusion Detection Systems (IDS)
* CICIDS2017 Dataset
