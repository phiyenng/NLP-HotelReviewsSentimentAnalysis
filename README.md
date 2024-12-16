# NLP-HotelReviewsSentimentAnalysis
Final Natural Language Processing project on Hotel Reviews Sentiment Analysis
---
# Phân tích quan điểm đánh giá chất lượng dịch vụ khách sạn dựa trên nền tảng TripAdvisor  
------------------------  
## What is this project?  
This is a final project for the Natural Language Processing (NLP) course, focusing on sentiment analysis of Vietnamese hotel reviews on TripAdvisor. Our project involves building and comparing machine learning and deep learning models to classify reviews as positive, neutral, or negative.  

------------------------  

## Data Source  
- **Data Origin**: The dataset was sourced from NIAID Data Ecosystem - [TripAdvisor Vietnam Hotel Reviews](https://data.niaid.nih.gov/resources?id=zenodo_7967493) by Zenodo  
- **Files**:  
   - `Reviews.csv`: Raw hotel reviews data.  
   - `TuDon.txt`
   - `vietnamese-stopwords.txt`: Vietnamese Stopwords.
  
---

## Dependencies

Ensure the following libraries are installed before running the program:

### Data Processing Libraries:
```bash
pip install pandas numpy
```

### Text Processing Libraries:
```bash
pip install nltk pyvi scikit-learn
```
- **NLTK**: Make sure to download required NLTK data with the following:
  ```python
  import nltk
  nltk.download('punkt')
  ```

### Machine Learning and Visualization Libraries:
```bash
pip install matplotlib seaborn wordcloud
```

### TensorFlow/Keras for Deep Learning:
```bash
pip install tensorflow
```

------------------------  

## Models Used  
We implemented and compared the following models:  
1. **Machine Learning Models**:  
   - Multinominal Logistic Regression  
   - Multinominal Naive Bayes  
   - Support Vector Machine (SVM)  

2. **Deep Learning Model**:  
   - Feedforward Neural Network (FNN)

------------------------  

### Our Contributors:    
- Đỗ Thị Mỹ Khánh - 31221024404
- Trần Nguyễn Thảo Nguyên - 31221023350
- Nguyễn Hữu Thanh - 31221021356
- Nguyễn Vân Phi Yến - 31221021785

### Course Information:
- Course: Natural Language Processing
- Professor: Ph.D. Đặng Ngọc Hoàng Thành
