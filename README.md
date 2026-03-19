
## Dataset

Dataset used in this project:

https://github.com/timooo-thy/fake-real-news-classifier

#  Fake News Detection Using Neural Network

This project is a Neural Network-based text classification system that detects whether a news headline is **Fake** or **Real**.

---

##  Project Description

Fake news has become a major issue in today's digital world. This project uses a **Feedforward Neural Network** to classify news headlines based on their content.

The model learns patterns from labeled data and predicts whether a given news headline is fake or real.

---

##  Dataset

We used the **Fake and Real News Dataset** which contains:

- Text (news content)
- Labels:
  - 0 → Real News
  - 1 → Fake News

Dataset files:
- Fake.csv
- True.csv

---

##  Technologies Used

- Python
- Pandas
- Scikit-learn
- TensorFlow / Keras

---

##  Project Steps

1. Data Loading and Exploration
2. Text Preprocessing (TF-IDF)
3. Train-Test Split (80/20)
4. Neural Network Model Building
5. Model Training
6. Model Evaluation
7. Testing with new headlines

---

##  Neural Network Architecture

- Input Layer
- Hidden Layer (128 neurons, ReLU)
- Hidden Layer (64 neurons, ReLU)
- Output Layer (1 neuron, Sigmoid)

---

##  Training Details

- Epochs: 10
- Learning Rate: 0.001
- Loss Function: Binary Crossentropy
- Optimizer: Adam

---

##  Results

- Accuracy: ~ (put your result here, e.g., 92%)
- Loss: (put your result)

---

##  Example Predictions

| Headline | Prediction |
|---------|----------|
| Scientists confirm water on Mars | Real |
| Secret government creates invisible humans | Fake |

---

##  How to Run

1. Upload dataset files (Fake.csv, True.csv)
2. Open the notebook in Google Colab
3. Run all cells

---

##  Conclusion

The neural network successfully learned patterns in news text and achieved high accuracy in classifying fake and real news.

---

##  Author

- YISEHAK ALELIGN
