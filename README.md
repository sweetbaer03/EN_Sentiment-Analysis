# EN_Sentiment-Analysis

빅데이터자연어처리기술
기말고사 감정분석 과제

## 1.   데이터셋

 영어드라마 Friends dataset

  (http://doraemon.iis.sinica.edu.tw/emotionlines/download.html)
 

## 2.   실험모델

*   BERT
*   ELECTRA
*   DistilBERT

## 3.   추가데이터
*   IMDB 데이터셋


## 4. 각 모델별 전처리 방식

실험 모델|전처리|모델|
|------|---|---|
|BERT|bert-base-uncased|bert-base-uncased|
|ELECTRA|electra-small, electra-base, electra-large|electra-small, electra-base, electra-large|
|DistilBERT|distilbert-base-uncased|distilbert-base-uncased|

## 5. 참고자료

ELECTRA : 
https://github.com/jiwonny/nlp_emotion_classification/blob/master/friends_electra.ipynb

텐서플로2와 머신러닝으로 시작하는 자연어 처리(전창욱 외, 위키북스, 2020) 참고
(IMDB전처리까지)
