
# 📧 Email Spam Detection Using Machine Learning

A machine learning-based system for detecting and filtering spam emails using various algorithms including SVM, Random Forest, CNN, KNN, Naive Bayes, MLP, and more. The project evaluates the performance of these models using the SpamBase dataset, providing precision, recall, and accuracy metrics along with visualization.

---

## 🧠 Objective

To build a reliable, intelligent spam email filtering system that leverages multiple machine learning classifiers and compares their effectiveness. This review-based implementation provides insight into performance differences and future improvements.

---

## 🚀 Features

* Preprocessing and handling of the SpamBase dataset
* Evaluation of **8 ML algorithms** for spam detection:

  * KNN, Naive Bayes, MLP
  * SVM, Decision Tree, AdaBoost
  * Random Forest, CNN
* Accuracy, Precision, Recall evaluation
* Comparative performance visualization
* GUI-based execution using Python’s `Tkinter`

---

## ⚙️ Technologies Used

| Category      | Tech Stack                                                               |
| ------------- | ------------------------------------------------------------------------ |
| Programming   | Python 3.7                                                               |
| ML Libraries  | scikit-learn, keras, numpy, pandas                                       |
| Visualization | matplotlib                                                               |
| GUI           | Tkinter                                                                  |
| Dataset       | [UCI SpamBase Dataset](https://archive.ics.uci.edu/ml/datasets/spambase) |

---

## 📂 Project Structure

```
📁 Spam-Filtering-ML
├── SpamFilter.py              # Main GUI and logic script
├── spambase.data              # Dataset file
├── requirements.txt           # Python dependencies (to be created)
└── README.md                  # Project documentation
```

---

## 📊 Algorithms Compared

| Algorithm                          | Accuracy | Precision | Recall |
| ---------------------------------- | -------- | --------- | ------ |
| K-Nearest Neighbor (KNN)           | ✅        | ✅         | ✅      |
| Naive Bayes                        | ✅        | ✅         | ✅      |
| Multilayer Perceptron (MLP)        | ✅✅       | ✅✅        | ✅✅     |
| Support Vector Machine (SVM)       | ✅        | ✅         | ✅      |
| Decision Tree                      | ✅        | ✅         | ✅      |
| AdaBoost                           | ✅        | ✅         | ✅      |
| Random Forest                      | ✅        | ✅         | ✅      |
| Convolutional Neural Network (CNN) | ✅✅       | ✅✅        | ✅✅     |

🟢 **MLP and CNN showed highest overall performance across metrics.**

---

## 🖥️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/spam-email-filter.git
   cd spam-email-filter
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**

   ```bash
   python SpamFilter.py
   ```

---

## 📈 Usage

* **Upload Dataset**: Load the `spambase.data` file
* **Preprocess**: Splits into 80% training and 20% testing data
* **Run Algorithms**: Execute and evaluate all included ML models
* **View Graphs**: Compare Accuracy, Recall, and Precision

---

## 📌 System Requirements

* **OS**: Windows 7/8/10 or Linux/Mac with GUI support
* **Python Version**: 3.7+
* **Memory**: Min 256 MB RAM
* **Disk**: Min 20 GB free space

---

## 📊 UML & Design Diagrams

* Use Case Diagram
* Sequence Diagram
* Activity Diagram
* Class & Component Diagrams
* Deployment Diagram

(All available in the project documentation)

---

## 🧪 Testing

* Unit and Integration Testing
* Accuracy, Recall, Precision test metrics
* Acceptance tested using test case scenarios
* Graph-based evaluation confirms model efficiency

---

## 📚 Future Work

* Enhance model with Adversarial Deep Learning
* Deploy model to web/cloud for real-time email filtering
* Expand dataset coverage (image spam, embedded content)
* Use ensemble stacking for improved accuracy

---

## 🔏 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🙌 Acknowledgements

* UCI Machine Learning Repository
* scikit-learn and keras communities
* Research by Awad, Foqaha, Bahgat, Sanz, and others on ML-based spam filtering


