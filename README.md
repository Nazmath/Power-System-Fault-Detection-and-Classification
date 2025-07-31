# Power-System-Fault-Detection-and-Classification

This project aims to develop a Machine Learning model that can automatically detect and classify power system faults based on electrical parameters like voltage, current, and phasor measurements. The goal is to enable rapid fault identification to improve response times and enhance the overall reliability of electrical power systems.

---

## 🚀 Project Overview

The system uses supervised learning techniques to classify fault types such as:
- Line-to-Ground (LG)
- Line-to-Line (LL)
- Double Line-to-Ground (LLG)
- Three-Phase (LLL)
- No Fault

Trained on a public dataset, the model helps automate fault detection and supports faster decision-making in smart grid environments.

---

## 🧠 Algorithms Used

- ✅ Random Forest Classifier
- 🔄 Support Vector Machine (for comparison)
- 🧪 Model selection based on accuracy, precision, recall, and F1-score

---

## 📂 Dataset

- **Source:** Kaggle – *Power System Fault Dataset*
- **Features:** Voltage, Current, and Phasor Measurements
- **Labels:** Fault categories

---

## 🔧 Project Pipeline

1. **Data Preprocessing**
   - Handling missing values
   - Normalization of features
2. **Model Training**
   - Train-test split
   - Hyperparameter tuning
3. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix
4. **Deployment**
   - Model deployed on IBM Watson Studio
   - Real-time predictions via API endpoint

---

## 🌐 Technologies Used

- Python (Scikit-learn, Pandas, NumPy, Matplotlib)
- IBM Watson Studio
- Jupyter Notebook
- Git & GitHub

---

## 🚧 Challenges Faced

- Data imbalance among fault classes
- Noisy measurements required heavy preprocessing
- Balancing model accuracy vs. interpretability

---

## 💡 Future Enhancements

- Integration of environmental data (e.g., weather, lightning)
- Deep Learning models like LSTM for time-series fault prediction
- Edge computing deployment for real-time fault detection
- Multi-city grid scalability

---

## 📚 References

1. Breiman, L. "Random Forests." *Machine Learning*, 2001.
2. Vapnik, V. "The Nature of Statistical Learning Theory." *Springer*, 1995.
3. IEEE Papers on Smart Grid Fault Detection
4. Kaggle Power System Fault Dataset
5. IBM Watson Studio Documentation

---

## 🙌 Contributors

- [Nazmath Pasha](https://github.com/Nazmath)

---

## 📜 License

This project is open source and available under the [No License].

