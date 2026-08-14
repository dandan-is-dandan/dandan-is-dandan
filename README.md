# 안다은 | Cloud · Data · DevOps Engineer

> **데이터가 생성되는 순간부터 서비스가 배포되고 운영되는 과정까지 연결하는 엔지니어를 지향합니다.**

데이터 분석에서 시작해 **Azure 기반 데이터 파이프라인과 클라우드 아키텍처**를 구축해 왔으며,
현재는 **Infrastructure as Code, Docker, CI/CD**를 활용한 배포 및 운영 자동화까지 경험을 확장하고 있습니다.

단순히 하나의 Azure 서비스를 사용하는 것보다
**데이터 수집 → 처리 → 저장 → API → 서비스 → 인프라 및 배포**가 하나의 시스템으로 연결되는 구조를 설계하는 데 관심이 있습니다.

---

## 🛠 Tech Stack

### Cloud & Data

`Microsoft Azure` `Azure IoT Hub` `Event Hubs` `Stream Analytics`
`Azure Functions` `Azure SQL Database` `Azure Databricks`
`Azure Data Explorer` `Azure Blob Storage` `Azure Key Vault`

### DevOps & Infrastructure

`Git` `GitHub` `GitHub Actions` `Docker`
`Bicep` `Terraform` `Infrastructure as Code`

### Data & Development

`Python` `SQL` `Pandas` `REST API`
`Data Pipeline` `Streaming Data` `Data Analysis`

---

# 🚀 주요 프로젝트

## 01. Azure 기반 실시간 EV 배터리 이상 탐지 모니터링 시스템

**Microsoft Data School 4기 | Team Leader · Data Engineering**

EV 배터리 센서 데이터를 실시간으로 수집·처리하고
이상 탐지 결과를 Azure SQL과 웹 대시보드까지 연결한 **End-to-End 데이터 파이프라인**입니다.

### Architecture

`Python Simulator`
→ `Azure IoT Hub`
→ `Azure Stream Analytics`
→ `Azure SQL Database`
→ `Azure Functions API`
→ `Web Dashboard`

<p align="center">
  <img src="./assets/ev-architecture.png" width="850">
</p>

### 담당 역할

* 팀장 및 데이터 엔지니어 역할 수행
* EV 배터리 센서 데이터 생성 및 전처리 흐름 구성
* IoT Hub 기반 실시간 센서 데이터 수집 구조 구성
* Stream Analytics 기반 스트리밍 데이터 처리
* Azure SQL Database 테이블 및 조회 구조 설계
* Azure Functions API와 Dashboard 연동
* Bicep 기반 Azure Infrastructure as Code 구성

### Key Point

**데이터 발생부터 서비스 활용까지 이어지는 전체 데이터 흐름 설계**

[프로젝트 자세히 보기 →](PROJECT_REPOSITORY_URL)

---

## 02. STOCK CRAFT

### Azure 기반 실시간 모의주식 거래·분석 플랫폼

**Microsoft Data School 4기 | Team Leader · Cloud Architecture · Data Pipeline**

사용자 주문과 Rule-based Agent 주문이 동시에 발생하는 모의 주식시장을 구축하고,
실시간 주문·체결 데이터를 수집·처리·저장하여 거래 결과를 분석하는 Azure 기반 서비스입니다.

### Architecture

`Event Hub`
→ `Stream Analytics`
→ `Azure SQL Database`
→ `Azure Databricks`
→ `Azure Functions`
→ `Dashboard`

<p align="center">
  <img src="./assets/stockcraft-architecture.png" width="850">
</p>

### 담당 역할

* 팀장 및 전체 Cloud Architecture 설계
* Event Hub → Stream Analytics → Azure SQL 실시간 데이터 처리 구조 설계
* Azure SQL 테이블 및 데이터 저장 구조 설계
* Databricks 기반 거래 분석 파이프라인 구성
* Azure Functions API와 분석 결과 연동
* VM · Docker 기반 서비스 실행 환경 구성
* Azure 인프라 코드화 및 배포 환경 구성

### Key Point

**실시간 거래 데이터의 수집·처리·분석·서비스 연동까지 이어지는 Cloud Architecture 설계**

