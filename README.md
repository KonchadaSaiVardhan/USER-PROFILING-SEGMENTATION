# USER-PROFILING-SEGMENTATION
# 🧠 User Profiling and Segmentation using Machine Learning

This project uses clustering techniques to segment users based on their demographics, online behavior, ad interactions, and interests using a dataset of 1000 users.

## 📊 Features Used:
- Demographics: Age, Gender, Location, Education, Income
- Online Behavior: Likes, Follows, Device Usage
- Engagement: Time spent online (Weekday/Weekend), CTR, Conversion Rate, Ad Time
- Interests: Multi-label field with user interests

## 🔧 Technologies & Libraries:
- Python
- pandas, matplotlib, sklearn (StandardScaler, KMeans, PCA)
- Google Colab

## 📌 Steps Performed:
1. Data preprocessing (encoding categorical and multi-label fields)
2. Feature scaling
3. Clustering using KMeans (n=5)
4. Dimensionality reduction using PCA
5. Visualization of clusters
6. Exported segmented dataset to CSV

## 📁 Output:
- `segmented_user_profiles.csv`: Contains all user data + segment label + PCA components for visualization

## 📷 Visualization:
![Cluster Plot](https://your_screenshot_link_if_any)

## 📥 Running Locally:
```python
!pip install pandas scikit-learn matplotlib
# Then run the provided Python code
