
 Fake News Detection Project

This project aims to detect fake news using the ISOT dataset. The primary methodologies used are Exploratory Data Analysis (EDA) with Recurrent Neural Networks (RNN) and a Bi-directional Long Short-Term Memory (Bi-LSTM) model. 

 Project Structure

- EDA RNN: This file focuses on performing exploratory data analysis on the ISOT dataset and applying a Recurrent Neural Network (RNN) to classify the data into fake and real news categories.
  
- ISOT Bi-LSTM: This file implements a Bi-directional Long Short-Term Memory (Bi-LSTM) model for fake news detection. Bi-LSTM is an advanced variation of LSTM that processes data in both forward and backward directions to better capture the context in text.

 Methodologies

 Exploratory Data Analysis (EDA) with RNN
- EDA: The purpose of EDA is to understand the distribution and structure of the dataset. It involves visualizing the data, cleaning the dataset, handling missing values, and analyzing the distribution of real vs. fake news.
- RNN: RNNs are a type of neural network designed to work with sequences of data, like text. They are ideal for processing news articles where the order of words matters. The RNN model used in this project captures the sequence of words in news articles and outputs a classification of fake or real news.

 ISOT Bi-LSTM
- Bi-LSTM: Long Short-Term Memory (LSTM) networks are a type of RNN that can capture long-term dependencies in sequences. Bi-directional LSTMs (Bi-LSTM) improve upon standard LSTMs by processing data in both directions—forward and backward—allowing the model to capture more context in the text. This approach is especially useful for text classification tasks like fake news detection, where understanding the broader context of a sentence or article is crucial.
  
 Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

 Usage
- Run EDA RNN:
   ```bash
   python EDA_RNN.py
   ```

- Run ISOT Bi-LSTM:
   ```bash
   python ISOT_Bi_LSTM.py
   ```

 Dataset
The dataset used for this project is the ISOT Fake News Dataset, which contains news articles labeled as real or fake. The dataset is publicly available and can be downloaded from [ISOT Fake News Dataset](https://onlineacademiccommunity.uvic.ca/isot/2022/11/27/fake-news-detection-datasets/).

 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
