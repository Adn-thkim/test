# Streamlit을 활용한 국내 여행지 추천 앱
## Languages
- MySQL
- Python
## Platform
- Jupyter
- Streamlit
- Google Analytics 4
- Amazon EC2
- Amazon RDS
## Data
- 출처 : 한국관광 데이터랩, TOUR API
- 기간 : 2021년 12월 - 2024년 2월 (계절 별)
  - 3, 4, 5월: 봄
  - 6, 7, 8월: 여름
  - 9, 10, 11월: 가을
  - 12, 1, 2월: 겨울
- 종류 :
  - 방문자 수
  - 숙박/체류 시간
  - 관광소비
  - 인기관광지
  - 소셜미디어
## Process(임시)
- 데이터 수집(TOUR API, 한국관광 데이터랩)
- 단위 기간 및 대상 도시 별 데이터를 카테고리별로 병합
- 테이블 및 테이블 관계 설정(key 컬럼 정의 및 생성)
- DB에 데이터 적재
- 컬럼명 컨벤션 정의 및 한글 컬럼명 영어로 변경
- 전처리(결측치, 중복값, 이상치 처리)
- EDA
