# 이카운트 ERP 연동 GCP 데이터 파이프라인 및 AI 업무 자동화 시스템 구축 — 제안 분석 로그

> 생성일: 2026-03-13
> 공고 URL: https://www.wishket.com/project/153473/

## 1. 공고 파싱 결과

```yaml
job:
  title: "이카운트 ERP 연동 GCP 데이터 파이프라인 및 AI 업무 자동화 시스템 구축"
  category: "개발/디자인/기획 — 웹/안드로이드/iOS/기타"
  budget_range: "40,000,000원 (조율 가능)"
  duration: "90일 (조율 가능)"
  tech_stack: [GCP, BigQuery, Cloud Functions, Google Gemini AI API, AppSheet, Looker Studio, Google Workspace, 이카운트 ERP Open API, Python, Node.js]
  description: "50명 규모 중소 무역회사. 이카운트 ERP → GCP BigQuery 데이터 파이프라인 구축 후 AI 무역 서류 자동 생성, AppSheet 입출고 앱, Looker Studio 대시보드 도입"
  requirements:
    - 이카운트 ERP Open API 연동 및 데이터 추출/정제
    - GCP BigQuery 데이터 웨어하우스 구축
    - Gemini AI 무역 서류(Invoice, Packing List) 자동 생성
    - AppSheet 현장 입출고 모바일 앱
    - Looker Studio 경영 대시보드 + 보고서 자동화
  client_questions: []
  deadline: "2026-03-25"
  job_post_url: "https://www.wishket.com/project/153473/"
  urls: []
  images: []
```

## 2. URL/이미지 분석

참고 URL/이미지 없음 — 해당 단계 건너뜀.

## 3. 실현 가능성 분석 (내부용)

- **프로젝트 유형**: API + 외부 연동 (이카운트 ERP) + 클라우드 인프라 → "결제/인증/외부 API 연동" = 조건부 가능
- **기본 공수**: 55 M/D (AI 보조 없이)
  - 기획/설계: 5 M/D
  - ERP 데이터 파이프라인: 16 M/D
  - AI 서류 자동화: 14 M/D
  - AppSheet 앱: 8 M/D
  - Looker Studio 대시보드: 7 M/D
  - QA/배포: 5 M/D
- **AI 반영 공수**: 55 × 0.50 = 27.5 → 28 M/D
- **버퍼 +15%**: 28 × 1.15 = 32.2 → 32 M/D
- **달력 일수**: 32 ÷ 1 × (7/5) = 45일
- **클라이언트 예상 기간 vs 산정 기간**: 90일 vs 45일
- **판정**: 산정 기간 ≤ 클라이언트 예상 기간 → 클라이언트 기간 그대로 사용 (90일)

## 4. 포트폴리오 매칭

| 프로젝트 | 매칭 점수 | 근거 |
|---------|----------|------|
| **Series B** | 90/100 | AI 보고서 자동 생성(ChatGPT), 대규모 데이터 처리, 대시보드, 외부 API 연동(VICS, NICE KYC) |
| **EZ-Approve** | 80/100 | B2B 기업 업무 자동화, 12개 외부 서비스 연동, 역할 기반 접근 제어 |
| **Harmony Link** | 75/100 | AI 데이터 분석(OpenAI), 멀티플랫폼 관리 시스템, 클라우드 인프라 자동화(AWS CDK) |

## 5. 최종 제안 요약

- **지원 금액**: 36,000,000원 (VAT 별도) — 클라이언트 예상 금액 40,000,000원의 90%
- **지원 기간**: 90일
- **핵심 제안 포인트**:
  1. AI 문서 자동 생성 경험 (Series B에서 ChatGPT 연동 투자심사보고서 자동 생성)
  2. 다수 외부 API 연동 경험 (EZ-Approve 12개 서비스, Series B VICS/NICE)
  3. AI 데이터 분석 + 멀티플랫폼 관리 시스템 구축 경험 (Harmony Link)
  4. Google Cloud 생태계 네이티브 통합 설계
  5. 단계별 마일스톤 (1개월 ERP 연동, 2개월 시연, 3개월 오픈)

## 6. 최종 산출물 (8단계 출력 전문)

### 제안서 사이트 URL
https://proposal-ecount-erp-gcp-pipeline.pages.dev/

### 지원 금액
36,000,000원

### 지원 기간
90일

### 클라이언트 질문 답변
해당 없음 (클라이언트 질문 없음)

### 지원 내용

안녕하세요, 이카운트 ERP 연동 GCP 데이터 파이프라인 및 AI 업무 자동화 시스템 구축 프로젝트에 지원합니다.

본 프로젝트에 대한 상세 제안서(견적서, 공수계산서, PRD, 일정, 포트폴리오)를 별도 페이지로 준비하였습니다. 아래 링크에서 확인해 주시면 감사하겠습니다.
▶ 제안서 상세 페이지: https://proposal-ecount-erp-gcp-pipeline.pages.dev/
▶ 위시켓 포트폴리오: https://www.wishket.com/partners/p/blueverse1/

---

<프로젝트 진행 제안>

■ 프로젝트 분석
50명 규모 중소 무역회사에서 이카운트 ERP 데이터를 GCP BigQuery로 실시간 이관하고, Gemini AI 기반 무역 서류 자동 생성, AppSheet 현장 입출고 앱, Looker Studio 경영 대시보드를 구축하는 1단계 업무 자동화 프로젝트로 파악하였습니다. 서류 작성 시간 40% 단축, 주간 보고서 10분 이내 생성이 핵심 목표이며, Google Cloud 생태계를 중심으로 각 서비스 간 네이티브 연동이 핵심입니다.

