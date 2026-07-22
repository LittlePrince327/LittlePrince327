# 안녕하세요! 👋
저는 AI 기술을 활용하여 지속 가능한 솔루션을 개발하는 AI 엔지니어입니다. 데이터 분석부터 모델 최적화까지 다양한 프로젝트를 통해 경험을 쌓았으며, AI와 머신러닝 기술로 복잡한 문제를 해결하는 데 중점을 두고 있습니다.

## 📚 프로젝트 경험

### 콜센터 STT 품질 검증 프로젝트 (CER 0.0761, 2025.03 - 2025.05)
- **설명**: 콜센터 음성의 포맷 편차와 장문 전사 문제를 개선하기 위해 Whisper 모델군 비교, 도메인 파인튜닝, CER 기반 오류 분석과 후처리 파이프라인 실험을 수행했습니다.
- **성과**: 992개 음성 샘플에서 Whisper 6종을 비교해 Large v3 Turbo 평균 CER 0.0889를 확인했으며, 후처리 포함 최저 CER 0.0761을 기록했습니다. 모델 원본 출력 기준 최적 설정은 `lr=3.16e-6`, `4 epochs`, `linear scheduler`, `16kHz`입니다.
- **기술**: Python, PyTorch, Hugging Face Transformers, Whisper, CER, LoRA/PEFT, Google Colab
- **추후 과제**: 독립 평가셋 재검증, WER 병행 측정, 운영 환경 연동 및 배포
- **공개 범위**: 회사 내부 데이터와 원본 코드는 공개하지 않습니다.
- [검증 요약 문서](./docs/STT_WhisperLargeV3Turbo_검증요약_최종(0.0761)_20250529.md)

### 금융 플랫폼 프로젝트 (2024.07 - 2024.10)
- **설명**: 사용자에게 자산 관리와 경제 관련 정보를 제공하는 AI 기반 금융 챗봇을 성공적으로 구축했습니다.
- **성과**: Kf-DeBERTa 기반 의도 분류 모델에서 Accuracy 0.90과 F1 0.90을 기록했으며, 문장 생성 모델의 유창성은 8/10점으로 평가했습니다. 주가 예측은 자산·모델별 MSE, RMSE, MAE, R² 평가표를 기준으로 비교했습니다.
- **기술**: KcBERT, Kf-DeBERTa, GPT2NMHeadModel, RAG, STT&TTS, Entity extraction
- [[프로젝트 리포지토리](https://github.com/LittlePrince327/AICC_MyAssetPlan.git)]

### 비속어 필터링 챗팅 프로젝트 (2023.10 - 2023.12)
- **설명**: 소셜 미디어에서 비속어를 탐지하고 대체하는 시스템으로, 온라인 커뮤니티의 건전성을 강화했습니다.
- **성과**: 비속어 필터링 성능을 93%까지 향상하고, BLEU 스코어 73점을 달성했습니다.
- **기술**: KcELECTRA, RNN, LSTM
- [[프로젝트 리포지토리](https://github.com/LittlePrince327/X_filter.git)]

### 전통주 추천 알고리즘 프로젝트 (2023.08)
- **설명**: 사용자 취향에 맞는 전통주를 추천하는 시스템을 구축했습니다.
- **성과**: 85%의 추천 정확도를 달성했습니다.
- **기술**: 협업 필터링, KNN, 코사인 유사도, 유클리드 유사도
- [[프로젝트 리포지토리](https://github.com/eunsol1023/Idle_cloud.git)]

## 🛠️ 기술 스택
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-%235835CC.svg?style=flat-square)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-%235835CC.svg?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-%235835CC.svg?style=flat-square)
![Chatbot](https://img.shields.io/badge/Chatbot-%23FFDD44.svg?style=flat-square)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-%2332CD32.svg?style=flat-square)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-%234B0082.svg?style=flat-square)

## 🏆 My Baekjoon
[![백준 레벨](https://mazassumnida.wtf/api/v2/generate_badge?boj=tkdgml5717)](https://solved.ac/profile/tkdgml5717)

  
## 🏆 자격증
- **SQLD** (2025년)
- **ADsP** (2024년)
- **프롬프트엔지니어 2급**
- **AI 상식**
- **MS Word 2010(Expert, 한글)** (2018)
- **MS PowerPoint 2010 (한글)** (2018)
- **컴퓨터 활용 능력 2급** (2021)


## 🏆 수상
- 비속어 필터링 Kaggle 상위 8%
  - [캐글 비속어 필터링 콘테스트 (GitHub)](https://github.com/YukyungShim/Competition/tree/main/01_Korean%20Hate%20Speech%20Detection)  
  - [캐글 비속어 필터링 콘테스트 (Kaggle)](https://www.kaggle.com/competitions/korean-hate-speech-detection)

![Kaggle Contest Reward](https://github.com/LittlePrince327/LittlePrince327/blob/main/picture/kaggle_contest_reward.png?raw=true)

- 재난 트윗 분류 Kaggle 상위 7%

  - [캐글 자연어 처리 콘테스트 (Kaggle)](https://www.kaggle.com/competitions/nlp-getting-started/overview)  
  - [캐글 자연어 처리 코드 (GitHub)](링크를 추후 업데이트 예정)

![NLP with Disaster Tweets](https://github.com/LittlePrince327/LittlePrince327/blob/main/picture/Natural%20Language%20Processing%20with%20Disaster%20Tweets.png)

## 📫 연락처
- **이메일**: tkdgml571728@gmail.com
- **Instagram**: [isaac_5717](https://www.instagram.com/isaac_5717/)
- **노션**: [노션 링크](https://plausible-sedum-d7d.notion.site/a0fade69cdbc4bc7897c891024a79794?pvs=4)
