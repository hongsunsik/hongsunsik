### 안녕하세요, LLM 서비스를 만들고 운영하는 엔지니어를 준비하고 있습니다 👋

- 🎓 수학과 · 바이오나노소재 전공, 바이오헬스 인공지능 부전공
- 🔧 관심 분야: **RAG · LLM 서빙 · LLMOps(관측 · 배포 · 평가)**, 헬스케어 AI
- 📚 2026.11 ~ 모두의연구소 아이펠 LLM 엔지니어 과정

## 대표 프로젝트

### 🧬 [Bio-GPT 프로토타입](https://github.com/hongsunsik/bio-gpt-prototype)
PubMed · ClinicalTrials.gov · openFDA를 검색해 **모든 문장에 출처를 다는** 바이오 · 제약 R&D 질의응답 시스템
- 업로드 문서 RAG: 근거 검색률 **58% → 83%**, 정답률 **69% → 77%**, 출처 없는 문장 **17줄 → 0줄**
- 검색 설정 192가지 · 프롬프트 기법 6가지 비교 실험, 인용 · 숫자 · 사실 3단계 자동 검증

### ⚙️ [Local LLMOps Inference Platform](https://github.com/hongsunsik/llmops-local-inference-platform)
로컬 LLM 여러 개를 라우팅 · 폴백하고, 지표 · 트레이싱 · 배포까지 갖춘 게이트웨이
- k6 부하테스트로 단일 인스턴스 큐잉 병목 분석 (p95 **50.7s → 15.0s**, 시나리오 재설계)
- Kubernetes 캐너리 배포 실측 (stable/canary **≈ 90/10**)
- 실환경 버그 3건 해결: MLflow 3.5 Host 검증 403, Whisper OOM, 포트 충돌

## 기술 스택
`Python` `FastAPI` `LangChain` `FAISS` `Ollama` `Docker` `Kubernetes(kind)` `Prometheus` `MLflow` `k6` `GitHub Actions`
