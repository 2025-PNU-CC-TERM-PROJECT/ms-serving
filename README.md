# MS-Serving
> 클라우드 네이티브 마이크로서비스 기반 AI 모델 서빙 플랫폼
## 👥 Team Members

| Profile | Email | GitHub |
|:------:|:------|:--------|
| <p align="center"><img src="https://github.com/khuni1.png?size=80" width="80"/><br/><strong>이광훈</strong></p> | gbhuni@gmail.com | [@khuni1](https://github.com/khuni1) |
| <p align="center"><img src="https://github.com/yeseul-kim01.png?size=80" width="80"/><br/><strong>김예슬</strong></p> | yesul0718@pusan.ac.kr | [@yeseul-kim01](https://github.com/yeseul-kim01) |
| <p align="center"><img src="https://github.com/Jeon-Jinhyeok.png?size=80" width="80"/><br/><strong>전진혁</strong></p> | aqwstn@gmail.com | [@Jeon-Jinhyeok](https://github.com/Jeon-Jinhyeok) |

## 📦 Stack Overview

| Component   | Description |
|-------------|-------------|
| **KServe**  | Model serving CRD (InferenceService) manager |
| **Knative** | Serverless deployment of model services (scale-to-zero, auto-scaling) |
| **Istio**   | Ingress routing and traffic control |
| **Spring Boot** | Backend API for managing models |
| **Next.js** | Frontend for user interface|

## Clone this Project
```bash
# 1. 서브모듈까지 포함하여 전체 프로젝트 클론
git clone --recurse-submodules https://github.com//2025-PNU-CC-TERM-PROJECT/ms-serving.git

# 2. 이미 클론했다면, 서브모듈 수동 초기화
git submodule init
git submodule update
```


