# 📊 YouTube Trending Analysis

유튜브 인기 영상 데이터를 자동으로 수집하고, 다양한 관점에서 분석 및 시각화하여 트렌드를 파악하는 데이터 분석 프로젝트입니다.

## 🎯 목표 (Objective)

- YouTube Data API를 활용해 인기 영상을 국가별로 수집
- 조회수, 좋아요, 카테고리, 업로드 시간 등 다양한 지표를 분석
- 데이터 기반의 인사이트를 도출하고 시각화
- 자동화된 데이터 수집 및 대시보드 제공 (선택 사항)

## 🗂️ 폴더 구조

``` 
youtube-trending-analysis/ 
├── data/ # 수집된 데이터 
│├── raw/ # 원본 데이터 
│└── processed/ # 전처리된 데이터 
├── notebooks/ # 분석용 노트북 
├── scripts/ # 주요 기능 스크립트 
├── dashboard/ # 시각화 대시보드 (선택) 
├── scheduler/ # 자동화 스크립트 
├── utils/ # 공통 유틸리티 
├── config/ # 환경 설정 
├── .env # 환경변수(API 키 등) 
├── requirements.txt # 의존성 패키지 
└── README.md # 프로젝트 설명 문서
``` 


## 🧰 사용 기술 (Tech Stack)

- Python (3.10+)
- YouTube Data API
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Jupyter Notebook
- Streamlit or Dash (선택)
- APScheduler / schedule (자동화)

## 🚀 실행 방법 (How to Run)

1. 저장소 클론
    ```bash
    git clone https://github.com/kiwissyy/youtube-trending-analysis.git
    cd youtube-trending-analysis
    ```

2. 가상환경 설치 및 패키지 설치
    ```bash
    python -m venv venv
    venv\\Scripts\\activate  # 윈도우 기준
    pip install -r requirements.txt
    ```

3. `.env` 파일 생성
    ```env
    YOUTUBE_API_KEY=your_api_key_here
    ```

4. 데이터 수집 실행
    ```bash
    python scripts/fetch_data.py
    ```

## 📊 주요 기능 (Features)

- [ ] 국가별 인기 영상 수집
- [ ] 카테고리 및 시간대별 분석
- [ ] 시각화 차트 생성
- [ ] 자동화 수집 및 업데이트
- [ ] 대시보드 UI 제공 (예정)

## 📌 진행 현황 (Project Status)

- ⏳ 초기 기획 및 설계 완료
- 🛠 데이터 수집 기능 구현 중
- 📈 분석 및 시각화 예정

## 📄 라이선스

MIT License

## 🙌 기여 & 문의

- 질문 및 피드백은 언제든지 [Issues]에 남겨주세요!