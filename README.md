
![CinePicLogo](https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/cabb5d17-d933-4062-be9e-e45eae85a529)

# CinePic
🔗 **CinePic 사이트**  

https://cinepic2024.site </br>

🔗 **발표 PPT**

[파이널 프로젝트 피피티-Cine Pic.pptx](https://github.com/user-attachments/files/15971084/-Cine.Pic.pptx)


🔗 **CinePic 페이지**

[씨네픽 전체 이미지.pdf](https://github.com/user-attachments/files/15971146/default.pdf)

## 🔍 프로젝트 소개 및 개요
**사용자 맞춤 영화 추천 및 커뮤니티를 활용한 영화 플랫폼 사이트**
1. 사용자 맞춤 영화 추천(머신러닝)
2. 독립 영화 상영극장 정보 제공(지도 api)
3. 700여 가지의 다양한 영화 정보 제공(엘라스틱 서치)
4. 사용자 간 소통을 할 수 있는 커뮤니티 및 채팅 기능(무한스크롤, 웹소켓 외)

## ⏰ 개발기간
2024.01.17 ~ 2024.02.21(1개월)

## 📌 프로젝트에 포함 될 주요 기능
- 주제 선정, 화면 구성(Figma)부터 프론트엔드, 백엔드, DataBase 설계, AWS 배포까지 전반적인 구현 경험
- CRUD 구현 및 다양한 API 활용
- React, Java, SpringBoot, MySQL, jwt, 웹소켓, Python, ElasticSearch, 머신러닝을 이용한 여러 기술 익히기
- 문서 작업(wbs 및 단위 테스트 진행)
    - WBS 방식의 일정 작성
    - 스토리 보드 작성
    - 기획 문서(일정, 팀원 역할, 설계 문서(ERD), 주제 선정)
- 필수 기능
  1. 머신러닝을 활용한 맞춤 영화 추천
  2. ElasticSearch를 활용 한 영화 검색
  3. 이메일 인증(아이디=이메일)
  4. 맞춤 추천을 위한 유저 취향 수집 (취향 설문 + 북마크 + 검색키워드)
  5. 게시판 활용(모임 모집 및 후기 공유(댓글 기능))
  6. 검색한 지역의 영화관 정보 제공
  7. 결제 ⇒ 멤버십 회원은 광고 제거
  8. 영화 상세 정보 제공 + (유저 평점, 간이 포스트 기능)
  9. 유저간 채팅기능
  10. 관리자 페이지 (시각화)
- 배포
    - AWS 클라우드 서비스 배포
    - 도메인 계정 등록(가비아)

## 작업 진행 현황
- **캘린더 일정**
  <img width="1292" alt="일정1" src="https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/be9f7724-9da1-4140-9196-47764af2101a">
  
  <img width="1292" alt="일정2" src="https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/23a6074f-5b08-4588-9dc9-c3b8c5706aab">

## 👨‍👩‍👧‍👦 역할분담 및 나의 역할
| 팀원 | 역할 |
| --- | --- |
| 김현지(팀장) | 로그인,회원가입 페이지 / 영화 검색 (엘라스틱 서치) |
| 박소현 | 메인페이지(머신러닝) / 결제페이지 / 관리자페이지  |
| 김지은 | 영화상세 페이지 / 게시판 리스트 페이지 |
| 황선영 | 영화관 정보 / 취향 선택 페이지 |
| 유현주 | 마이페이지 / 404페이지 / 카카오 대기페이지 / 이메일인증(Backend)/ 관리자(FAQ) |
| 이세웅 | 게시글 상세페이지 + 댓글 / 게시글 작성 및 수정 페이지 |

| 구현 내용 | 상세 정보 |
| --- | --- |
| 메인화면 | 메인 사진영화추천(로그인 전) </br> 회원 취향관련 영화추천(로그인 후)</br>요일별 장르 추천</br>페이지 내 다른 기능페이지 이동</br>중간 배너(광고)
FAQ창 |
| 로그인 및 회원가입 | 회원 로그인 / 관리자 로그인카카오 로그인(제 3자 인증방식)</br>회원가입(이메일 인증,취향 등록)</br>비밀번호 찾기 |
| 엘라스틱서치(검색기능) | 영화 검색(최신순,관련순) |
|  머신러닝 | 영화상세내용 |
| 채팅기능 | 영화취향 공유 채팅방 |
| 결제기능 | 광고결제 |
| 취향수집 | 북마크 |
| 마이페이지 | 회원정보수정</br>내 취향 수정</br>내 글 관리하기 |
| 관리자페이지 | 회원 관리</br>게시판 관리</br>FAQ 관리 |
| 영화 검색 | 무한스크롤</br>과거순 정렬</br>영화 검색이나 키워드 검색 |
| 영화 상세 정보 | 후기 댓글</br>포토 후기</br>게시판</br>스틸 컷(모달)</br>씨네포스트 - 가로 슬라이드</br>최신순, 과거순 필터</br>검색기능 |
| 영화 상세 정보 제공 지도 api | 독립, 예술 영화관 찾기</br>시나 도 키워드 검색으로 상세내용 및 선택 키워드 마커표시 |
|  jwt 보안 | 보안설정 |
| Python 크롤링 | 영화정보 가져오기</br>지도 데이터 정보 받아오기 |
| 오류페이지 | 404페이지 |

### ⚙️ 사용기술 및 환경

- 동작 원리


  ![요청](https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/653e7fb2-faa0-466e-8b16-68979a833053)


| 분류 | 기술 |
|----|----|
| 사용 언어             | HTML, CSS(SCSS), JavaScript(JSX) / Java / Python  |
| 프론트엔드 라이브러리 | React                                           |
| 백엔드 프레임워크     | Spring Boot - JPA / Flask                       |
| 검색 엔진             | ElasticSearch                                   |
| RDBMS                | MySQL                                           |
| 클라우드 스토리지     | Firebase Storage                                |
| IDE                  | IntelliJ, VScode, MySQL WorkBench, DBeaver, Pycharm |
| 협업 도구            | GitHub, Notion, Figma, Google Spreadsheet        |
| MockUp Tool          | Figma                                           |
| 형상 관리             | Git, GitHub                                     |
| 테스트               | Postman, swagger UI, Junit                      |


### 개인 담당 역할
### 취향 등록 구현
로그인 전 : 영화 장르 / 성별 / 선호 배우 / 선호 감독 선택함으로써 기본적인 취향 수집


### 취향 등록 구현 페이지

### 취향 수정 구현
로그인 후 : 마이페이지에서 회원가입 시 한 내용을 수정하고 싶다면 영화 장르 / 성별 / 선호 배우 / 선호 감독 취향 수정 할 수 있음

### 취향 수정 구현 페이지

### 지도API 구현
검색 창에 구 또는 시를 검색하면 독립 예술 영화관에 대한 정보가 지도에 뜨고 하나를 선택하게 되면 그 내용에 맞는 상세내용이 뜸

### 지도API 구현 페이지

## 📌 문서 작업
- **wbs**


<img width="1161" alt="WBS" src="https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/2550bcb0-3bf9-415a-84b3-f1c754f173f8">

- **단위 테스트(front)**


<img width="1341" alt="단위테스트 - 프론트" src="https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/6311b251-a1e5-4628-8f55-5283400adf61">

- **단위 테스트(back)**


<img width="1341" alt="단위 테스트 - 백엔드" src="https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/43d3ce0f-fe36-48bf-9eb3-36c81bec0618">
<img width="1223" alt="단위 테스트 - 백엔드2" src="https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/85e03d67-4ef1-42f3-a156-7eda1cd7078e">

## 📌 작업 리스트
### 스토리보드

#### ERD


  ![cinepic_erd](https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/f91d96d1-d38a-4cbe-b095-52a50755338c)

#### PREFER

- id(자동생성) / 회원ID / 감독이름 / 배우이름 / 성별 / 영화장르

- 취향 테이블 필요(로그인 전-등록) → 회원ID / 감독이름 / 배우이름 / 성별 / 영화장르
- 회원정보테이블 필요(로그인 후-수정) → 회원ID(foreign key)

| 이름 | 컬럼명 | 자료형 | 제약 조건 | 비고 |
| --- | --- | --- | --- | --- |
| 취향선택 ID | prefer_id | Long | PRIMARY KEY | 자동생성 |
| 회원ID(FK) | user_id | Member | FOREIGN KEY 
NOT NULL | 외래키(특정 사용자의 취향) |
| 감독이름 | directorName | String | NOT NULL | 최소 1개 선택 |
| 배우이름 | actorName | String | NOT NULL | 최소 1개 선택 |
| 성별 | gender | String | NOT NULL |  |
| 영화 장르 | genre | String | NOT NULL | 최소 1개 선택 |

#### THEATER

- 지도 테이블 필요 - id(영화관아이디) / 도(지역) / 시,구(도시) / 상영관이름 / 총 스크린 수 / 총 좌석 수 / 필름 상영관 수 / 2D 상영관 수 / 3D 상영관 수 / 4D 상영관 수 / IMAX 상영관 수 / 특별관 운영 여부 / 주소 / 전화번호 / 홈페이지주소 / 위도 / 경도

| 이름 | 컬럼명 | 자료형 | 제약 조건 | 비고 |
| --- | --- | --- | --- | --- |
| 영화관ID | theater_id | Long | PRIMARY KEY | 기존 고유번호 사용 |
| 도(지역) | province | String | NOT NULL | 검색 시 사용 |
| 시,구(도시) | city | String | NOT NULL | 검색 시 사용 |
| 상영관이름 | theater_name | String | NOT NULL |  |
| 총 스크린 수 | screens | int | NULL |  |
| 총 좌석 수 | seats | int | NULL |  |
| 필름 상영관 수 | screen_film | int | NULL |  |
| 2D 상영관 수 | screen_2d | int | NULL |  |
| 3D 상영관 수 | screen_3d | int | NULL |  |
| 4D 상영관 수 | screen_4d | int | NULL |  |
| IMAX 상영관 수 | screen_imax | int | NULL |  |
| 특별관 운영 여부 | is_special_screen | Boolean | NOT NULL |  |
| 주소 | theater_addr | String | NOT NULL,UNIQUE |  |
| 전화번호 | theater_phone | String | NOT NULL,UNIQUE |  |
| 극장 홈페이지 | theater_url | String | NULL |  |
| 위도 | Latitude | Double | NOT NULL | 지도에 핀 찍기 위한 고정값 |
| 경도 | longitude | Double | NOT NULL | 지도에 핀 찍기 위한 고정값 |

- 메뉴트리


  ![Untitled](https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/ad83398e-69f1-4038-b206-1a0eafc88e5a)


- **애자일 방법론**


<img width="545" alt="스프린트" src="https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/6cfb3dce-f541-4bc0-abe8-4a61be8397b4">

- **회의록**


<img width="815" alt="회의록" src="https://github.com/ghkdtjsdud0312/finalprj_total_cinepic/assets/142463073/ca9d404b-cedd-4a00-a12e-0a414455428f">
