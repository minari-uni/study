# 연구: 재정지원사업 고수혜 대학의 차별적 특성 (XGBoost·SHAP)
- 대상: 교육부 소관 4년제 일반대학, 본교·분교 분리
- 기간: 2018~2025 회계연도, 단위는 대학-연도
- 종속변인: 학생 1인당 일반지원 수혜액(학자금·국공립 경상비 제외, 로그)
- 독립변인: 대학알리미 공시 지표, t-1 시점으로 정렬
- 결합 키: 대학알리미 학교코드
- 폴더: data/raw(원자료, 수정 금지), data/clean, scripts, outputs
- 모든 처리는 scripts/의 Python 스크립트로 남겨 재현 가능하게 할 것

## 작업 환경
- Python: `.venv\Scripts\python.exe` (3.13)로 실행
- Git: `C:\Program Files\Git\cmd\git.exe` (셸 PATH에 없을 수 있음), 원격 `origin` = github.com/minari-uni/study
- `data/`와 `.env`는 .gitignore 대상 — 원자료는 저장소에 올리지 않음