[프로젝트 자세히 보기 →](https://github.com/dandan-is-dandan/azure-realtime-stock-trading-platform)

---

## 03. Edge–Cloud 기반 굴착 공사현장 이상징후 감지 및 다현장 안전관리 플랫폼

**Microsoft Data School 4기 | DevOps · CI/CD · Cloud Infrastructure**

Raspberry Pi와 MPU6050을 활용해 굴착 공사현장의 기울기·진동 변화를 수집하고,
여러 현장의 데이터를 Azure Cloud와 연동하여 상태와 이상징후를 통합 관리하는 프로젝트입니다.

<p align="center">
  <img src="./assets/gapguard-architecture.png" width="850">
</p>

### 담당 역할

* Git Repository 구조 및 협업 규칙 설계
* Branch · Commit · Pull Request 전략 수립
* Docker 기반 서비스 컨테이너화
* GitHub Actions 기반 CI/CD Pipeline 구축
* Infrastructure as Code 기반 Azure Resource 관리
* Azure 서비스별 배포 환경 및 Configuration 관리
* Cloud 서비스 모니터링 및 운영 구조 구성

### Key Point

**개발 환경부터 Cloud Infrastructure와 배포까지 반복 가능한 DevOps 환경 구축**

🚧 **현재 진행 중**

[프로젝트 자세히 보기 →](PROJECT_REPOSITORY_URL)

---

# 💼 Experience

## 두우엔지니어링 | IT Intern

**2025.07 – 2025.09**

**OCR 기반 FRS 이미지 자동 판독 및 데이터 처리 프로젝트**

원자력 발전소 내진검증용 FRS 이미지의 수작업 판독 과정에서 발생하는 오류와 반복 작업을 줄이기 위한 데이터 처리 프로그램 개발에 참여했습니다.

* Python · Pandas 기반 데이터 처리 및 전처리 로직 구현
* FRS Excel 데이터 수집 및 DataFrame 기반 병합
* 결측치 · 이상치 확인 및 단위·주파수 범위 정제
* 비정형 이미지 데이터를 분석 가능한 정형 데이터로 변환
* CSV / JSON 형태 결과 데이터 저장
* 원본 데이터와 보수적 FRS Profile 비교 시각화

**`Python` `Pandas` `Data Processing` `CSV` `JSON` `Visualization`**

---

## Microsoft Data School 4기

**2026.03 – 2026.09**

Azure 기반 **Cloud · Data Engineering · DevOps** 프로젝트 수행

* Azure 기반 실시간 데이터 파이프라인 설계
* Cloud Architecture 설계
* Azure SQL · Databricks 기반 데이터 처리
* Docker · GitHub Actions 기반 배포 자동화
* Bicep / Terraform 기반 Infrastructure as Code

---

## 국립한밭대학교 빅데이터 분석 연구실

**Lab Leader | 2023.10 – 2025.01**

센서 데이터와 산업 공정 데이터를 활용한 데이터 분석 및 인공지능 모델링 연구를 수행했습니다.

* 실내 공기질 센서 데이터 전처리 및 분석
* 산업 공정 시계열 데이터 분석
* 결측치 · 이상치 처리 및 Feature Analysis
* 상관관계 분석 및 데이터 시각화
* LSTM 기반 시계열 예측 모델링
* 연구 일정 및 팀원 역할 조율
* 국내 학술대회 논문 공동저자 참여

---

# 🔬 Research

## ETRI 제지공정 전력 최적화 연구

**2024.02 – 2024.09**

제지공정의 전건조·후건조 단계에서 발생하는 스팀 사용량과 공정 데이터를 분석하여
에너지 효율 개선을 위한 데이터 기반 모니터링 방안을 연구했습니다.

* 산업 설비 시계열 데이터 전처리
* 지종 · 평량별 공정 데이터 분리 분석
* 공정 Tag와 Steam 사용량 간 상관관계 분석
* 입력 변수 선정 및 Feature Analysis
* LSTM 기반 Steam 사용량 예측
* 회수열 데이터 기반 에너지 효율 분석

**`Python` `Time Series` `LSTM` `Data Analysis` `Feature Engineering`**

---

# 📄 Publications

### 2024 · 한국통신학회 (KICS)

**멀티 센서 기반의 스마트홈 공기질 향상을 위한 모니터링 시스템**

센서 데이터를 활용한 실내 공기질 상태 분석 및 모니터링 시스템 연구

---

### 2024 · 대한전자공학회 (IEEK)

**스팀량 예측 인공지능 모델을 통한 공정의 에너지 효율 개선 모니터링 시스템**

산업 공정 시계열 데이터와 LSTM 기반 스팀 사용량 예측 및 에너지 효율 분석

---

### 2024 · 한국통신학회 (KICS)

**딥러닝 전처리 모델 및 클러스터링 분석을 활용한 주거용 건물 실시간 공기질 모니터링 플랫폼**

센서 데이터 결측치 처리와 비지도 학습을 활용한 주거 환경 공기질 패턴 분석

---

# 🎓 Education

### 국립한밭대학교 컴퓨터공학과

**2026.02 졸업**

---

# 📜 Certification

* Microsoft Certified: **Azure Data Fundamentals (DP-900)**
* **SQL 개발자 (SQLD)**
* **데이터분석준전문가 (ADsP)**

---

# 📫 Contact

**Email** · [cyma54@naver.com](mailto:cyma54@naver.com)
