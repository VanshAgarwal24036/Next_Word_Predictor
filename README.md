# 🧠 Next Word Predictor using LSTM

A Deep Learning based **Next Word Prediction** system built using **TensorFlow/Keras**. The model is trained on a custom text corpus and predicts the most probable next word given an input sequence.

---

## 📌 Features

- Text preprocessing and tokenization
- Sequence generation for language modeling
- Padding of variable-length sequences
- LSTM-based Neural Network
- Next-word prediction
- Hyperparameter tuning using Keras Tuner
- Early stopping to prevent overfitting

---

## 🛠 Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Keras Tuner

---

## 📂 Project Structure

```
Next-Word-Predictor/
│
├── Next_Word_predictor.ipynb      # Training and prediction notebook
├── my_sentences.txt               # Training dataset
├── requirements.txt               # Required libraries
├── README.md
└── LICENSE (optional)
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Next-Word-Predictor.git
cd Next-Word-Predictor
```

### Create Virtual Environment (Recommended)

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📖 Dataset

The model is trained on a text file named

```
my_sentences.txt
```

Each line should contain meaningful English text.

Example:

```
Machine learning is transforming the world.
Deep learning models require quality data.
Natural language processing is fascinating.
```

---

## 🚀 Training

Open the notebook

```
Next_Word_predictor.ipynb
```

Run all cells sequentially.

The notebook performs:

- Loading dataset
- Tokenization
- Sequence generation
- Padding
- Model creation
- Training
- Hyperparameter tuning
- Prediction

---

## 🏗 Model Architecture

```
Embedding Layer
        ↓
LSTM Layer
        ↓
Dense Layer (Softmax)
```

Loss Function

```
Categorical Crossentropy
```

Optimizer

```
Adam
```

---

## 🔍 Example Prediction

Input

```
I would like
```

Output

```
I would like to
I would like to thank
I would like to thank you
...
```

---

## 📈 Hyperparameter Tuning

The project uses **Keras Tuner** to search for the best model configuration.

Tunable parameters include:

- Number of LSTM units
- Dense layer size
- Learning rate
- Other configurable parameters

---

## 📚 Future Improvements

- GRU implementation
- Bidirectional LSTM
- Transformer-based language model
- Streamlit Web App
- Beam Search decoding
- Model checkpointing
- Export trained model for deployment


---

## 👨‍💻 Author

**Vansh Agarwal**

If you found this project useful, consider giving it a ⭐ on GitHub.
