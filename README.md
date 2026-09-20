# SubTriage AI - Iyuno AI Agent Engineer Portfolio
> **Iyuno AI Agent Engineer (JR101122) 채용공고 기반 과제 구현 저장소**  
> 작성자: 김태현 (첨단 IT학부 / 20211701)

---

## 1. 채용공고 요구사항 매핑 (Job Requirement Mapping)

| 채용공고 요구사항 | 프로젝트 구현 내용 및 파일 위치 |
| :--- | :--- |
| **LLM 기반 AI Agent 설계·개발** | `src/agent.py` - 다단계 워크플로우 Router 및 Agent 구현 |
| **RAG 검색·응답 시스템** | `src/retriever.py` - 공개 구독 문서 Ingestion 및 Vector Search |
| **Tool Calling / API 통합** | `src/tools.py` - 구독 정보 조회 및 비용 계산 Tool 구현 |
| **평가 및 정량 지표 측정** | `evaluation/metrics.json` - 질문 30개 정량 평가 결과 |
| **Feedback Loop / 비용 개선** | 사용자의 수정 신호 기록 및 Latency/Cost 모니터링 |

---

## 2. 프로젝트 개요 (Overview)
- **주제**: 구독 내역 자동 수집 및 취향 기반 콘텐츠 추천 AI Agent
- **핵심 가치**: 파편화된 구독 서비스의 지출을 통합 관리하고, 선택 피로(결정 장애)를 해소하는 개인화 추천 제공

---

## 3. 시작하기 (Quick Start)

### 환경 설정 및 실행
```bash
git clone https://github.com/xogus1829-cpu/AI-.git
cd AI-
pip install -r requirements.txt
python main.py
