# Amazon-Product-Recommendation-System using Advanced NLP and ML Techniques

## Authors
- Weiting Li
- Yumin Wang
- Jiayi Zhang

## Project Overview
This project aims to recommend Amazon products to users based on the Amazon product co-purchasing network. The goal is to design and develop a recommender system that is both accurate and efficient. The project involves conducting network analysis, sentiment analysis on product reviews, and implementing topic modeling to understand user preferences better. Finally, a machine learning-based recommendation system is developed to enhance product recommendations.

### Problem Statement
The problem this project addresses is the challenge of designing and developing a product recommendation system that is both accurate and efficient. By analyzing Amazon's co-purchasing network and user reviews, the project seeks to improve the accuracy of product recommendations, thereby enhancing the user experience and increasing sales on e-commerce platforms.

## Course Information
This project is part of the Social Media Analytics CS 5664 course at Virginia Tech for master-level students.

## Contents

### Code Folder
1. **Network Analysis and Topic Modeling.ipynb**: Jupyter notebook for network analysis and topic modeling.
2. **Music_Sentiment_Analysis.ipynb**: Jupyter notebook for sentiment analysis of music product reviews.
3. **Video_Sentiment_Analysis.ipynb**: Jupyter notebook for sentiment analysis of video product reviews.
4. **Recommender_System_ML_Music.ipynb**: Jupyter notebook for the machine learning-based recommendation system for music products.
5. **Recommender_System_ML_Video.ipynb**: Jupyter notebook for the machine learning-based recommendation system for video products.

### Dataset Folder
1. **amazon-meta.txt**: Metadata for Amazon products.
2. **nodeList.csv**: CSV file containing nodes for network analysis.
3. **edgeList.csv**: CSV file containing edges for network analysis.
4. **Movies_and_TV.json**: JSON file with reviews of movies and TV products.
5. **Digital_Music.json**: JSON file with reviews of digital music products.

### Supplementary Material Folder
1. **Network_Topic_Analysis**: Contains pictures for network analysis and topic modeling.
2. **Sentiment_Analysis**: Contains pictures for sentiment analysis.
3. **Demo**: Interactive visualizations for topic modeling.
   - [Demo Video](https://www.youtube.com/watch?v=8ae4x3PKybM)

### Final Report
- **FinalReport-Jiayi-Zhang.pdf**: Detailed report on the project's methodology, experiments, and results.

## Methodology

### Data Collection
- Amazon product co-purchasing network metadata was collected from the SNAP website.
- Amazon review data was collected from the Computer Science department of UCSD.

### Data Pre-processing
- Parsing and cleaning the data to remove unnecessary elements like spaces, punctuation, and stopwords.
- Tokenization of reviews for sentiment analysis.

### Network Analysis
- Generation of node and edge lists for network analysis.
- Calculation of degree centrality, average degree, and network density.

### Topic Modeling
- Implementation of Latent Dirichlet Allocation (LDA) to identify hidden topics in product reviews.
- Visualization of topics using pyLDAvis.

### Sentiment Analysis
- Sentiment analysis on product reviews using VADER, an NLTK module.
- Analysis of the sentiment distribution and frequent words in reviews.

### Product Recommendation
- Development of a recommendation system using machine learning-based collaborative filtering.
- Evaluation of the recommendation system using Root Mean Squared Error (RMSE).

## Experiment
- Detailed evaluation of the datasets using the methods mentioned above.
- Sentiment analysis of music and video product reviews.
- Implementation and tuning of a product recommendation system.

## Limitations
- The system's performance is limited by hardware constraints and the size of the dataset.
- The datasets used are not up-to-date.
- Difficulty in handling stopwords specific to music and video products during sentiment analysis.

## Future Work
- Exploration of deep learning techniques for product recommendation.
- Continuous improvement of the model by incorporating new data.

## Conclusion
This project successfully implemented an accurate product recommendation system by leveraging network analysis, sentiment analysis, and topic modeling. The results provide valuable insights into user preferences and enhance the overall user experience on e-commerce platforms like Amazon.

## References
- Carremans, B. (2018). Sentiment Analysis with Text Mining. Towards Data Science.
- Chuang, J., Manning, C. D., & Heer, J. (2012). Termite: Visualization Techniques for Assessing Textual Topic Models.
- Gounder, S. (2023). Co-products recommender system using Amazon metadata. GitHub.
- Gutiérrez, G. V. A. (2020). A Comparative Study of NLP and Machine Learning Techniques for Sentiment Analysis and Topic Modeling on Amazon Reviews.
- Haque, T. U. (2018). Sentiment analysis on large scale Amazon product reviews.
- Meda, V. P. S. (2019). Amazon Product Recommendation. Department of Computer Science, Blacksburg, VA. GitHub.
- Sharma, D. (2019). Sentiment Analysis Techniques for Social Media Data: A Review.
- Vishalsha. (2021). Amazon Products Analysis. GitHub.
