# 지도를 기반으로 한 장소 기록 서비스(팀명: 봄이 오겠조)
![traveler_main](https://user-images.githubusercontent.com/100760266/170603134-2a5562c5-9521-4c40-badb-83c03610540a.png)


## 1. 프로젝트명
* 지도를 기반으로 한 장소 기록 서비스
* 서비스설명: 자신에게 소중한 경험을 선사했던 장소라는 매개체를 지도 위 마커로 나타내어 전체 사용자와 함께 공유하는 서비스입니다.

## 2. 주요기능
* 마커 생성 및 게시물 작성
* 마커 생성순으로 선 이어 타임라인 만들기
* 팔로우한 사람의 마커와 타임라인, 게시물 확인하기
* 카테고리별 마커 및 게시물 확인하기

## 3. 개발환경
|구분|내용|
|------|---|
|사용언어|Java, HTML, CSS, JavaScript|
|사용한 라이브러리| Bootstrap / Kakao Map |
|개발도구|Eclipse |
|서버환경|tomcat 9.0|
|데이터베이스| oracle 11g |

## 4. 아키텍처(구조)
![서비스 아키텍처](https://user-images.githubusercontent.com/100760266/170609265-8506e39e-1259-4158-955f-4a80925909b5.png)


## 5. 기능 흐름도
### 서비스 흐름도(유스케이스)
#### SW 유스케이스
![흐름도](https://user-images.githubusercontent.com/100760266/170609448-24b0f334-e242-484a-a213-3e661373085c.png)

#### 서비스 흐름도(웹 화면설계서)
![image](https://user-images.githubusercontent.com/100760266/170609658-e3db0066-8b88-4235-9a5e-a36a9c0d893d.png)

#### ER 다이어그램
![image](https://user-images.githubusercontent.com/100760266/170611412-57321696-406a-4e9e-b2d6-53a759b2e537.png)

## 6 SW 동작 화면
### 로그인/회원가입/회원괸리/회원수정/회원탈퇴
![제목을-입력해주세요_-001](https://user-images.githubusercontent.com/100760266/170613256-973393e3-73f1-4de5-bb91-c5e7c909a0f9.png)

### 지도 기반 기능(마커 생성 및 게시물 작성, 타임라인 확인, 카테고리별 마커 및 게시물 확인)
#### 마커 생성 및 게시물 작성
![제목을-입력해주세요_-001 (1)](https://user-images.githubusercontent.com/100760266/170613930-9cdc6d3e-ba23-45c0-b735-ef3183413304.png)
#### 타임라인 확인
![제목을-입력해주세요_-001 (2)](https://user-images.githubusercontent.com/100760266/170614383-2554b519-aa5b-4bf4-8c8c-6d289273531d.png)
### 카테고리별 마커 및 게시물 확인
![제목을-입력해주세요_-001 (3)](https://user-images.githubusercontent.com/100760266/170614832-221fdb34-2a22-46bc-a91d-88529d460782.png)

## 7 제작 일정
![image](https://user-images.githubusercontent.com/100760266/170614924-0f4a9ab0-4fa4-44b0-96ff-40dcecb7ed97.png)

## 8 팀원 단위 업무 분장 및 결과표
![image](https://user-images.githubusercontent.com/100760266/170615082-8c13f286-6934-4409-b5d8-bdc0b615c82d.png)

## 9 트러블슈팅
* [문제1] 깃허브 충돌 문제<br>
[해결방안1] 구글 스프레드 시트를 통해 작업 시트를 생성함. 작업시 작업 파일명과 작업자의 이름을 작성하도록 함. <br>
[해결방안2] push 작업 전 전체 작업자들에게 공지 후 공지 시점을 기준으로 작업 시트를 재작성하도록 함.  
 
* [문제2] 광범위한 사용자 범주<br>
[해결방안] 카테고리와 팔로우 기능을 통해 사용자를 분류하여 기능을 이용할 수 있게함.
