# Toxic_Comment_Classification
## Datasets
K-MHaS: A Multi-label Hate Speech Detection Dataset in Korean Online News Comment
- https://github.com/adlnlp/K-MHaS

## Summary
본 프로젝트에서는 LLM 사용이 증가함에 따라, 언어 윤리 문제의 중요성이 커지는 사회에서 악성 댓글 문제를 해결하기 위해 악성 댓글 종류 판별 시스템을 구현한다.
기존에 수집된 한국어 뉴스 댓글 데이터를 활용하여, 머신러닝 알고리즘을 사용해 악성 댓글의 여부에 그치지 않고, 악성 댓글의 종류까지 판별하도록 구현하였다.

텍스트 데이터 수치화 방법으로 "BoW (Bag of Words)", "TF-IDF (Term Frequency–Inverse Document Frequency)", "Word2Vec (Word to Vector)" 세 가지를 이용하고, 머신러닝 알고리즘은 Logistic Regression, Naïve Bayes, XGBoost를 이용하여 다중 클래스 분류 모델을 구축한다. 


세가지 임베딩 방식에 머신러닝 알고리즘 별로 모델을 만들어 성능을 비교해 본 결과 BoW 임베딩에서 XGBoost 알고리즘을 이용해 학습한 모델이 79% 정도의 정확도로 가장 높은 성능을 보였다. 
