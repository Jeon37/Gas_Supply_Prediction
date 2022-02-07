# Gas_Supply_Prediction
## 💻프로젝트 소개
- **목적:** 시간단위 공급량 데이터 및 기상정보 등 외부데이터를 이용해 일간 공급량을 예측하는 모델 개발

- **참가 대회:** [데이콘 가스공급량 수요예측 모델개발](https://dacon.io/competitions/official/235830/overview/description)

- **기간:** 2021.09~2021.12

- **팀원:** 전지우, 김현지, 전보민, 김유민, 임혜리
<br>

## 📑사용 데이터셋
**1. 대회 제공 데이터** : 한국가스공사 시간별 공급량 데이터

**2. 외부 데이터**
- 전산업생산지수
- 가스기름 상대가격
- 가스전기 상대가격
- 2013 ~ 2018년 기온 데이터

> **출처:** 
  - [공공데이터포털](https://www.data.go.kr/index.do), 
  - [기상자료개방포털](https://data.kma.go.kr/cmmn/main.do) 
<br>

## 🗝️ 진행 과정
![image](https://user-images.githubusercontent.com/80508535/152716988-0649c354-21cd-4144-a439-34b058923224.png)
![image](https://user-images.githubusercontent.com/80508535/152717018-591f2a38-60b7-472b-bc19-54552561a4bc.png)
![image](https://user-images.githubusercontent.com/80508535/152717042-3cc7ceee-1357-4137-b624-946a7d64720a.png)
![image](https://user-images.githubusercontent.com/80508535/152717055-8709df33-62cd-4b7b-870c-068c0ad13036.png)
![image](https://user-images.githubusercontent.com/80508535/152717059-275f9089-f655-46a3-9c96-b825b324abd6.png)
![image](https://user-images.githubusercontent.com/80508535/152717063-b06d5d48-de49-42b2-9d5d-efa683f71447.png)
![image](https://user-images.githubusercontent.com/80508535/152717079-949bce24-343d-492e-a896-2ad149bbe81f.png)

**결과** : Accuracy(NMAE) : 0.11121


## 🗓️프로젝트 진행 일정  

|   주차   |   일정   |   내용   |   과제 및 논의   |
|:----------------------------|:----------------------------:|:--------------------:|:-------------------:|
|  1  | 2021.09.26 | OT | 프로젝트 세분화 |
|  2  | 2021.09.27~2021.10.10 | 전력사용량 예측 코드 리뷰 | Analytics 및 알고리즘 모델링 코드 리뷰 |
|  3  | 2021.10.11~2021.10.31 | 가스공급량 데이터 전처리 | 대회 선정 및 EDA 진행, Baseline 모델 구축 |
|  4  | 2021.11.01~2021.11.20 | 가스공급량 데이터 모델링 | Feature Engineering 및 모델링 |
|  5  | 2021.11.21~2021.12.03 | 가스공급량 데이터 모델링 | 모델 앙상블 및 하이퍼파라미터 튜닝 | 
