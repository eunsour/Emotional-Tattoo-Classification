# Emotional-Tattoo-Classification-and-Recommendation-Service
감성 타투 도안 분류 및 유사도 기반 추천 서비스 - 팔레트<br><br>

## 기획 배경
팔레트 프로젝트는 한국 인구 10명 중 2.5명이 경험이 있을 정도로 수요가 높은 타투를 사용자와 타투샵과의 편리한 매칭을 위해 기획하였으며, 사용자가 원하는 도안의 윤곽선을 그리면 이와 유사한 타투샵의 도안을 출력해주고 예약까지 이어지는 시스템으로 구성하였습니다.<br><br><br>



## 주요 기능 설명
### **사이트 메인화면**
<br>

![ezgif com-gif-maker (8)](https://user-images.githubusercontent.com/67885590/102000511-905f8800-3d2b-11eb-8c20-6032a574c8d6.gif)

<br>

> 메인화면에서는 타투 도안 추천 서비스, 타투 설문, 타투샵 랭킹, 타투 용품, 리뷰 게시판, 챗봇 등을 이용할 수 있습니다.

<br>


### **그림판**
<br>

![ezgif com-gif-maker (10)](https://user-images.githubusercontent.com/67885590/102000543-d288c980-3d2b-11eb-8817-a6b98551ebe7.gif)

<br>

> 사용자가 그림을 그리고 업로드하면 서버에 그림이 저장되고, 전송하기 버튼을 누르면 Flask 통해 파이썬 모듈을 실행합니다. 이후 사용자가 그린 도안을 종류별로 분류하고 기존 도안과 비슷한 도안들을 추천해줍니다.

<br>


### **설문조사**
<br>

![ezgif com-gif-maker (11)](https://user-images.githubusercontent.com/67885590/102000551-e03e4f00-3d2b-11eb-920c-ff3c698895d0.gif)

<br>

> 800여 개의 타투들 중 랜덤으로 25개를 5개씩 5번 랜덤으로 보여주고 그 중 선택한 값 5개를 기반으로 협업 필터링을 통해 사용자가 만족할 만한 타투들을 5개 추천해줍니다..

<br><br>

## Database Modeling
![3차ERD](https://user-images.githubusercontent.com/67885590/102000485-5a220880-3d2b-11eb-91c0-203dec6ac684.PNG)

<br>

## 시연 영상
- YouTube : https://www.youtube.com/watch?v=0UsQITQ9IeY
