# Instagram Fake Account Detection

This project focuses on detecting fake or spam Instagram accounts using machine learning techniques. By analyzing user metadata (such as followers, following count, profile picture status, and username characteristics), the model classifies accounts as fake or genuine.

##  Problem Statement

Fake accounts are a common issue on social media platforms, used for spam, bots, and fraudulent activity. This project builds a supervised ML model to identify such accounts based on publicly available profile features.

---

##  Dataset

The dataset was collected via an Instagram crawler and manually labeled as fake or genuine.  
Features include:

- profile_pic : Binary (1 if profile picture exists, 0 otherwise)
- nums/length username : Ratio of digits to username length
- fullname words : Number of words in full name
- description length : Bio text length
- #followers, #follows, #posts: Engagement metrics
- private : Binary (1 if account is private)
- fake`: Target label (1 = fake, 0 = genuine)

---

##  Machine Learning Workflow

- **Data Cleaning & Exploration** using pandas, matplotlib, seaborn
- **Feature Engineering**: followers/following ratio, description length, profile attributes
- **Model Training**: Random Forest, Decision Tree
- **Model Evaluation**: Confusion matrix, classification report, accuracy score
- **Test Results**: Achieved over 94% accuracy on unseen test data

---

## 🛠 Tech Stack

- Python: pandas, scikit-learn, matplotlib, seaborn
- Tableau for visualization
- Jupyter Notebook

---

## 📂 Project Structure

├── data/
│   ├── train.csv
│   └── test.csv
├── notebooks/
│   └── instagram_fake_detection.ipynb
├── README.md


---

## 📌 Key Learnings

- Handling tabular data for binary classification
- Real-world feature engineering from social media data
- Model evaluation and bias inspection
- Translating ML insights into dashboards for stakeholders

---

## 🚀 Future Improvements

- Integrate deep learning for profile image/text analysis
- API-based real-time detection system
- Deploy a Streamlit or Flask app

---
