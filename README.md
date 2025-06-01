# PCOS Detection Using Machine Learning
This project aims to detect Polycystic Ovary Syndrome (PCOS) in patients using machine learning classification algorithms implemented in Python. The analysis is based on a dataset collected from multiple hospitals in Kerala, India, containing clinical and diagnostic information of 541 patients across 42 features.

## 🔍 Project Overview
Polycystic Ovary Syndrome (PCOS) is a common hormonal disorder affecting women. Accurate and early diagnosis can help manage symptoms and prevent complications. This project leverages various machine learning algorithms to classify and predict PCOS status based on medical data.

## 🛠️ Technologies & Tools
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

## 📊 Dataset
- Source: Collected from 10 different hospitals in Kerala, India
- Size: 541 records, 42 attributes
- Preprocessing: Missing values were handled, irrelevant features were removed, and significant features were selected for better accuracy.

## 🧪 Machine Learning Models
The following supervised learning classification models were applied:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree (CART)
- Random Forest (RF)
  
### Model Comparison
| Model       | Accuracy |
|-------------|----------|
| RF          |⭐Highest |
| SVM         | Moderate |
| CART        | Moderate |
| KNN         | Moderate |

## 📈 Results
Random Forest performed the best among all tested models, achieving the highest accuracy in predicting PCOS presence. Feature importance analysis revealed that follicle count, skin darkening, weight gain, and menstrual cycle frequency were among the most significant indicators.

## 📌 Conclusion
Machine learning, especially classification techniques, can play a crucial role in assisting medical professionals with disease diagnosis. This project demonstrates a practical approach to identifying PCOS using real-world medical data.

## 👩‍💻 Author
**Gökçe USTA**  
