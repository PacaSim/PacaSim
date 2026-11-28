<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:2563EB&height=220&section=header&text=Junhyun%20Sim&fontSize=64&fontColor=F8FAFC&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20Medical%20AI%20%C2%B7%20LLM%20Serving&descSize=20&descAlignY=58&animation=fadeIn" alt="header" />
</p>

<h3 align="center">적은 데이터로도 정확한 모델을 만들고, LLM·API 서버로 서비스에 연결합니다</h3>

<p align="center">
  <a href="mailto:junhyun919@gmail.com"><img src="https://img.shields.io/badge/Email-junhyun919%40gmail.com-0F172A?style=flat-square&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/M.S.-Kyonggi%20Univ.%20CS%20(2027.02)-2563EB?style=flat-square" />
  <!-- TODO: 포트폴리오 페이지를 만든 뒤 href="#"을 실제 주소로 바꾸세요 -->
  <a href="#"><img src="https://img.shields.io/badge/Portfolio-View-334155?style=flat-square&logo=googlechrome&logoColor=white" /></a>
</p>

---

### 👋 About

```python
class JunhyunSim:
    role       = "AI Engineer"
    education  = "경기대학교 대학원 컴퓨터과학과 석사 (2027.02 졸업 예정)"
    focus      = ["Medical Imaging", "Multimodal Learning", "PEFT", "LLM 서비스 연동"]
```

### 🏆 Highlights

