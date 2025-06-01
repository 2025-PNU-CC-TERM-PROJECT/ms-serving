# MS-Serving

클라우드 네이티브 마이크로서비스 기반 AI 모델 서빙 플랫폼

---

## A. 프로젝트 명
**MS-Serving**  
(Cloud-native Microservice-based AI Model Serving Platform)

## B. 프로젝트 멤버 및 담당 파트

| 이름   | 이메일                    | GitHub               | 담당 파트 |
|--------|----------------------------|----------------------|-----------|
| 이광훈 | gbhuni@gmail.com           | [@khuni1](https://github.com/khuni1) | KServe, Knative, Istio 설정 |
| 김예슬 | yesul0718@pusan.ac.kr      | [@yeseul-kim01](https://github.com/yeseul-kim01) | Spring Boot Backend, 전체 아키텍처 설계 |
| 전진혁 | aqwstn@gmail.com           | [@Jeon-Jinhyeok](https://github.com/Jeon-Jinhyeok) | Next.js Frontend, UI/UX 설계 |

## C. 프로젝트 소개

본 프로젝트는 **AI 모델을 클라우드 네이티브 환경에서 효율적으로 배포하고 서비스할 수 있는 플랫폼**을 구축하는 것을 목표로 한다.  
Kubernetes 기반 인프라 위에 KServe, Knative, Istio 등을 활용하여 확장성과 유연성을 제공한다.

## D. 프로젝트 필요성 소개

- 다양한 AI 모델 서빙 요구 증가
- 수요에 따른 오토스케일링 필요
- 안정적인 서비스 품질 보장 필요
- 마이크로서비스 아키텍처 기반 관리의 용이성

## E. 관련 기술 / 논문 / 특허 조사 내용 소개

- KServe: Model Serving용 Kubernetes Custom Resource
- Knative: Serverless Deployment 지원
- Istio: Service Mesh, Traffic Routing
- 참고 논문 및 기술 문서
    - [KServe 공식 문서](https://kserve.github.io/website/latest/)
    - [Knative Docs](https://knative.dev/docs/)
    - [Istio Docs](https://istio.io/latest/docs/)
    - 논문 예시: "Service Mesh in Kubernetes: Implementing Istio for Enhanced Observability and Security" (Pavan Nutalapati, 2022)

## F. 프로젝트 개발 결과물 소개

### 시스템 아키텍처 다이어그램

(다이어그램 이미지 첨부 예정 — `/docs/architecture.png` 또는 README에 직접 첨부 가능)

### 주요 구성 요소 - Stack Overview

| Component   | Description |
|-------------|-------------|
| KServe      | Model serving CRD (InferenceService) manager |
| Knative     | Serverless deployment of model services (scale-to-zero, auto-scaling) |
| Istio       | Ingress routing and traffic control |
| Spring Boot | Backend API for managing models |
| Next.js     | Frontend for user interface |

## G. 개발 결과물 사용하는 방법

### 설치 방법

```bash
# 1. 서브모듈까지 포함하여 전체 프로젝트 클론
git clone --recurse-submodules https://github.com/2025-PNU-CC-TERM-PROJECT/ms-serving.git

# 2. 이미 클론했다면, 서브모듈 수동 초기화
git submodule init
git submodule update
```
### 접속 방법 

## H. 개발 결과물 활용 방안


