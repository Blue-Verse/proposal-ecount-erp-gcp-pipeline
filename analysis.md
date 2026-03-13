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

<!-- 8단계 완료 후 추가 예정 -->
