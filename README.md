# DeepLearningPJ

딥러닝 기반 데이터 분석 및 예측 모델 프로젝트 저장소입니다.

## 폴더 구조

```text
DeepLearningPJ/
├── data/
│   ├── raw/          # 원본 데이터 (수정 금지)
│   └── processed/    # 전처리 완료 데이터
├── notebooks/        # 탐색적 데이터 분석(EDA) 및 실험 노트북
├── src/              # 전처리·모델·학습·평가 파이썬 모듈
├── outputs/
│   ├── figures/      # EDA 및 평가 결과 시각화 그래프
│   └── models/       # 학습된 모델 가중치 (Git 제외)
├── docs/             # 보고서 및 프로젝트 문서
├── requirements.txt  # 파이썬 패키지 의존성
└── .gitignore
```

## 환경 설정

```bash
python -m venv .venv
# Windows (PowerShell)
.venv\Scripts\Activate.ps1

pip install -r requirements.txt
```

> GPU(CUDA) 환경의 PyTorch는 [PyTorch 공식 안내](https://pytorch.org/get-started/locally/)에 맞춰 설치하세요.
