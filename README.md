# LimeOpt: Optimized Limestone Injection for SOx Reduction


## 👥 팀원 구성
- **이 원**: ([GitHub](https://github.com/yusongod0303))
- **이유송**: ([GitHub](https://github.com/yusongod0303))

## 📌 프로젝트 개요
배연·탈황 공정에서 석회석 주입량을 최적화하여 SOx (황산화물) 배출을 줄이는 데이터 기반 모델을 개발하였습니다. 
이 프로젝트는 발전소에서 발생하는 배기가스 내 SOx 저감을 목표로 하며, 석회석 사용량을 효과적으로 줄이면서도 환경 규제를 충족하는 최적화 방안을 제안합니다.

## 📊 데이터 분석 및 모델 개발

### 🔹 1. 데이터 탐색 (EDA)
- 총 4개의 호기 데이터를 분석 대상으로 설정
- 발전량, 석회석 주입량, In-SOx 및 Out-SOx 간 상관관계 분석
- 한 개의 호기는 결측치가 많아 신뢰성 있는 분석을 위해 제외

### 🔹 2. 데이터 전처리
- 발전량 단계별 구간화
- SOx 저감 비율 산식을 적용하여 대표값 도출
- 구간별 평균값 그래프를 통해 최적의 발전량 구간 설정

### 🔹 3. 최적화 모델 개발
- 발전량 대비 SOx 배출 특성을 반영한 최적화 알고리즘 적용
- 석회석 사용량을 약 **14% 감소**시키는 최적 모델 도출

## 📌 주요 결과
- 발전량과 석회석 주입량 간의 관계 분석을 통해 최적 투입량 도출
- 발전량 구간별 대표값을 설정하여 석회석 사용량을 최적화
- 기존 대비 **석회석 사용량 14% 절감** 효과 달성

## 🛠️ 사용 기술
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Jupyter Notebook** (EDA 및 모델 분석)
- **데이터 전처리** (결측치 처리, 구간화, 표준화)
- **최적화 알고리즘** (석회석 주입량 조정)
