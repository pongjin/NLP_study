# NLP_study
> * 스터디 기간 : 23.01.01 ~ 23.02.10
> * 참고도서 : 딥 러닝을 이용한 자연어 처리 입문 [E-book](https://wikidocs.net/book/2155)
> * 목표 : 텍스트 전처리, 빈도 기반 분석, 워드 임베딩, 딥러닝 모델 구현
> * 각 주차 별 세부 내용은 코드 마다 정리  
> * 스터디 노션 링크 : [Notion](https://ancient-tip-9ff.notion.site/2253e1917efb4be585139ff030162350)
## 스터디 후기
한달 남짓한 시간으로 인해 책 내 심화과정까지는 다루지 못했지만, 자연어 처리에 대한 기초지식을 쌓을 수 있는 좋은 경험이였다. 결합어인 한글에 비해 영어는 토큰화 같은 전처리가 쉬워 비교적 쉽게 모델링까지 접근할 수 있었던것 같다.   
추후 BERT 모델과 같은 transformer를 다루는것과, 한국어 전처리를 영어처럼 쉽게 할 수 있는 방안에 대해 공부해 볼 예정이다. 

## 1주차 : 텍스트 전처리
(책 2장)  
1. ### tokenization<br>

2. ### cleaning & normalization  
    punctuations 처리 <br>
    어간(stemming), 표제어(lemmatization) <br>
    불용어(stopwords)<br>
    정규 표현식(regex)

## 2주차 
1. ### 빈도 기반 표현 및 분석
   (책 4장)  
    bow / DTM / TF-IDF<br>
    Count/Tfidf Vectorizer parameter<br>
    분류모델 : 전처리 방법에 따른 성능 비교<br> 
2. ###  워드 임베딩 기초
    (책 9장)  
    Word2Vec
      * CBOW 
      * Skip-Gram

    FastText<br>
    Keras Embedding()

## 3주차  
1. ### 워드 임베딩 심화
   (책 9장)  
    #### Pre-Trained Embedding 
    * embedding layer  
    * fine-tuning  


2. ### 딥러닝 이론 및 ANN DNN
   (책 7장)  
    * how to avoid overfitting 
    * Neural Network Language Model  

## 4주차 

1. ### RNN models
    (책 8장)  
    * vanilla RNN
    * LSTM, GRU, BiLSTM
2. ### 데이콘 실습 데이터 전처리
    * EDA

## 5주차
1. ### 데이콘 실습 데이터 모델링
    * NN + pre-trained w2v
    * Bi-LSTM + pre-trained w2v 
    * NN + Emb layer
2. ### 스터디 보고서 작성
    * (발표자료는 팀원들과 같이 작성)