# NAVI — 사내 업무지원 챗봇 (RAG 기반 검색 시스템)

## 📄 프로젝트 포트폴리오 (PDF)
아래 이미지를 클릭하면 전체 포트폴리오 PDF가 열립니다.

[![NAVI Portfolio](./navi_portfolio_cover.png)](./Project_Portfolio.pdf)

---

## 📌 프로젝트 요약
사내 규정·지침 문서가 여러 시스템에 분산되어 있어 
필요한 문서를 찾는 데 평균 **5~10분 이상** 소요되는 비효율이 존재했습니다.  

이 문제를 해결하기 위해 **세션 기반 멀티턴 RAG 구조 + Qdrant 메타데이터 필터링 + Django REST API** 기반의  
AI 문서 검색 챗봇 **NAVI**를 개발했습니다.

이 시스템을 통해 문서 탐색 시간이 **7~10초 이하로 단축**되었고,
검색 정확도(Recall)는 **65% → 83%로 향상**되었습니다.

---

## 🛠 주요 기술 스택

**Backend / AI**
- Python, Django REST API  
- LangChain, RAG Pipeline  
- Embedding Models (KoE5, OpenAI, Upstage)

**Vector DB**
- Qdrant (Metadata Filtering 적용)

**Infra**
- AWS EC2 / RDS / S3  
- Docker, Nginx Reverse Proxy

**Frontend**
- React (Vercel)  
- Gabia Domain 연결

---

## 🖼 주요 구성 요소 미리보기

### 📌 시스템 아키텍처
![architecture](./architecture.png)

### 📌 Before → After (검색 방식 변화)
![before_after](./before_after.png)

### 📌 보안 강화 (Prompt Injection 대응)
![prompt_injection](./prompt_injection.png)

### 📌 성능 개선 지표
![performance_table](./chart.png)

---

