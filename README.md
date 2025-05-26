

#  Emoji Prediction using Natural Language Processing

This project focuses on predicting the most appropriate emoji based on the sentiment and context of a given input sentence. The aim is to simulate how humans associate emotions (emojis) with textual expressions. This model enhances interactive applications like social media assistants, chatbots, and smart input systems.

---

## 📌 Project Objectives

* To predict the correct emoji from a sentence input.
* To preprocess and prepare textual data for deep learning models.
* To implement a transformer-based model (DistilBERT) for classification.
* To fine-tune and evaluate performance on a custom emoji dataset.
* To provide a user-friendly interface for interactive prediction.

---

## 📚 Dataset

* **Source**: [Kaggle - Twitter Emoji Prediction](https://www.kaggle.com/datasets/hariharasudhanas/twitter-emoji-prediction)
* **Format**: CSV file containing `text` and `label` columns.
* The dataset includes sentences or tweets and the corresponding emoji labels.

---

## 🔍 Technologies & Libraries Used

* **Python**
* **Google Colab** for model development
* **Transformers** (`DistilBERT`) from Hugging Face
* **Scikit-learn**
* **Pandas**, **NumPy**
* **Matplotlib** (for optional visualizations)
* **Torch**

---

## ⚙️ Model Architecture

* **Model Used**: `DistilBERTForSequenceClassification`
* **Tokenizer**: `DistilBertTokenizerFast`
* Fine-tuned on the emoji prediction dataset.
* Input: Tokenized text
* Output: Predicted emoji label

---

## 📂 Files in This Repository

| File Name                                  | Description                                        |
| ------------------------------------------ | -------------------------------------------------- |
| `emoji_prediction_cleaned.ipynb`           | Final cleaned version of the Google Colab notebook |
| `Emoji_Prediction_Abstract.pdf`            | Abstract summarizing the objective and approach    |
| `Detail_View_of_Algorithm_and_Dataset.pdf` | Detailed explanation of methodology and dataset    |
| `output.jpg`                               | Sample prediction output screenshot                |
| `README.md`                                | Project overview and instructions                  |

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/emoji-prediction-nlp.git
   cd emoji-prediction-nlp
   ```

2. Open the notebook in **Google Colab** or **Jupyter**.

3. Upload the dataset or mount Google Drive if necessary.

4. Run all cells to:

   * Preprocess data
   * Train/fine-tune model
   * Predict emoji for new inputs

5. To test interactively, enter a sentence when prompted:

   ```
   Enter a sentence (or type 'exit' to quit): I am so Happy today!
   Predicted Emoji: 😊
   ```

---

## 🖼️ Sample Output

> **User Input**: `"I am so Happy today!"`
> **Predicted Emoji**: 😊

📸 See `output.jpg` for the actual terminal display.

---

## ✅ Features

* Transformer-based architecture for contextual understanding
* Emoji prediction from real-world user inputs
* Clean and simple output interface
* Easily extendable to more emojis or languages

---

## 📌 Future Enhancements

* Support multi-label emoji prediction (more than one emoji per sentence)
* Integrate emoji suggestions into messaging interfaces
* Improve generalization with larger and more diverse datasets
* Add support for regional or language-specific emojis

---

##  Author

**Harshith Manikhanta**
B.Tech AI & ML Student
VIT-AP University

---

