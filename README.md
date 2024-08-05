![Tensorflow](https://img.shields.io/badge/-Tensorflow-ff6f00?style=flat&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/-Keras-d00000?style=flat&logo=keras&logoColor=white) ![sklearn](https://img.shields.io/badge/-sklearn-F89C3F?style=flat&logo=scikit%20learn&logoColor=white&labelColor=3294C7)

# Text Generation Projects

Welcome to the Text_Generation repository! This repository contains four interrelated projects: **Text_Generation.ipynb**, **Text_Reformulation.ipynb**, **Text_Reduction.ipynb**, and **Translate.ipynb**. Each project explores different aspects of text manipulation and generation, highlighting how small changes in methodology can significantly impact the results.

## Projects Overview

### 1. Text_Generation.ipynb
This project focuses on generating text using N-Gram models within an LSTM (Long Short-Term Memory) neural network architecture. The LSTM model predicts the next word in a sequence based on the previous \( n-1 \) words, capturing local context and generating coherent, contextually appropriate text.

> [!NOTE]  
> Unfortunately, I was unable to upload the models to the repository because I haven't been able to download them from Kaggle due to a technical issue.

### 2. Text_Reformulation.ipynb
Text_Reformulation is closely related to Text_Generation, using the same LSTM neural network architecture and dataset. The primary difference lies in the use of a Continuous Bag of Words (CBOW) model instead of an N-Gram model. While N-Gram models focus on consecutive word sequences, CBOW models predict a target word based on its context words, capturing broader context. Despite the almost identical code, this small adjustment significantly impacts the reformulated text by providing a different contextual understanding.

### Key Similarities and Difference: N-Gram vs. CBOW
- **Neural Network Architecture**: Both projects use LSTM neural networks (RNN).
- **Dataset**: Both projects utilize the same dataset.
- **Code**: The code is almost identical, with minor adjustments for the different modeling techniques.
- **N-Gram Model**: Considers contiguous sequences of words.
- **CBOW Model**: Predicts a target word based on surrounding context words.

### 3. Text_Reduction.ipynb
This project can summarize any article on the web. It takes two parameters from the user: the link to the article and the percentage of reduction. The model calculates the importance of each sentence in the article, allowing it to generate a concise summary that retains the core meaning.

### 4. Translate.ipynb
Currently under development, this project functions more like a dictionary of English than a full translator. It aims to translate text while maintaining semantic integrity and fluency.

## Detailed Insights

### Impact of Small Changes
- **N-Gram vs. CBOW**: Changing from N-Gram to CBOW alters context capture, leading to significant differences in generated or reformulated text. N-Gram models focus on immediate word sequences, making them good for local context. CBOW models, by considering broader contexts, generate more varied and contextually rich text.
  
- **Summarization Techniques**: Different summarization techniques (extractive vs. abstractive) can drastically change the output. Extractive summarization picks sentences directly from the text, while abstractive summarization generates new sentences, leading to more coherent and concise summaries.

## Getting Started

To explore these projects, simply clone the repository and open the respective Jupyter notebooks. Each notebook contains detailed instructions and explanations for running the code and understanding the results.

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/Text_Generation.git
```

### 2. Install the required dependencies: 
```bash
pip install -r requirements.txt
```

### 3. Install Jupyter Notebook:
```bash
pip install notebook
```

### 4. Dataset: 
```bash
https://www.kaggle.com/datasets/thedrcat/daigt-proper-train-dataset
```

## Contributing
Feel free to fork this repository, make changes, and submit pull requests. All contributions are welcome!