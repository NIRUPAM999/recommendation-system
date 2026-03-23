# 🎯 Recommendation System (Task 4)

## 📌 Overview

This project implements a **Recommendation System** using **Collaborative Filtering** techniques.
It suggests items (movies) to users based on the preferences of similar users.

---

## 🚀 Features

* User-Item Matrix creation
* User similarity using Cosine Similarity
* Personalized recommendations
* Simple and efficient implementation
* RMSE evaluation metric

---

## 🧠 Method Used

**Collaborative Filtering (User-Based)**

* Finds users with similar interests
* Recommends items liked by similar users

---

## 📂 Dataset

* MovieLens 100K Dataset
* Contains:

  * 100,000 ratings
  * 943 users
  * 1682 movies

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Google Colab

---

## ⚙️ How It Works

1. Load dataset
2. Create User-Item Matrix
3. Compute similarity between users
4. Identify most similar user
5. Recommend items liked by them

---

## 📊 Output Example

```
Recommended Items for User 3:
Item 50
Item 172
Item 181
Item 174
Item 210
```

---

## 📉 Evaluation

* RMSE (Root Mean Squared Error): ~2.95
* Indicates reasonable prediction accuracy for a basic model

---

## 📁 Project Structure

* `task4.ipynb` → Main notebook
* `README.md` → Project documentation

---

## 🙌 Conclusion

This project demonstrates the fundamentals of recommendation systems and collaborative filtering, forming the base for advanced systems used in platforms like Netflix and Amazon.

---
