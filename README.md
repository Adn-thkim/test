# 외국인을 위한 국내 여행지 정보 제공 웹 서비스
## Languages
- MySQL
- Python
## Platform
- Jupyter
- Streamlit
- Google Analytics 4
  - Google Tag Management
- Amazon Web Service
  - Amazon EC2
  - Amazon RDS
- Github
## Data
- 출처 : TOUR API, 힌국 관광 데이터랩
- 종류 :
  - 관광 빅데이터 정보 서비스
  - 영문 관광 정보 서비스
- 기간 :
  - 계절 별 데이터 수집
  - 3, 4, 5월 : 봄
  - 6, 7, 8월 : 여름
  - 9, 10, 11월 : 가을
  - 12, 1, 2월 : 겨울
## Process
- Python을 활용하여 TOUR API에서 데이터 수집
- Python 네이밍 컨벤션 정의
- 테이블 및 테이블 관계 정의(key 정의 및 생성)
- Amazon RDS Database에 데이터 적재
- Streamlit을 활용하여 웹 페이지 제작
- Amazon Web Service EC2를 활용하여 웹 페이지 배포
- Google Analytics 4를 활용하여 고객 행동 데이터 수집 설계
- 데이터 전처리(결측치, 중복값, 이상치 처리)
- EDA
