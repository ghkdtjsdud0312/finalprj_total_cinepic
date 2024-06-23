
# CinePic
✅사이트로 이동 | https://cinepic2024.site

## 🔍 프로젝트 소개
Cinepic은 회원가입 시 등록한 취향정보, 좋아하는 영화를 북마크 한 데이터를 활용해 **사용자 맞춤 영화를 추천해주는 사이트**입니다.
사용자간 소통할 수 있는 커뮤니티와 채팅기능과 더불어 독립영화 극장정보의 정보도 제공합니다.
약 한달의 기간동안 이전 프로젝트인 '무비버스'를 **머신러닝 및 엘라스틱 서치를 적용해 업그레이드** 하였습니다.
**사용자 편의에 맞춘 UI개선**과 추가적인 기능을 더해 AWS에 배포하였습니다.
AWS 프리티어의 제한 사항을 고려하여 Flask, Spring Boot, Elasticsearch, React를 효과적으로 운영하기 위해
전체 영화 데이터를 약 700건으로 제한하고, Elasticsearch의 메모리 설정을 조정하여 서버 안정성을 확보했습니다.


✅프로젝트 상세 정보 - 노션
https://www.notion.so/cinepic-da06b8c802584538a6d9d91894e0dfb0


### ⏰ 개발기간
2024.01.15 ~ 2024.02.16

### 📌 주요기능
1. 사용자 맞춤 영화 추천(머신러닝)
2. 독립 영화 상영극장 정보 제공(지도 api)
3. 700여가지의 다양한 영화 정보 제공(엘라스틱 서치)
4. 사용자간 소통을 할 수 있는 커뮤니티 및 채팅기능(무한스크롤, 웹소켓 외)

### 👨‍👩‍👧‍👦 역할분담 및 나의 역할
1. **박소현(나)**
    - 메인페이지(머신러닝) : 머신러닝을 사용하여 사용자 취향을 고려한 영화를 추천합니다.
    - 결제페이지 : 실제 사용자의 정보를 받아 DB에 변경된 멤버십 내용을 저장합니다. 사용자 정보에 따라 광고페이지가 보이지 않도록 설정하였습니다.
    - 관리자페이지 : 차트 라이브러리를 다양하게 활용하였고, 불필요한 리렌더링을 하지 않도록 성능을 최적화하였습니다. 또한 커스텀 훅을 사용하여 토큰 관련 이슈를 해결하였습니다.

3. 김현지(팀장)	로그인, 회원가입 페이지 / 영화 검색 (엘라스틱 서치)
4. 김지은(팀원)	영화상세 페이지 / 게시판 리스트 페이지
5. 황선영	영화관 정보 / 취향 선택 페이지
6. 유현주	마이페이지 / 404페이지 / 카카오 대기페이지 / 이메일인증(Backend)/ 관리자(FAQ)
7. 이세웅	게시글 상세페이지 + 댓글 / 게시글 작성 및 수정 페이지

### ⚙️ 사용기술 및 환경

- 사용 언어 : HTML, CSS(SCSS), JavaScript(JSX) / Java / Python
- 프론트엔드 라이브러리 : React
- 백엔드 프레임워크 : Spring Boot - JPA / Flask
- 검색 엔진:  ElasticSearch
- RDBMS : MySQL
- 클라우드 스토리지 : Firebase Storage
- IDE : IntelliJ, VScode, MySQL WorkBench, DBeaver, Pycharm
- 협업 도구 : GitHub, Notion, Figma, Google Spreadsheet
- MockUp Tool : Figma
- 형상 관리 : Git, GitHub