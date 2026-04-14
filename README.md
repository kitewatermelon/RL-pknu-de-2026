# RL-pknu-de-2026
국립부경대학교 2026 데이터공학과 석사 과정 강화 학습 코드 레포지토리

## 환경 세팅

### 요구사항
- [uv](https://docs.astral.sh/uv/getting-started/installation/) 설치 필요

### 설치

```bash
git clone https://github.com/your-org/RL-pknu-de-2026.git
cd RL-pknu-de-2026

uv sync
source .venv/bin/activate  # Windows: .venv\Scripts\activate
uv run chapter2/2_1.py # 실행 방법
```

### 실행 확인

```bash
python -c "import gymnasium; print(gymnasium.__version__)"
```