# SSAFY EnjoyTrip [여행객을 위한 플랫폼 구현]

## 팀원 <img width="91" alt="star3" src="https://user-images.githubusercontent.com/78655692/151471989-9e21d7a8-a7b6-44b0-b598-2bb204b56b00.png">
| 이름   | GitHub                                         |
| ------ | ---------------------------------------------- |
| 서정운 | [@SlowCloud](https://github.com/SlowCloud) |
| 이강우 | [@dbdbais](https://github.com/dbdbais) |


## 기술 스택 <img width="91" alt="star3" src="https://user-images.githubusercontent.com/78655692/151471989-9e21d7a8-a7b6-44b0-b598-2bb204b56b00.png">


![stack](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/69882e68-80f5-4fb8-9e26-23dc8ddf5d92)

- FrontEnd : Vue.js, BootStrap
- BackEnd : SpringBoot (Java)
- DataBase : MySql, MyBatis
- API : OpenWeather, Kakao map, Jsoup, Spring Boot Starter Mail
- ETC : Swagger


## 개발 일정 <img width="91" alt="star3" src="https://user-images.githubusercontent.com/78655692/151471989-9e21d7a8-a7b6-44b0-b598-2bb204b56b00.png">
<img width="1000" alt="일정" src="https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/6d95d39d-1c4b-4caa-a918-a1baf529a235">



## 구현 기능 <img width="91" alt="star3" src="https://user-images.githubusercontent.com/78655692/151471989-9e21d7a8-a7b6-44b0-b598-2bb204b56b00.png"> 

- 공공데이터와 KaKao Map API를 활용한 여행지 조회 플랫폼

- 사용자 회원가입, 로그인, 메일로 비밀번호 찾기, 마이페이지

- 게시판, 공지사항, 검색, 댓글 좋아요 기능
  
- 첨부파일 이미지 저장을 이용한 프로필 이미지 연동
  
- 날씨 API를 활용한 검색 위치의 날씨를 고려한 여행경로 설정
  
- 사용자들의 여행계획 조회 및 등록
  
- 검색 위치를 기반으로 웹 크롤링을 이용한 핫플레이스 등록 및 조회
  
- 메인 페이지에 핫플레이스 이미지 업로드

- CHAT-GPT API를 이용한 챗봇 가능

## Swagger <img width="91" alt="star3" src="https://user-images.githubusercontent.com/78655692/151471989-9e21d7a8-a7b6-44b0-b598-2bb204b56b00.png"> 
<img width="951" alt="명세서" src="https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/27a8d69f-6d2c-4513-bb37-3fa8c06de999">

## 동작 영상 <img width="91" alt="star3" src="https://user-images.githubusercontent.com/78655692/151471989-9e21d7a8-a7b6-44b0-b598-2bb204b56b00.png"> 



|회원 가입|
|:---:|
|![회원가입](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/6e64cdf3-4812-4229-a739-e7a1b8fd0ccd)|

|PW찾기 / 로그인|
|:---:|
|![PW조회](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/9e94dc60-14a7-4c6d-8595-c1642f8e60fe)|

|게시글 & 댓글 CRUD / 조회 수, 좋아요 |
|:---:|
![게시판](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/fe0d8aca-7f39-4d6d-8536-cf0c7691f3d6)|

|키워드 검색 / 페이지네이션 / 공지사항 / 조회 순 정렬 / Q&A 게시판|
|:---:|
|![페이징](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/5235ec4f-bd39-4de7-a334-ce770f21e876)|

|여행계획 조회|
|:---:|
|![여행계획조회](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/8f6ef769-be9a-4cd9-83ea-71d7e84d58c6)

|위치 기반 날씨 조회 |
|:---:|
|![날씨 API](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/60a1beb1-97c1-4421-a37b-85e53a366ab7)|

|여행 계획 등록|
|:---:|
|![여행계획 등록](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/66b98102-fabe-47fa-9621-50c9fc673e16)|

|위치 기반 웹 크롤링 |
|:---:|
|![웹크롤링](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/ab2e01b3-6deb-4ee9-ae71-446460636b5d)|

|핫플레이스(리뷰) 등록|
|:---:|
|![핫플레이스 등록](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/457e28f2-291f-49aa-b032-4e43bb212510)|

|핫플레이스(리뷰) 랜덤 조회|
|:---:|
|![핫플레이스 게시](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/481f0332-9a8a-48b7-b12b-4dae8cf80e5e)|

|여행 도우미 챗봇|
|:---:|
|![CHAT-GPT](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/b0174f8b-8117-49d2-8656-82f90338a98e)|


## ERD <img width="91" alt="star3" src="https://user-images.githubusercontent.com/78655692/151471989-9e21d7a8-a7b6-44b0-b598-2bb204b56b00.png"> 

![erd](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/273bb91f-bdd5-4b08-87d3-5e1c64fca2ff)


## Use Case Diagram <img width="91" alt="star3" src="https://user-images.githubusercontent.com/78655692/151471989-9e21d7a8-a7b6-44b0-b598-2bb204b56b00.png"> 

![usecase](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/86bac48f-e933-4d3a-acc7-15a976886598)


## Class Diagram <img width="91" alt="star3" src="https://user-images.githubusercontent.com/78655692/151471989-9e21d7a8-a7b6-44b0-b598-2bb204b56b00.png"> 


![1](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/94fc169c-0d70-40a7-b90e-9c4f24a66b1a)
![2](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/1436d30a-96fb-44ee-b009-2a2338089cc1)
![3](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/cdadd23b-5c61-4f9a-b196-ab3d6042ee11)
![4](https://github.com/dbdbais/SSAFY_TripProject/assets/99540674/08399228-2598-41cd-b3a0-423156cf11ca)

## 개발 후기

- 백엔드에 업로드 한 이미지를 즉각으로 가져오지 못해 시간이 많이 소요되었다.
- DB 설계 후에 수정해야 할 일이 많아 시간이 많이 소요되었다.
- 프로젝트 기간이 짧아 테스팅과 유지보수할 시간이 없어 아쉬웠다.