| | |
|:--|:--|
| 🥇 **우수논문상** | 2026 한국인터넷정보학회 춘계학술발표대회 · 제1저자 |
| 🧬 **AI·가상융합 경진대회 우수상** | 팀장 · [시연영상](https://youtu.be/niwRdi4E6vI?si=so8QCcnozd8ES00Q) |
| 🎖️ **우수연구자상** | 경기대 ICT 안전융합인재양성센터 (2026) |
| 🦷 **MICCAI 2025 ToothFairy3** | Task 1 최종 **6위** · Dice 0.82 |

### 💼 Experience

| 기간 | 내용 |
|:--|:--|
| **2026.07 – 08** | **(주)이코모스 · 인턴** <sub>ICT 안전융합인재양성센터 인턴십</sub><br>연합학습 기반 드론 환경 모니터링<br>· 문제: 드론 하강풍에 의한 측정 왜곡, 현장 간 원천 데이터 공유 제약<br>· 해결: 원천 데이터를 공유하지 않는 **연합학습 기반 측정 보정 구조** 설계<br>· 성과: 보정 구조 설계안과 R&D 계획서를 작성해 기업에 전달 |

### 🔬 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🩺 VSC-Prompt
<sub>석사학위논문 · 2025–2026 · 단독 연구</sub>

사전학습 CLIP은 고정하고, B-mode 구조 조건과 임상 기준 설명문으로 **조건부 프롬프트**를 만들어 Strain 영상 인코더에 주입하는 유방 탄성초음파 분류 모델

- 학습 파라미터 **2.48M** · Macro AUROC **93.59%** · F1 **82.46%**
- 어텐션 융합(127.21M) 대비 파라미터 약 **1/51**, AUROC **+1.65%p**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![CLIP](https://img.shields.io/badge/CLIP-412991?style=flat-square) ![PEFT](https://img.shields.io/badge/PEFT-2563EB?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🧠 이중 모달리티 융합 · 🥇 우수논문상
<sub>산학 공동연구 · 2025–2026 · 제1저자</sub>

B-mode와 Strain을 Cross-Attention으로 서로 비교하고, 동적 게이팅으로 두 영상의 비중을 조절

- 단일 모달리티 대비 F1 **71.2% → 76.3%**
- (주)헬스허브 · 고려대 안암병원 공동연구

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Attention](https://img.shields.io/badge/Cross--Attention-334155?style=flat-square) ![Grad-CAM](https://img.shields.io/badge/Grad--CAM-64748B?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧬 돌연변이 길들이기 · 🏅 경진대회 우수상
<sub>2026.05–09 · 2인 팀 리드</sub>

음성으로 단백질 구조를 불러오는 LLM 기반 MR 과학 교육 플랫폼. 서버·LLM 연동은 직접 구현했고, 클라이언트는 팀원이 맡았습니다.

- Whisper → LLM(Solar)이 정해진 JSON 명령으로 변환 → 프록시 서버가 RCSB 구조 조회·검증
- AutoDock Vina 도킹 실험 서버 구현
- 3종 JSON 설정만으로 새 시나리오 추가

[![Repo](https://img.shields.io/badge/leecursion%2FTaming--Mutants-181717?style=flat-square&logo=github)](https://github.com/leecursion/Taming-Mutants) ![Cloudflare](https://img.shields.io/badge/Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)

</td>
<td width="50%" valign="top">

#### 🛡️ AI 유해 필터링 모임앱
<sub>전공동아리 · 2024.05–12 · 3인</sub>

모임을 만드는 순간 유해 여부를 판정해 공개 목록에서 제외. 모델 학습, FastAPI 필터링 서버, 앱 서버 연동을 맡았습니다.

- KoELECTRA(텍스트) · YOLOv5(이미지) 직접 학습
- 판정 결과를 모아 재학습하는 흐름 포함
- 2024 SW 기술대상 서류 통과

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![KoELECTRA](https://img.shields.io/badge/KoELECTRA-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![YOLOv5](https://img.shields.io/badge/YOLOv5-00FFFF?style=flat-square)

</td>
</tr>
</table>

<details>
<summary><b>📂 More Experience</b></summary>
<br>

| 프로젝트 | 내용 | 결과 |
|:--|:--|:--|
| **ToothFairy3** · MICCAI 2025 | 3D CBCT 다중 구조 분할. 데이터 전처리 · 모델 학습 · 앙상블·후처리 | Task 1 6위 · [순위표](https://toothfairy3.grand-challenge.org/challenge-winners/) |
| **관상동맥 석회화 분할** · PLOS ONE 2026 | 2.5D 다중 단면 특징 융합 (공동저자) | [DOI](https://doi.org/10.1371/journal.pone.0363737) |
| **대동맥판막 석회화 분할** · KSC 2025 | 위치 검출 후 정밀 분할하는 2단계 구조 (제1저자) | Dice 0.62 → 0.83 |
| **AI 침수 예측·재난 알림** · 2025 PBL | LSTM 침수 예측 + RAG 챗봇을 FastAPI로 통합 (팀장) | 10분 단위 위험 감지·알림 |

</details>

---

### 🛠️ Tech Stack

**AI · Model**

<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch&theme=dark" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" height="48" />
</p>

`LLM·RAG` `VLM` `Fine-tuning·PEFT` `Computer Vision` `Multimodal Learning`

**Serving · Dev**

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,flask,spring,aws,mysql,linux,git,github&theme=dark" />
</p>

---

### 📄 Publications

- Pi, S.-W., **Sim, J.-H.**, & Lee, B.-D. (2026). *Segmentation of sparse coronary artery calcifications in computed tomography via 2.5D multi-slice feature fusion.* **PLOS ONE**, 21(11), e0363737.
- **심준현**, 이병대. (2025). 심장 CT에서 대동맥판막 석회화의 자동 정량화를 위한 2단계 딥러닝 분할 프레임워크. 한국정보과학회 학술발표논문집, 654–656.
- 2026 한국인터넷정보학회 춘계학술발표대회, 어텐션 기반 이중 모달리티 융합 (제1저자, **우수논문상**)

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=PacaSim&show_icons=true&hide_border=true&theme=tokyonight&bg_color=0F172A&title_color=60A5FA&icon_color=2563EB&text_color=CBD5E1" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PacaSim&layout=compact&hide_border=true&theme=tokyonight&bg_color=0F172A&title_color=60A5FA&text_color=CBD5E1" />
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,100:0F172A&height=120&section=footer" alt="footer" />
</p>
