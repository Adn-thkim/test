# 외국인을 위한 국내 여행지 정보 제공 웹 서비스
## Languages
- MySQL
- Python
## Platform
- Jupyter
- Streamlit
- Google Analytics 4
- Google Tag Management
- Amazon EC2
- Amazon RDS
## Data
- 출처 : TOUR API
- 기간 : 2021년 12월 - 2024년 2월 (계절 별)
  - 3, 4, 5월: 봄
  - 6, 7, 8월: 여름
  - 9, 10, 11월: 가을
  - 12, 1, 2월: 겨울
## Process(임시)
- 데이터 수집(TOUR API, 한국 관광 데이터랩)
- 테이블 및 테이블 관계 설정(key 정의 및 생성)
- Amazon RDS DB에 데이터 적재
- Google Analytics 4 데이터 수집 설계
- 컨벤션 정의 및 한글 컬럼명 영어로 변경
- 전처리(결측치, 중복값, 이상치 처리)
- EDA
