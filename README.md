# MSA 기반 SurveyPulse 게이트웨이 서비스

SurveyPulse 플랫폼의 모든 마이크로서비스 앞단에서 API 요청을 라우팅하고 공통 관리를 담당하는 게이트웨이 서비스입니다. 인증, 로깅, 라우팅, 장애 격리 등을 중앙에서 처리합니다.

## 주요 기능

- **API 라우팅**
  - `/api/users/**` → User Service
  - `/api/surveys/**` → Survey Service
  - `/api/responses/**` → Response Service
  - `/api/reports/**` → Report Service
  - `/api/advertisements/**` → Advertise Service

## 기술 스펙
- **서비스 디스커버리**: Spring Cloud Discovery 
