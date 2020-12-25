# Python-Project
tutorial repository


# 소개
#### 위 코드는 HuggingFace BERT를 사용하여 감정 분석을 진행했습니다.

# 설명
##### BERT(Bidirectional Encoder Representations from Transformers)는 구글이 개발한 사전훈련(pre-training) 모델입니다. 
##### 위키피디아 같은 텍스트 코퍼스를 사용해서 미리 학습을 하면, 언어의 기본적인 패턴을 이해한 모델이 만들어집니다. 
##### 이를 기반으로 새로운 문제에 적용하는 전이학습(transfer learning)을 수행합니다. 좀 더 적은 데이터로 보다 빠르게 학습이 가능하다는 장점이 있습니다. 

## 데이터 설명
### 1. (한국어) 네이버 영화 리뷰 데이터 
#### 1) 칼럼명: id : 아이디 / document : 문장 / label : 긍정(1)/부정(0)
#### 2) 데이터 셋 종류 :train data/ test data
#### 3) 한국어 데이터 셋의 주소 : https://github.com/e9t/nsmc.git

### 2. (영어) Friends data
#### 1) 칼럼명 : speaker :화자 / utterance : 대화 /emotion : joy, surprise, non-neutral ,sadness , disgust, fear, anger, neutral
#### 2) 데이터 셋 구성 : train data/ dev data / test data
#### 3) 영어 데이터 셋의 주소 : http://doraemon.iis.sinica.edu.tw/emotionlines/index.html

### 3. 참고한 자료
#### https://colab.research.google.com/drive/1EMzEfTYjYLgEHjCCP1vEr9oOZLXMocGh?usp=sharing
#### https://github.com/deepseasw/bert-naver-movie-review
#### https://stackoverflow.com/questions/44560549/unbalanced-data-and-weighted-cross-entropy
#### https://medium.com/@eyfydsyd97/bert-for-question-answer-fine-tuning%EC%9D%84-%ED%99%9C%EC%9A%A9%ED%95%98%EC%97%AC-by-pytorch-fbe15fdef330
#### https://www.kaggle.com/javaidnabi/toxic-comment-classification-using-bert
