<p align="center">
  <img src="./assets/scientific-bento.svg" alt="Chaeyeon Lee — Bioinformatics, Medical AI and Data Science. Major in Convergent Bioscience and Informatics; double major in Bio AI Convergence; Molecular Epigenomics Lab undergraduate thesis: Epigenomic Analysis of Enhancers; Biomedical AI Training Program — 미래융합교육원 × 건양대학교병원." width="800">
</p>

<p align="center">
  <a href="https://chaeiiii.github.io/index.html"><img src="https://img.shields.io/badge/VIEW%20MY%20PORTFOLIO-38536C?style=for-the-badge&logo=githubpages&logoColor=white" alt="View my portfolio"></a>
</p>

## About Me

생명정보학과 인공지능을 전공하며 유전체, 임상데이터, 의료영상 등 다양한 데이터를 분석해 왔습니다. 데이터 분석, 예측 모델링 및 AI 기술을 활용한 프로젝트를 진행하고 있으며, 데이터의 특성을 고려한 분석과 결과의 신뢰성 및 해석 가능성을 중요하게 생각합니다.

## Selected Projects

### [KIRC Genomic Prognosis](https://github.com/chaeiiii/kirc-genomic-prognosis)
*Bioinformatics · Machine Learning · Personal Project*

임상정보와 유전자 발현 데이터를 활용하여 신장암 환자의 질병 진행 위험을 예측하고, 유전자 발현 정보가 예후 예측에 추가적인 가치를 제공하는지 분석했습니다.

- TCGA-KIRC 환자 529명의 임상·RNA 데이터 통합 및 품질 검토
- 학습 데이터 기반 전처리 및 변수 선택으로 데이터 누수 방지
- CoxNet 생존분석 모델 4종 비교, 환자별 변수 기여도 분석 및 유전자 발현 유사 환자 탐색
- Streamlit 기반 환자별 예측 결과 시각화 및 추론 기능 구현

**Results & Validation:** 임상정보만 사용한 모델의 Test C-index는 0.887, RNA를 추가한 모델은 0.892였습니다. C-index는 환자별 위험도 순서의 구분 능력을 나타내는 지표입니다. 성능 차이의 신뢰구간에 0이 포함되어 명확한 개선으로 결론 내리지 않았으며, 평가 환자 80명 모두에서 일괄·개별 추론 결과의 일관성을 확인했습니다.

**Tech:** Python · Pandas · NumPy · scikit-survival · Scikit-learn · Streamlit

### HeartLink
*Medical AI · Team Project · In Progress*

심부전 환자의 퇴원 후 30일 재입원 위험을 예측하고 의료진의 퇴원 관리 및 환자 교육을 지원하는 시스템입니다.

**My Contributions**

- MIMIC-IV 임상 검사 및 약물 데이터 추출, 변수 정의와 결측률 검토
- 퇴원 이후 정보가 예측에 포함되지 않도록 데이터 추출 기준 검토
- 심부전 진료지침을 검색 가능한 단위로 구성하고 관련 근거 검색 및 재정렬 기능 구현
- 검색 근거를 활용한 대규모 언어 모델(LLM) 기반 관리 계획 생성 및 출력 검토

**Current Status:** 팀 분석 대상은 환자 4,949명, 기준 입원 8,077건입니다. 개인 담당 영역은 진료지침 검색 및 생성형 AI 기반 관리 계획과 교육 초안 개발입니다. 교육용 프로토타입으로 실제 임상 적용 및 최종 검증은 완료되지 않았습니다.

**Tech:** Python · SQL · FAISS · Hugging Face · Ollama

### Epigenomic Analysis of Enhancers
*Bioinformatics · Undergraduate Thesis · Molecular Epigenomics Lab*

인핸서는 유전자 발현을 조절하는 DNA 영역입니다. 마우스 배아줄기세포의 여러 시퀀싱 데이터를 통합해 전사인자 결합에 따른 인핸서 활성 특성을 분석했습니다.

