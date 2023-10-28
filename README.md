# Korean-Sign-Language-presentation-with-deep-learning

## 딥러닝을 이용한 한국수화언어 통역 시스템 설계 및 구현 발표
### 팀명 : 수화 사이드, 팀장 : 이경섭, 팀원 : 김주연, 이수민

***

![이재화 강사님 과제](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/d1ff47e6-ba7c-4f2a-8e72-5c75324417f2)

## 필요성

1. 청각 장애인의 인구 : 약 35만명
 
2. 그중 80%가 수어가 가능하다.

3. 한국 수화 언어 연구소에서 표본 통계를 냈을 때 500명중 327명이 기술의 발달로 새로운 세상이 열리기를 기대하고 있다.

4. 일반인에 비해 정보 취득과 의사소통의 문제로 지적 능력 향상이 어렵다.

5. 이에 따라 사회적 격차를 초래하고 있다.

## 기존 연구 동향

미국(영어) <-> 한국어 - 언어 구성의 차이가 수화에서도 똑같이 적용된다.

한국수화언어에도 자연수화언어, 문법수화언어, 지문자 등으로 연구가 나뉘어 한국수화언어 통역 연구가 필요하다.

## 수화 연어의 특징

![수화하는 이미지](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/16d402fd-57da-48d4-9b3d-8af9a05e3b7b)

![수화의 구성](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/7058d71a-544b-4ff7-ba36-011aae4fdc43)

## 수화 언어 인식법

***

### 1) 영상 검출

![영상검출](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/6d69420a-0d08-4cff-a6ad-f2ed1a1a9044)

### 2) 데이터 글러브를 이용한 수화언어 인식

![데이터 글러브를 이용한 수화언어 인식](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/fc1b98cb-f745-4e08-a3a7-ea2636fb5fef)

### 3) 키넥트를 이용한 수화언어 인식

#### 3차원 인지

![3차원 인지](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/4f06cb1d-b9b2-49ff-b3a0-fda5360361a4)

#### 스켈레탈 매핑(skeletal mapping)

![스켈레탈 매핑](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/be245778-ce32-4623-980e-d67f4995c9f9)

#### 4) 립모션을 이용한 수화언어 인식

![립모션을 이용한 수화언어 인식](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/f6bbaaed-5c37-4ad1-873d-451b92e9d1ac)

한계점 : 얼굴 표정과 같은 비지수 요소를 포함하지 못함.

#### 5) 딥러닝을 이용한 수화언어 인식

![딥러닝을 이용한 수화언어 인식](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/10c0cb78-5a07-4670-aa6d-57c52337e4a0)

CNN 기법인 GoogleNet 모델을 사용하여 실시간 미국수어(ASL) 지문자 인식을 수행하였는데, Top-5 Accuracy 0.9163의 성능을 보임.

## 한국 수화 언어 통역 시스템

### 한국수화언어 특징 추출 모듈

***

### 딥러닝 모델

#### YOLO(You Only Look Once)

![Yolo](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/c10bd8a8-78e0-4619-a23d-73237e11fe70)

#### Tiny-YOLO

![tiny Yolo](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/c6bbf271-5b93-4428-9dd3-473b0f3f5be7)

1) YOLO 모델 중 가장 작은 연산량을 자랑하는 모델이다.

2) GPU 사용시 244FPS의 빠른 성능을 자랑한다.

3) 증강/혼합현실용 HMD와 같은 웨어러블 디바이스 적용에 용이하다.

### 딥러닝을 이용한 객체 인식

#### SqeezeNet

![SqeezeNet](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/4590fedf-d125-445e-83ba-1bf73131e790)

#### Dense Net

![DensNet](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/0caf0f01-ec49-4075-aa47-135e2798cf57)

### 홀로렌즈

![홀로 렌즈](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/dccc7d31-37bb-4bcf-b69f-a72a3a00309c)

#### HoloLensHandNet

![HoloLensHandNet](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/fcc0a4a6-87ba-440e-bd5e-c7eaa204e837)

#### 한국수화언어 통역 시스템 구성안

![홀로 렌즈 통역 시스템 구성안](https://github.com/Leegyeongseob/Korean-Sign-Language-presentation-with-deep-learning/assets/67867076/ac66ffdd-213e-4f31-b1ca-109e4aae5a36)

## 결론

***

### 한게점 : 한 화자의 수화언어만 통역이 가능

#### 손 모양의 수형을 65가지로 코드화하여 사용한다. 이는 손 모양에 따라 수형코드로 검출할 수 있으나 동일한 수형에 있어 회전과 같은 시퀀스 정보를 포함 할 수 없는 제한점이 있다.

### 향후 연구 구현 과제

#### PC 환경 및 증강/혼합현실 HMD와 같은 웨어러블 디바이스뿐만 아니라 휴대폰과 같은 범용적인 모바일 디바이스 환경에서도 활용할 수 있을 것으로 기대된다. 그리고 한국수화언어 대화 가이드 시스템으로 확장 할 수 있다.

### Reference

***

#### 신기철, 이승훈, 권재영, 장현̀, 이희연. (2019). 영상인식과 립모션을 활용한 한̀수어 번역. 한̀HCI학회 학술대회, (), 645-649.

#### 정동화, 송준영, 이영훈, 이현승, 강소희, 임완수. (2019). 신경망과 TFLITE를 이용한 한̀수어 번역 알고리즘 ˿현. 한̀통신학회 학술대회논문집, (), 499-501.

#### 김송희, 신다솜, 윤정민, 이응규, 장성찬, 어수웅, 노병희, 곽진. (2016). 키넥트를 이용한 수화 번역 시스템. 한̀통신학회 학술대회논문집, (), 1077-1078.

#### 구민재. "딥러닝을 이용한 한̀수화언어 통역 시스템 설계 및 ˿현." ̀내석사학위논문 한̀방송통신대학교 대학원, 2019. 서울

#### 강소희, 김용겸, 김유신, 배승용, 박지현, 이정환, 정동화, 임완수. (2018). 신경망을 이용한 한̀수어 번역 알고리즘 ˿현. 대한전자공학회 학술대회, (), 765-768.

#### Kim, Kwang-Baek , Song, Doo-Heon , Woo, Young-Woon(2010).Real Time Recognition of Finger Language Using Color Information and Fuzzy
Clustering Algorithm.학술저널().
19-22(4쪽)

#### 이동형 , 강만모 , 김영기 , 이수동.(2009).Sign Language recognition Using Sequential Ram-based Cumulative Neural Networks.학술저널
().205-211(7쪽)

#### 정택위(Teak-Wei Chong) , 김범준(Beom-Joon Kim).(2020).딥러닝 방식의 웨어러블 센서를 사용한 미̀식 수화 인식 시스템.학술저널().291-297(7쪽)

### SEUNG-KANG LEE. 지도교수:Ho-Joon Kim(2014).수정된 FMM 신경망을 이용한 수화 인식 기법.한동대학교 대학원. vi, 44 p.

#### 김호준(Ho-Joon-KIM).(2012).수화 패턴 인식을 위한 2단계 신경망 모델. 한동대학교 전산전자공학부.319-327(8쪽)

#### 배효철.지도교수: 윤경로.(2020).심층 신경망을 이용한 한̀ 수어 단어 인식.학위논문(박사)-- 건̀대학교 대학원 : 컴퓨터·정보통신공학과. vi. 1~99 p
