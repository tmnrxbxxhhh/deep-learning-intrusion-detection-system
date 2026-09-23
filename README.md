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

## Methodology

The project follows a deep learning-based intrusion detection workflow using the CICIDS2017 dataset.

The main stages of the project are:

1. **Data Preparation**

   * Load the CICIDS2017 network traffic data.
   * Clean and preprocess the input features.
   * Handle labels and transform them into the required format.

2. **Data Preprocessing**

   * Encode categorical labels.
   * Normalize the input features.
   * Split the data into training and evaluation sets.

3. **Model Training**

   * Train four deep learning approaches independently:

     * CNN
     * DNN
     * RNN
     * Transformer + AutoEncoder

4. **Model Evaluation**

   * Evaluate the trained models using classification metrics.
   * Generate performance curves during execution.
   * Analyze the behavior and performance of each approach.

5. **Comparative Analysis**

   * Use `CourbeComparatif.ipynb` to compare the results obtained from the four approaches.

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

Each deep learning approach includes its own training and evaluation process in the corresponding notebook.

The notebooks generate performance curves during model training and evaluation, allowing the behavior and performance of each approach to be analyzed.

The project includes a dedicated comparison notebook:

`CourbeComparatif.ipynb`

This notebook brings together the results of the four approaches:

* CNN
* DNN
* RNN
* Transformer + AutoEncoder

The comparison is based on the experimental results obtained from the individual approaches and provides a comparative view of their performance for network intrusion detection.

Detailed results and visualizations can be found in the corresponding notebooks.
The performance curves are generated directly during notebook execution in Google Colab. They are displayed as part of the notebook outputs and are not stored as separate image files in the repository.

## Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Google Colab
* Google Drive
* CICIDS2017 Dataset

## How to Run

The notebooks are designed to be executed using **Google Colab**.

### 1. Kaggle Account

A Kaggle account is required to obtain the CICIDS2017 dataset.

Each user should use their own Kaggle account and their own API credentials.

### 2. Kaggle API Configuration

Before running the notebooks, configure the Kaggle API in Google Colab using your own `kaggle.json` credentials.

> **Security note:** Do not share your Kaggle API key or commit `kaggle.json` to this repository.

### 3. Dataset

Download the required CICIDS2017 dataset using the Kaggle API and place the CSV files in the dataset directory expected by the notebook.

### 4. Run the Notebooks

Open the required notebook from the `notebooks/` directory in Google Colab and execute the cells sequentially.

Each notebook contains the training and evaluation process for its corresponding deep learning approach, including performance curves generated during execution.

The comparison notebook is used to compare the results of the four approaches.