- Linux 환경에서 시퀀싱 데이터 전처리, 참조 유전체 정렬 및 분석 영역 검출
- 염색질 접근성(ATAC-seq)과 히스톤 변형(ChIP-seq) 정보를 통합해 활성 인핸서 14,910개 식별
- 유전체 위치, 활성 신호 및 전사인자 결합 조합에 따른 인핸서 분류
- RNA 전사 활성(GRO-seq) 비교, 기존 인핸서 영역 및 무작위 대조군을 활용한 결과 검토
- 히트맵, 평균 신호 그래프 및 유전체 브라우저를 활용한 시각화

**Key Findings:** 인접 인핸서 영역을 연결하고 활성 신호 강도로 분류하는 ROSE 알고리즘을 활용했습니다. 슈퍼 인핸서(강한 활성 신호를 보이는 인핸서 영역) 374개와 일반 인핸서 10,028개를 분류했으며, 네 가지 줄기세포 관련 전사인자의 동시 결합 비율은 각각 38.2%, 4.4%였습니다. 네 인자가 모두 결합한 인핸서에서 높은 양방향 RNA 전사 활성을 관찰했습니다. 공개 데이터 기반 연관성 분석으로 인과관계는 검증하지 않았습니다.

**Tech:** Linux · Bash / Shell · Trim Galore · Bowtie2 · SAMtools · Sambamba · MACS3 · BEDTools · HOMER · deepTools · ROSE · UCSC Genome Browser

### CXR-Insight
*Medical Imaging · Deep Learning · Team Project · Private*

흉부 X-ray 영상에 딥러닝 기술을 적용한 의료영상 분류 팀 프로젝트입니다.

### [ASMR Recommender](https://github.com/chaeiiii/asmr-recommender)
*Personalization · Personal Project · In Development*

원하는 ASMR 콘텐츠를 찾기 어려웠던 경험을 바탕으로 사용자 취향과 반응을 반영하는 개인화 추천 서비스를 기획했습니다.

- 콘텐츠 유형 및 사용자 선호 정보 구조화
- 좋아요, 싫어요, 저장, 스킵 등 사용자 행동별 추천 반영 흐름 설계
- 생성형 AI 개발 도구를 활용한 웹 애플리케이션 구현

**Current Status:** 콘텐츠 기반 추천 프로토타입으로 최종 배포와 릴리스 검증은 완료되지 않았습니다.

**Project Stack:** Next.js · TypeScript · FastAPI · PostgreSQL · Docker

## Tech Stack

**Programming Languages**

데이터 추출 및 처리, 분석 코드 작성

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-38536C?style=flat-square)

**Data Analysis**

데이터 전처리 및 통합, 결측률과 데이터 품질 검토

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Machine Learning & Deep Learning**

예측 모델 학습, 생존분석, 성능 비교 및 예측 결과 해석

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![scikit-survival](https://img.shields.io/badge/scikit--survival-38536C?style=flat-square)

**Generative AI & RAG**

문서 청킹, 임베딩, 벡터 검색 및 관련도 재정렬, LLM 연동

![Hugging Face](https://img.shields.io/badge/Hugging%20Face-B28A16?style=flat-square&logo=huggingface&logoColor=white) ![FAISS](https://img.shields.io/badge/FAISS-38536C?style=flat-square) ![Ollama](https://img.shields.io/badge/Ollama-333333?style=flat-square&logo=ollama&logoColor=white)

**Bioinformatics**

시퀀싱 데이터 처리, 유전체 영역 통합, 신호 비교 및 시각화

`Trim Galore` · `Bowtie2` · `SAMtools` · `Sambamba` · `MACS3` · `BEDTools` · `deepTools` · `HOMER` · `ROSE` · `IGV` · `UCSC Genome Browser`

**Application Development**

분석 결과 대시보드 구현, API 기반 기능 연동 및 데이터베이스 활용 경험

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Development Environment & Tools**

Linux 서버 환경 분석, 개발 환경 및 코드 버전 관리

![Linux](https://img.shields.io/badge/Linux-555555?style=flat-square&logo=linux&logoColor=white) ![Bash / Shell](https://img.shields.io/badge/Bash%20%2F%20Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Conda](https://img.shields.io/badge/Conda-44A833?style=flat-square&logo=anaconda&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
