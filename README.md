# 안녕하세요, 심준현입니다 👋

**AI Engineer** · 경기대학교 대학원 컴퓨터과학과 석사 (2027.02 졸업 예정)

적은 데이터로도 정확한 모델을 만들고, LLM·API 서버로 서비스에 연결합니다.

📧 junhyun919@gmail.com

---

## 🏆 Highlights

- **SCI 공동저자**: PLOS ONE (2026), 관상동맥 석회화 2.5D 분할
- **우수논문상**: 2026 한국인터넷정보학회 춘계학술발표대회 (제1저자)
- **MICCAI 2025 ToothFairy3 챌린지**: Task 1 최종 6위 (Dice 0.82)
- **2026 AI·가상융합 경진대회 우수상**: 팀장
- **우수연구자상**: 경기대 ICT 안전융합인재양성센터 (2026)

## 🔬 Projects

### VSC-Prompt: 유방 탄성초음파 분류 (석사학위논문, 2025–2026)
- 사전학습 CLIP은 고정하고, B-mode 구조 조건과 임상 기준 설명문으로 **조건부 프롬프트**를 만들어 Strain 영상 인코더 전 층에 주입
- 학습 파라미터 **2.48M**으로 홀드아웃 **Macro AUROC 93.59% · F1 82.46%**
- 어텐션 융합 모델(127.21M) 대비 학습 파라미터는 약 1/51, AUROC는 +1.65%p
- `PyTorch` `CLIP` `PEFT` `Prompt Learning` `Multimodal`

### 이중 모달리티 융합: 유방 초음파 분류 (산학 공동연구, 2025–2026) · 🏅 우수논문상
- B-mode와 Strain을 Cross-Attention으로 서로 비교하고, 동적 게이팅으로 두 영상의 비중을 조절
- 단일 모달리티 대비 F1 **71.2% → 76.3%**
- (주)헬스허브 · 고려대 안암병원 공동연구
- `PyTorch` `Cross-Attention` `Grad-CAM`

### 돌연변이 길들이기: LLM 음성 명령 MR 과학 교육 플랫폼 (2026.05–09) · 🏅 경진대회 우수상
- 2인 팀 리드로 시나리오·교육 콘텐츠를 설계하고 서버·LLM 연동을 직접 구현했습니다. 클라이언트는 팀원이 맡았습니다.
- 음성(Whisper) → LLM(Upstage Solar)이 정해진 JSON 명령으로 변환 → 프록시 서버가 RCSB에서 구조를 조회·검증 → MR 화면에 표시
- AutoDock Vina 기반 도킹 실험 서버 구현
- 엔진 코드 수정 없이 3종 JSON 설정(구조 · 후보물질 · 퀘스트)만으로 새 시나리오 추가
- 🔗 [leecursion/Taming-Mutants](https://github.com/leecursion/Taming-Mutants)
- `LLM` `Whisper` `Cloudflare Workers` `AutoDock Vina` `Unity`

### AI 유해 필터링 모임앱 (전공동아리, 2024.05–12)
- 3인 팀에서 유해 판정 모델 학습, FastAPI 필터링 서버 구축, 앱 서버 연동을 맡았습니다.
- KoELECTRA(텍스트) · YOLOv5(이미지)로 유해 모임을 판정하고 공개 목록에서 제외, 재학습 흐름 포함
- 2024 SW 기술대상 서류 통과
- `KoELECTRA` `YOLOv5` `FastAPI`

### 그 밖의 경험
- **ToothFairy3 (MICCAI 2025)**: 3D CBCT 다중 구조 분할. 데이터 전처리, 모델 학습, 앙상블·후처리를 맡았고 Task 1 6위를 기록했습니다. [순위표](https://toothfairy3.grand-challenge.org/challenge-winners/)
- **관상동맥 석회화 분할**: 2.5D 다중 단면 특징 융합 (PLOS ONE 2026, 공동저자). [DOI](https://doi.org/10.1371/journal.pone.0363737)
- **대동맥판막 석회화 분할**: 2단계 분할로 Dice 0.62 → 0.83 (한국정보과학회 2025, 제1저자)
- **AI 침수 예측·재난 알림**: LSTM 침수 예측과 RAG 챗봇을 FastAPI로 통합 (2025 PBL, 팀장)

## 🛠 Tech Stack

**AI·모델** &nbsp; PyTorch · Hugging Face · LLM·RAG · VLM · Fine-tuning·PEFT · Computer Vision · Multimodal Learning

**서빙·개발** &nbsp; Python · FastAPI · Flask · Spring Boot · AWS · MySQL · Linux · Git·GitHub

## 📄 Publications

- Pi, S.-W., **Sim, J.-H.**, & Lee, B.-D. (2026). *Segmentation of sparse coronary artery calcifications in computed tomography via 2.5D multi-slice feature fusion.* PLOS ONE, 21(11), e0363737.
- **심준현**, 이병대. (2025). 심장 CT에서 대동맥판막 석회화의 자동 정량화를 위한 2단계 딥러닝 분할 프레임워크. 한국정보과학회 학술발표논문집, 654–656.
- 2026 한국인터넷정보학회 춘계학술발표대회, 어텐션 기반 이중 모달리티 융합 (제1저자, 우수논문상)
