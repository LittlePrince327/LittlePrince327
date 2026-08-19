# 박상희 · AI Engineer

**Email** · tkdgml571728@gmail.com  
**GitHub** · https://github.com/LittlePrince327

> 공개 GitHub용 요약 이력서입니다. 전화번호 등 불필요한 개인정보는 포함하지 않습니다.

## Professional Summary

데이터 품질과 평가 기준을 통제하고, 모델 성능 검증 결과를 API·DB·서비스 실행 환경까지 연결해 온 AI 엔지니어입니다. 콜센터 STT 품질 검증, 오픈소스 LLM 상담 요약·품질 평가 벤치마크, 금융 AI 챗봇, 비속어 탐지·순화 프로젝트, AI 위험성평가 백엔드를 수행했습니다.

## Experience

### 씨넷테크놀로지 · AI 엔지니어 인턴
**2025.03 ~ 2025.05**

- 콜센터 도메인 STT 검증: Whisper 모델 비교·Full fine-tuning·후처리 파이프라인 설계
- 원본 음성 1,000건 청취·검수, 무음 8건 제외 후 992개 유효 평가 샘플 확정
- Whisper 기본 모델 6종 비교에서 Large v3 Turbo 평균 CER **0.0889** 확인
- Full fine-tuning 원본 출력 **0.1756**, 별도 설정의 후처리 포함 결과 **0.0761**을 서로 다른 평가 조건으로 구분 관리
- 오픈소스 LLM 테스트 기록 26개 정리, 완전한 3단계 출력과 8개 평가 결과가 확보된 12개 모델 상세 비교
- 프로젝트 자체 기준 240점 평가에서 **230/240 공동 최고 3개 모델**을 상위 후보군으로 도출

### 동신대학교 학생생활관 · 사원
**2020.02 ~ 2021.10**

- 학생생활관 행정 업무 담당

## Skills

- **Languages / Data** · Python · SQL · pandas · NumPy
- **AI / ML** · PyTorch · Hugging Face Transformers · Whisper · KF-DeBERTa · KcBERT · KcELECTRA · scikit-learn
- **LLM / NLP** · GGUF · OpenAI API · SentenceTransformer · FAISS · Prompt Engineering · LoRA/PEFT
- **Backend / DB** · FastAPI · Pydantic · PostgreSQL · MariaDB · AWS RDS
- **Infra / Deployment** · Git/GitHub · Linux · AWS EC2 · AWS S3 · Nginx · Uvicorn · systemd · GitHub Actions

## Projects

### MAP · Financial AI Chatbot
**2024.07 ~ 2024.10 · AI 파트장**

- KF-DeBERTa 기반 재무·주식·FAQ 의도 분류
- Accuracy **0.90** · Precision **0.91** · Recall **0.90** · F1 **0.90**
- Naver News API → PageRank → SentenceTransformer → FAISS → GPT2LMHeadModel 답변 생성 흐름 구현

### X-filter · SNS Profanity Detection & Replacement
**2023.10 ~ 2023.12**

- KcBERT·KcELECTRA·RandomForest·Logistic Regression 비교
- 저장된 KcBERT 평가 혼동행렬 재계산 기준: Accuracy **0.9648** · Precision **0.9651** · Recall **0.9709** · F1 **0.9680**
- 소수 둘째 자리 표기: **0.96 / 0.97 / 0.97 / 0.97**
- 사전 기반 치환 및 RNN·LSTM 대체 문장 생성 실험
- 과거 문서의 **BLEU 73**은 최종 원시 예측·참조 문장과 평가 로그 재확보 후 재평가가 필요한 과거 기록으로 관리
- Django REST API 엔드포인트 골격 구현

### CLEAR · AI Risk Assessment Service
**2025.11 ~ 2025.12**

- OpenAI Responses API 기반 이미지+텍스트 위험성평가 초안 생성
- FastAPI `/assess` 및 사용자 선택 결과 저장 흐름 구현
- PostgreSQL(RDS) · S3 private 이미지 · EC2 연동
- Nginx · Uvicorn · systemd 실행 환경 및 GitHub Actions main 브랜치 자동 배포 구성
- AI가 최종 판단을 대신하지 않는 **위험성평가 자료 작성 지원 서비스**로 범위를 명확히 구분

## Certifications & Competitions

- 빅데이터분석기사
- SQLD (SQL 개발자)
- ADsP (데이터분석 준전문가)
- 프롬프트엔지니어 2급
- Kaggle Korean Hate Speech Detection · Top 8%
- Kaggle Natural Language Processing with Disaster Tweets · Top 7%

## Education

- 한국방송통신대학교 통계·데이터과학과 · 재학 · 2026.03 ~
- 코드랩아카데미 AICC 2기 · 수료 · 2024.04 ~ 2024.10
- 인공지능사관학교 4기 · 수료 · 2023.06 ~ 2023.12
- 동신대학교 사회복지학과 · 학사 · 2014.03 ~ 2020.02
