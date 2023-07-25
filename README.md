# Project Name : ☕ Cafe-reviews-To-Stars
 카페의 전체 리뷰들로부터 원하는 가게의 평점을 리뷰로 예측할 수 있게 해주는 프로젝트

## Contents Table
- [프로젝트 상세 내용](#프로젝트-상세-내용)
    - [문제 상황](#문제-상황)
    - [기대효과](#기대효과)
    - [PROJECT 설명](#PROJECT-설명)
    - [활용 Dataset](#활용-Dataset)
- [사용 기술 및 라이브러리](#사용-기술-및-라이브러리)
- [담당한 부분](#담당한-부분) 
- [개발 환경](#Environment)
</br></br>

## 📖 프로젝트 상세 내용
### 문제 상황

- 원하는 식당이나 카페를 선정할 때 특정 지도 플랫폼의 평점, 리뷰는 중요한 역할을 담당한다.

![Alt text](Problem.PNG)

- 지도 플랫폼을 확인해 보았을 때, 같은 가게에 대한 평점이 크게 다른 것을 볼 수 있다.<br>
-> 이는 사용자들이 광고성 리뷰를 제외한 내용들을 읽어야 가게를 선정할 수 있다는 것을 의미한다.

- **원하는 지도 플랫폼에서 가게 이름으로부터 리뷰들을 얻고, 텍스트로부터 평균 평점을 에측해주는 모델을 만들자!**

### 기대효과 

- 가고싶은 가게를 선정할 때 리뷰내용을 바탕으로 평점을 계산하여 신뢰성이 있는 점수를 얻을 수 있다.
- 

- 대중교통( 지하철, 버스 등 )을 이용하여 출퇴근 할 때의 시간이나 남는 시간을 활용하여 논문 내용을 학습할 수 있다.
- 인공지능 분야가 아닌 다른 논문을 학습할 때에도 효율적으로 학습할 수 있다.
- TTS 모델을 학습시킨다면, 원하는 목소리로 내용을 들을 수 있다.

### PROJECT 설명 
![image](https://github.com/Kihoon9498/Paper-to-Speech-/assets/121469546/4a829a6b-df55-490e-8675-55e735fc9550)

논문의 정보를 쉽게 파악할 수 있도록 영어/한국어로 된 논문 내용을 한국어 음성 파일로 변환시켜 학습할 수 있게 해주는 프로젝트

### 활용 Dataset
AIHub - [논문자료 요약](https://aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=realm&dataSetSn=90)

- 3만개의 원문 / Summary 데이터 이용


## 🛠️ 사용 기술 및 라이브러리
- Numpy, Pandas, Matplotlib
- Tensorflow
- Transformers
- Hugging Face
- Bart, KoBart, Tacotron2

## 담당한 부분
- 텍스트 데이터 전처리, TTS(Tacotron2)모델 Pipeline 구축, 구현을 위한 전체 모델 연결

## 🗃️ Environment

| Env |CPU | GPU | RAM | OS 
|:--:|:--:|:--:|:--:|:--:|
| Local | i5- 10400F | RTX-3080(12G) | 32G| Window10 |
| AWS |  AMD-EPYC-7R32 | RTX-3090| 12G| Ubuntu |
| Colab + | intel Xeon | A100 | 80G | Ubuntu |
