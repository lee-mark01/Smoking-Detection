# 흡연 여부 예측 모델 프로젝트

## 프로젝트 개요
건강검진 데이터를 바탕으로 개인의 흡연 여부를 예측하는 머신러닝 모델 개발 프로젝트입니다.  
로지스틱 회귀 모델을 활용하였으며, 데이터 전처리부터 모델 평가까지 전 과정을 포함합니다.

## 주요 기능
- 데이터 전처리 및 이상치 처리, 결측치 확인  
- 로그 변환 등 특성 엔지니어링  
- SMOTE를 이용한 불균형 데이터 오버샘플링  
- Logistic Regression 모델 학습 및 하이퍼파라미터 튜닝  
- 모델 성능 평가(정확도, AUC, 정밀도, 재현율, F1-score)  
- 테스트 데이터 예측 및 제출파일 생성

## 개발 환경
- Python 3.x  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn, imblearn  
- Google Colab (Nanum 폰트 설치 포함)

## 사용 방법
1. GitHub에서 `train.csv`, `test.csv` 데이터를 준비합니다.  
2. `rojiseutig-hoegwi-heubyeon-yeobu-yeceug.ipynb` 노트북을 열어 순서대로 실행합니다.  
3. 데이터 전처리, 모델 학습, 검증 결과를 확인합니다.  
4. `submission.csv` 파일이 생성되면 제출용으로 사용합니다.

## 파일 구성
- `rojiseutig-hoegwi-heubyeon-yeobu-yeceug.ipynb`: 프로젝트의 전체 분석과 모델 개발이 포함된 노트북  
- `train.csv`, `test.csv`: 학습 및 평가 데이터 (별도 준비 필요)  
- `submission.csv`: 테스트 데이터 예측 제출파일

## 모델 성능 예시
- 검증 정확도 약 74.3%  
- AUC 약 0.80  
- 상세 분류 지표 리포트 제공

## 향후 개선 방향
- 추가적 특성 엔지니어링  
- 다양한 모델 실험 및 앙상블 기법 도입  
- 하이퍼파라미터 튜닝 고도화  
- 외부 데이터 통합 및 비지도 학습 연구

---

본 프로젝트는 머신러닝 기반 건강 데이터 분석에 관심 있는 분들께 유용한 참고자료가 될 것입니다.
