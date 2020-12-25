# Python-Project
tutorial repository


# 소개
#### 위 코드는 HuggingFace BERT를 사용하여 감정 분석을 진행했습니다.

# 데이터 설명
## 1. (한국어) 네이버 영화 리뷰 데이터 
### 구성 : 
#### 1) 칼럼명: id : 아이디 / document : 문장 / label : 긍정(1)/부정(0)
#### 2. 데이터 셋 종류 :train data/ test data
#### 한국어 데이터 셋의 주소 : https://github.com/e9t/nsmc.git

## 2. (영어) Friends data
### 구성:
#### 1. 칼럼명 : speaker :화자 / utterance : 대화 /emotion : joy, surprise, non-neutral ,sadness , disgust, fear, anger, neutral
#### 2. 데이터 셋 구성 : train data/ dev data / test data
#### 영어 데이터 셋의 주소 : http://doraemon.iis.sinica.edu.tw/emotionlines/index.html

### 참고한 자료: 
#### https://github.com/deepseasw/bert-naver-movie-review
#### https://stackoverflow.com/questions/44560549/unbalanced-data-and-weighted-cross-entropy
#### https://medium.com/@eyfydsyd97/bert-for-question-answer-fine-tuning%EC%9D%84-%ED%99%9C%EC%9A%A9%ED%95%98%EC%97%AC-by-pytorch-fbe15fdef330
#### https://www.kaggle.com/javaidnabi/toxic-comment-classification-using-bert
