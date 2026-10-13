# Data & Software Portfolio

> 통계적 검증, 오류 분석, 데이터 기반 서비스 구현 경험을 정리한 포트폴리오

## Profile

심리학을 전공하고 통계학을 복수전공했습니다. Python·R·SQL을 사용해 데이터 구조를 확인하고, 비교 조건과 평가 지표를 명시해 분석 결과를 해석합니다.

KDT 팀 프로젝트에서는 번호판 OCR의 실환경 오류를 분석하고 모델을 FastAPI·Spring Boot·PostgreSQL 기반 서비스에 연결했습니다. 통계 프로젝트에서는 모델 간 성능 차이뿐 아니라 데이터 구성, 검증 방법과 해석의 한계를 함께 기록했습니다.

## Representative Projects

| 프로젝트 | 담당 내용과 결과 | 기술 |
|---|---|---|
| [CLOUDWASH — 차량번호판 OCR·세차장 운영 서비스](https://github.com/stonetiger95/kdt-teamproject-carwash) | 4인 팀의 팀장으로 OCR 데이터·모델 개발과 서비스 연동을 담당했습니다. 학습·튜닝과 분리한 실환경 번호판 Crop 1,000장에서 Lite050의 문자열 완전 일치 971건(97.1%)을 확인했습니다. | Python, PyTorch, FastAPI, Spring Boot, Vue, PostgreSQL |
| [Heart Failure Model Validation](https://github.com/stonetiger95/heart-failure-model-validation) | 심부전 임상자료에서 결과와 관련된 추적기간 변수를 제외하고 LDA·QDA·SVM·ANN을 동일한 반복 교차검증으로 비교했습니다. | R, repeated CV, ROC-AUC, sensitivity, specificity |
| [NCI-60 Gene Expression Statistics](https://github.com/stonetiger95/nci60-gene-expression-statistics) | 5개 암종의 40개 세포주와 6,830개 유전자 발현 변수를 ANOVA·BH-FDR·PCA·군집분석으로 탐색했습니다. | R, BH-FDR, PCA, clustering, bootstrap, permutation |
| [Face Impression Multivariate Analysis](https://github.com/stonetiger95/face-impression-multivariate-analysis) | 66개 얼굴 자극의 14개 인상 평정을 PCA·요인분석·군집분석으로 요약하고 방법별 잠재 구조를 비교했습니다. | R, PCA, PCFA, MLFA, clustering |
| [Statistics Mini Analyses](https://github.com/stonetiger95/statistics-mini-analyses) | 주가 시계열, 반복검정 오류, 육상 기록의 공통 차원, 범주형 자료의 연관 구조를 분석한 네 가지 사례입니다. | R, ARIMA, multiple testing, PCA/FA, correspondence analysis |

## Skills

- 데이터 분석: Python, R, SQL, SAS, statistical modeling, model validation
- 다변량·생물통계: PCA, factor analysis, clustering, classification, multiple testing
- 서비스 연동: FastAPI, Java, Spring Boot, PostgreSQL, REST API, Vue.js
- 컴퓨터 비전: PyTorch, YOLO, OCR
- 학습 중: Tableau, BigQuery

## Repository Notes

- 각 저장소의 README에 데이터 구성, 평가 범위와 한계를 기록했습니다.
- 공개할 수 없는 원본 데이터 대신 집계 결과와 민감정보를 제거한 코드를 제공합니다.
- 대표 성능 수치는 학습·튜닝 데이터와 분리한 평가 결과를 우선 사용합니다.