■ 작업 일정

[Phase 1: 기획/설계 + ERP 데이터 연동] Day 1-30
- 시스템 아키텍처 설계, 데이터 모델링
- 이카운트 ERP Open API 연동 및 인증 토큰 관리
- BigQuery 데이터 웨어하우스 구축 및 스키마 최적화
- 데이터 파이프라인 안정화 (배치/실시간 추출, 에러 모니터링)

[Phase 2: AI 서류 자동화 + AppSheet 앱] Day 31-60
- Gemini AI 연동 무역 서류(Invoice, Packing List) 자동 생성
- 다국어 번역, 국가별 양식 템플릿, Google Docs/PDF 변환
- AppSheet 기반 현장 입출고 모바일 앱 개발
- BigQuery/ERP 실시간 연동

[Phase 3: 대시보드 + 통합] Day 61-80
- Looker Studio 경영 대시보드 구축 (매출, 재고, 수출입 현황)
- 주간/월간 보고서 자동 생성 및 이메일 발송
- 부서별/직급별 권한 제어 및 데이터 보안 설정
- 전체 시스템 통합 시연

[Phase 4: QA/배포/문서화] Day 81-90
- 통합 테스트, 무역/물류팀 실무진 테스트 피드백 반영
- 운영 매뉴얼 및 API 명세서 작성
- 최종 오픈 및 인수인계

■ 마일스톤 및 산출물
- M1 (Day 30): 이카운트 ERP → BigQuery 데이터 연동 완료
- M2 (Day 60): AI 서류 자동 생성 데모 + AppSheet 입출고 앱 베타
- M3 (Day 80): 전체 시스템 시연 (대시보드 + 앱 + AI 서류)
- M4 (Day 90): 최종 오픈, 운영 매뉴얼 납품, 인수인계

■ 미팅 시 협의 필요 사항
- 이카운트 ERP Open API 접근 권한 및 사용 가능한 데이터 항목 확인
- 기존 무역 서류(Invoice, Packing List) 양식 및 주간 보고서 엑셀 파일 공유
- GCP 프로젝트 계정 생성 및 권한 설정 방식
- Gemini AI API 사용량 및 비용 한도 협의
- AppSheet 라이선스 및 사용자 수 확인
- 2단계 확장 범위 사전 논의 (회계, 경영지원 부서)

---

<유사 프로젝트 진행 경험>

▶ Series B — 투자조합 관리 올인원 플랫폼 (14개월)
- 프로젝트 유형: B2B SaaS / 핀테크 / 업무자동화
- 핵심 기능: AI 투자심사보고서 자동 생성(ChatGPT), VICS 규제 보고 자동화, 전자결재, 80+ 엔티티 대시보드
- 유사점: AI 기반 문서 자동 생성 경험, 대규모 데이터 처리 및 대시보드, 다수 외부 API 연동
- 기술 스택: Next.js, NestJS, MySQL, ChatGPT API, AWS

▶ EZ-Approve — 전자결재 업무 관리 플랫폼 (9주)
- 프로젝트 유형: B2B SaaS / 기업용 소프트웨어
- 핵심 기능: 8종 결재 워크플로우, 120-150 API, 7종 역할 권한 제어, 12개 외부 서비스 연동
- 유사점: 기업 업무 자동화 시스템, 다수 외부 API 연동, 역할 기반 접근 제어
- 기술 스택: Next.js, NestJS, MySQL, Docker, Firebase

▶ Harmony Link — 시니어 주간보호 관리 플랫폼 (6개월)
- 프로젝트 유형: B2B SaaS / 헬스케어 / 멀티플랫폼
- 핵심 기능: AI 건강 데이터 분석(OpenAI), 140+ API, 6개 플랫폼 지원, AWS CDK 인프라 자동화
- 유사점: AI 데이터 분석 연동, 멀티플랫폼 관리 시스템, 클라우드 인프라 자동화
- 기술 스택: Flutter, NestJS, Next.js, OpenAI API, AWS CDK

---

<사용 기술과 툴>

▶ 개발 기술
- 클라우드: Google Cloud Platform (BigQuery, Cloud Functions, Cloud Scheduler)
- AI: Google Gemini AI API
- 프론트엔드: AppSheet, Looker Studio, Google Workspace
- 백엔드: Python, Node.js
- 연동: 이카운트 ERP Open API, Google Sheets API, Google Drive API

▶ 개발 도구 및 인프라
- 버전 관리: GitHub
- CI/CD: GitHub Actions
- 클라우드: Google Cloud Platform
- 모니터링: Cloud Monitoring, Cloud Logging

▶ 커뮤니케이션
- 일일 진행 공유: Slack 또는 카카오톡
- 주간 미팅: Zoom / Google Meet
- 문서 공유: Notion 또는 Google Docs
- 이슈 트래킹: GitHub Issues

### 관련 포트폴리오 추천
1. **Series B** — AI 보고서 자동 생성, 대규모 데이터 대시보드, 외부 API 연동 경험
2. **EZ-Approve** — 기업 업무 자동화, 다수 API 연동, 역할 기반 권한 제어
3. **Harmony Link** — AI 데이터 분석, 멀티플랫폼 관리 시스템, 클라우드 인프라 자동화
