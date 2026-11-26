<p align="center">
  <img src="./assets/scientific-bento.svg" alt="Chaeyeon Lee — Bioinformatics, Medical AI and Data Science. Major in Convergent Bioscience and Informatics; double major in Bio AI Convergence; Molecular Epigenomics Lab undergraduate thesis: Epigenomic Analysis of Enhancers; Biomedical AI Training Program — 미래융합교육원 × 건양대학교병원." width="800">
</p>

<p align="center">
  <a href="https://chaeiiii.github.io/index.html"><img src="https://img.shields.io/badge/VIEW%20MY%20PORTFOLIO-38536C?style=for-the-badge&logo=githubpages&logoColor=white" alt="View my portfolio"></a>
</p>

## About Me

생명정보학과 인공지능을 전공하며 유전체, 임상데이터, 의료영상 등 다양한 데이터를 분석해 왔습니다. 데이터 분석, 예측 모델링 및 AI 기술을 활용한 프로젝트를 진행하고 있으며, 데이터의 특성을 고려한 분석과 결과의 신뢰성 및 해석 가능성을 중요하게 생각합니다.

## Selected Projects

### HeartLink
*Medical AI · Team Project · In Progress*

심부전 환자의 30일 재입원 위험 예측 및 퇴원 관리 지원 시스템 개발

- MIMIC-IV 임상 검사 데이터 추출 및 전처리
- 심부전 진료지침 기반 RAG 검색 및 리랭킹 구현
- LLM 연동 및 생성 결과의 근거 적합성 검토

**Tech:** Python · FAISS · Hugging Face · Ollama

### [KIRC Genomic Prognosis](https://github.com/chaeiiii/kirc-genomic-prognosis)
*Bioinformatics · Machine Learning · Personal Project*

임상 및 유전자 발현 데이터를 활용한 신장암 환자의 예후 예측

- TCGA-KIRC 환자 529명의 임상·RNA 데이터 전처리 및 통합
- 생존분석 모델 개발 및 성능 비교
- 환자별 예측 기여도 분석 및 유사 환자 탐색
- Streamlit 기반 예측 결과 시각화

**Tech:** Python · Pandas · scikit-survival · Streamlit

### CXR-Insight
*Medical Imaging · Deep Learning · Team Project · Private*

흉부 X-ray 데이터를 활용한 의료영상 분석 프로젝트

### Epigenomic Analysis of Enhancers
*Bioinformatics · Undergraduate Thesis · Molecular Epigenomics Lab*

마우스 배아줄기세포의 ATAC-seq, ChIP-seq, GRO-seq 데이터를 통합하여 활성 인핸서를 식별하고, 전사인자 결합에 따른 후성유전체 특성과 전사 활성을 비교 분석했습니다.

**Key Contributions**

- Linux 환경에서 시퀀싱 데이터 전처리, mm10 참조 유전체 정렬 및 peak calling 수행
- ATAC-seq와 H3K27ac ChIP-seq 데이터 통합 및 프로모터 인접 영역 제외를 통해 활성 인핸서 14,910개 식별
- 유전체 위치, ROSE 기반 인핸서 유형 및 전사인자 결합 조합에 따른 분류
- 전사인자 결합, 히스톤 변형 및 가닥 특이적 GRO-seq 신호 비교 분석
- 기존에 알려진 인핸서 영역과 무작위 대조군을 활용한 분석 결과 검토
- Heatmap, Metaplot 및 UCSC Genome Browser를 활용한 결과 시각화

**Key Findings:** ROSE 분석에서 Super-enhancer 374개와 Typical enhancer 10,028개를 분류했습니다. 네 가지 다능성 관련 전사인자의 동시 결합 비율은 각각 38.2%와 4.4%였으며, 네 인자가 모두 결합한 인핸서에서 높은 양방향 전사 활성을 관찰했습니다. 공개 데이터 기반 연관성 분석으로, 인과관계는 검증하지 않았습니다.

**Tech:** Linux · Bash / Shell · Trim Galore · Bowtie2 · SAMtools · Sambamba · MACS3 · BEDTools · HOMER · deepTools · ROSE · UCSC Genome Browser

### [ASMR Recommender](https://github.com/chaeiiii/asmr-recommender)
*Personalization · AI-assisted Development · Personal Project*

사용자 취향과 반응 데이터를 활용한 개인화 ASMR 추천 서비스

- 사용자 선호 및 행동 데이터 기반 추천 방식 설계
- 좋아요, 싫어요, 저장, 스킵 반응을 활용한 개인화 기능 기획 및 구현
- 생성형 AI 개발 도구를 활용한 웹 애플리케이션 개발

**Project Stack:** Next.js · TypeScript · FastAPI · PostgreSQL

## Tech Stack

**Programming Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-38536C?style=flat-square)

**Data Analysis**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Machine Learning & Deep Learning**

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![scikit-survival](https://img.shields.io/badge/scikit--survival-38536C?style=flat-square)

**Generative AI & RAG**

![Hugging Face](https://img.shields.io/badge/Hugging%20Face-B28A16?style=flat-square&logo=huggingface&logoColor=white) ![FAISS](https://img.shields.io/badge/FAISS-38536C?style=flat-square) ![Ollama](https://img.shields.io/badge/Ollama-333333?style=flat-square&logo=ollama&logoColor=white)

**Bioinformatics**

`Trim Galore` · `Bowtie2` · `SAMtools` · `Sambamba` · `MACS3` · `BEDTools` · `deepTools` · `HOMER` · `ROSE` · `IGV` · `UCSC Genome Browser`

**Application Development**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Development Environment & Tools**

![Linux](https://img.shields.io/badge/Linux-555555?style=flat-square&logo=linux&logoColor=white) ![Bash / Shell](https://img.shields.io/badge/Bash%20%2F%20Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Conda](https://img.shields.io/badge/Conda-44A833?style=flat-square&logo=anaconda&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
