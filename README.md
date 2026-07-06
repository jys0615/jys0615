<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=wave&color=1B2A4A&height=120&text=&animation=&fontColor=000000&fontSize=70" />
</div>

<div align="center">
  <h1>안녕하세요~ 정윤서입니다 👋</h1>
  <h3>💻 AI를 검증하는 엔지니어, 신뢰할 수 있는 AI 운영 체계를 만들어갑니다 🤖</h3>
  <p>
    LLM/Agent 평가·검증부터 신뢰성 있는 AI 운영까지,<br/>
    기준을 세우고 데이터로 증명합니다.
  </p>
</div>
<br/>

<div align="center">
  <a href="mailto:jys0615234@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/jys0615">
    <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"/>
  </a>
  <a href="https://yoonsuh.com">
    <img src="https://img.shields.io/badge/Portfolio-1B2A4A?style=for-the-badge&logo=Safari&logoColor=white"/>
  </a>
</div>

<br/>

---

## 🏢 Currently

- **AI Verification & Development Engineer** @ SureSoftTech (2026.07~)
  - AI 에이전트/LLM 검증 및 신뢰성 엔지니어링 도메인 학습 및 실무 수행 중

<br/>

---

## 🛠️ Tech Stacks

**Backend**

<div align="center">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"/>
</div>

<br/>

**AI / ML**

<div align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=LangChain&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=HuggingFace&logoColor=black"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=OpenAI&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"/>
</div>

<br/>

**Testing & Evaluation**

<div align="center">
  <img src="https://img.shields.io/badge/BERTScore-4B8BBE?style=for-the-badge&logo=Python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=Grafana&logoColor=white"/>
</div>

<br/>

**Database & Infra**

<div align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=Redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=Elasticsearch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=AmazonAWS&logoColor=white"/>
</div>

<br/>

---

## 🏆 수상 경력

| 연도 | 대회 | 수상 |
|------|------|------|
| 2025 | 경희대학교 제1회 세모톤 | 최우수상 |
| 2023 | 제4회 아름다운 사회복무요원 사랑나눔 공모전 | 우수상 |

<br/>

---

## 🚀 Projects

### 🤖 Agent KHU — AI 기반 캠퍼스 정보 통합 플랫폼
> MCP 아키텍처로 독립 서버를 통합한 AI 에이전트 | **2025.09 ~ 2025.12** | 졸업프로젝트 A+

- 6개 MCP 마이크로서비스 설계 (교실·공지·도서관·학사일정·셔틀버스 등) + FastAPI 백엔드 통합
- Elasticsearch BM25 RAG + QuestionClassifier 기반 하이브리드 라우팅 — 전체 질의의 **62%를 LLM 없이 처리**, Simple 질의 응답 100~200ms 달성
- asyncio.gather 병렬 초기화 + Tool별 차등 TTL Redis 캐싱으로 응답시간 **16.6초 → 5.5초 (67% 단축)**, 캐시 히트율 **95%** 달성
- _reconnect_lock 기반 Graceful Degradation 설계 — 세션 장애 시에도 서비스 중단 없음
- Elasticsearch Observability 파이프라인 (12개 필드 색인) + Prometheus/Grafana 커스텀 메트릭 4개 구축

`FastAPI` `MCP` `LangChain` `Elasticsearch` `PostgreSQL` `Redis` `Prometheus` `Grafana` `Docker`

---

### 🧠 Open Patient-Ψ — 오픈소스 정신건강 상담 시뮬레이션
> GPT-4 기반 환자 시뮬레이션 구조를 경량 오픈소스 모델로 재현 | **2025.04 ~ 2025.09** | KCC2025 제1저자

- CBT 기반 상담 데이터셋 **1,300개** 직접 설계·구축 (7개 상황 범주 × 3개 핵심 신념 × 6개 발화 스타일)
- QLoRA 4-bit 양자화로 Qwen2.5 0.5B/3B 파인튜닝 — 단일 GPU에서 3B 모델 학습, 메모리 사용량 **75% 절감**
- epoch × learning rate **25개 조합 자동 탐색** (grid search), BERTScore F1 기준 최적 구성 선정
- 단일 지표로는 놓칠 수 있는 응답 품질을 다각도로 검증하기 위해 **BERTScore(정량) + GPT-4.1-mini pointwise(정성) 이중 자동 평가 파이프라인** 설계 → GPT-4.1-nano 대비 우위 달성

`QLoRA` `Qwen2.5` `HuggingFace` `PyTorch` `BERTScore`

---

### 🎓 EPiC — 학번별 졸업요건 자동 진단 시스템
> 경희대 졸업요건을 LLM이 자동 분석·진단하는 AI 서비스 | **2025.03 ~ 2025.04 (원개발) / 2026.04 (리팩토링)** | 세모톤 최우수상

- FastAPI(AI 서버) + Spring Boot(BE 서버) 이기종 통합 설계 — BodyInserters.fromMultipartData()로 멀티파트 PDF 파일 파이프라인 구현
- RestTemplate → WebClient 전환 (Thread-per-request → Netty 이벤트 루프), 코드량 **50% 감소**
- Redis 3단계 차등 TTL 캐싱 + session-id 헤더 기반 세션 격리로 커리큘럼 추천 응답 **5.8초 → 0.07초 (99% 단축)**
- Nginx Gzip 압축으로 API 응답 크기 **40% 감소**
- GitHub Actions CI/CD + Docker Compose + Azure 자동 배포

`FastAPI` `Spring Boot` `Java 21` `Redis` `MongoDB` `OpenCV` `Nginx` `Docker` `Azure`

---

### 🏛️ 민들레 — 동대문구 민원 자동화 플랫폼
> 4개 서버를 하나의 트랜잭션처럼 연결하는 오케스트레이션 구조 | **2025.07 ~ 2025.08**

- Spring Boot를 단일 진입점·오케스트레이터로 설계 — 채널 분류 → AI 초안 생성 → 민원 자동 입력까지 7단계 파이프라인 순차 처리
- 단계별 즉시 DB 커밋 구조 (DB 상태 플래그 기반 이벤트) → 이기종 서버 간 **DB 정합성 100%** 확보, 재시도 시 중복 처리 방지
- HTTP → SSE 스트리밍 전환으로 GPT 초안 생성 결과를 청크 단위 실시간 전달, 타임아웃 해소

`Spring Boot` `FastAPI` `Node.js` `Next.js` `PostgreSQL`

---

### 🎤 InterV — LLM 기반 면접 생성 서비스
> AWS 인프라 기반 실서비스 품질의 면접 Q&A 생성 시스템 | **2025.03 ~ 2025.06** | 클라우드컴퓨팅 A+

- LangChain 프롬프트 템플릿 + BERTScore 기반 피드백 평가 파이프라인 구현
- cProfile로 모델 로딩 병목 진단 → 모델 캐싱 + 비동기 I/O + JSON 직렬화 최적화
- AWS EC2/RDS/S3/CloudFront 기반 배포 및 운영

`Spring Boot` `FastAPI` `LangChain` `AWS EC2/RDS/S3` `CloudFront`

---

<details>
<summary>👴 <b>SeniorSK</b> — 어르신 대상 키오스크 실전 학습 웹 (2023, 사회복무 중 단독 개발)</summary>
<br/>

튜토리얼 모드 + 실전 연습 모드 분리 설계, 실사용자 시연 반복을 통한 UI/UX 개선, 실수 복구 기능(되돌리기/재시작) 구현. 사랑나눔 공모전 우수상.

`HTML/CSS/JS`

</details>

<br/>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=wave&color=1B2A4A&height=80&section=footer" />
</div>
