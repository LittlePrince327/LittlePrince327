# 박상희 · AI Engineer Portfolio

> 공개 GitHub에서 확인 가능한 채용용 포트폴리오 인덱스입니다. 회사 원본 데이터·고객정보·내부 코드처럼 공개하면 안 되는 자료는 제외하고, 검증 가능한 범위와 근거를 중심으로 정리했습니다.

## 1. 콜센터 STT 품질 검증 및 후처리 개선

**씨넷테크놀로지 · AI 엔지니어 인턴 · 2025.03 ~ 2025.05**

- 원본 음성 **1,000건** 청취·검수
- 무음 **8건 제외 → 992개 유효 평가 샘플** 확정
- PCM/WAV 입력 사양 확인 및 **16kHz · mono · 16-bit WAV** 통일
- Whisper 기본 모델 **6종** 비교
- Large v3 Turbo 기본 모델 평균 CER **0.0889**
- Full fine-tuning 원본 출력 평균 CER **0.1756**
- 별도 설정의 세그먼트 병합·텍스트 정규화 후처리 포함 결과 **0.0761**
- 세 값은 같은 설정의 순차 개선값이 아니라 **서로 다른 평가 조건**으로 구분

[STT 검증 요약](./STT_WhisperLargeV3Turbo_검증요약_최종(0.0761)_20250529.md)

---

## 2. LLM 상담 요약·품질 평가 벤치마크

**씨넷테크놀로지 · AI 엔지니어 인턴 · 2025.03 ~ 2025.05**

- 상담 데이터 활용 아이디어 **7개 기획**
- 동일 상담 예시 **1건** + 동일 **3단계 프롬프트** 적용
- 양자화 버전·미완료 실행을 포함한 **26개 테스트 기록** 정리
- 완전한 결과가 확보된 **12개 모델** 상세 비교
- 프로젝트 자체 기준 **8개 항목 × 30점 = 240점**
- **230/240 공동 최고 3개 모델**을 상위 후보군으로 도출
- 단일 운영 모델 확정이나 공인 벤치마크 성과로 표현하지 않음

[LLM 벤치마크 검증 요약](./LLM_상담평가_벤치마크_검증요약.md)

---

## 3. MAP · Financial AI Chatbot

**2024.07 ~ 2024.10 · AI 파트장**

- KF-DeBERTa 기반 재무·주식·FAQ 의도 분류
- Accuracy **0.90** · Precision **0.91** · Recall **0.90** · F1 **0.90**
- 날짜·지출·소득·투자자산 등 엔터티 추출 및 의도별 라우팅
- `Naver News API → PageRank → SentenceTransformer → FAISS → GPT2LMHeadModel` 답변 생성 흐름 구현
- 브라우저 Web Speech API 기반 STT/TTS 연동

[MAP Repository](https://github.com/LittlePrince327/AICC_MyAssetPlan)

---

## 4. X-filter · SNS Profanity Detection & Replacement

**2023.10 ~ 2023.12**

- KcBERT·KcELECTRA·RandomForest·Logistic Regression 비교
- 저장된 KcBERT 혼동행렬 재계산 기준:
  - Accuracy **0.9648**
  - Precision **0.9651**
  - Recall **0.9709**
  - F1 **0.9680**
- 소수 둘째 자리: **0.96 / 0.97 / 0.97 / 0.97**
- 사전 기반 치환 및 RNN·LSTM 대체 문장 생성 실험
- **BLEU 73은 과거 프로젝트 기록**이며 원시 예측·참조·평가 로그 재확보 후 재평가 필요
- Django REST API 엔드포인트 골격 구현

[X-filter Repository](https://github.com/LittlePrince327/X_filter) · [지표 검증 문서](https://github.com/LittlePrince327/X_filter/blob/main/docs/XFILTER_METRICS.md)

---

## 5. CLEAR · AI Risk Assessment Service

**2025.11 ~ 2025.12**

- 이미지+작업 설명 기반 위험요인·현재조치·개선대책·위험수준 **초안 생성**
- OpenAI Responses API · FastAPI · Pydantic
- PostgreSQL(RDS) 저장 · S3 private 이미지 연동
- EC2 · Nginx · Uvicorn · systemd 실행 환경 구성
- GitHub Actions 기반 main 브랜치 자동 배포 흐름 구성
- 최종 위험 판단 자동화가 아닌 **위험성평가 자료 작성 지원**으로 범위 명시

[CLEAR 구현 요약](./CLEAR_AI_위험성평가_구현요약.md)

---

## 핵심 기술

`Python` · `SQL` · `PyTorch` · `Hugging Face Transformers` · `Whisper` · `KF-DeBERTa` · `KcBERT` · `FAISS` · `FastAPI` · `PostgreSQL` · `AWS RDS/S3/EC2` · `Nginx` · `Uvicorn` · `GitHub Actions`

## 함께 보기

- [GitHub Profile README](../README.md)
- [Public Resume](./RESUME.md)
- Email · tkdgml571728@gmail.com
