<div align="center">

## 🌏 보다 나은 여행을 위해 **“BABO”**
### LLM(Gemini)을 활용한 개인화된 여행 리뷰 및 추천 마이크로서비스

</div>

---

### 🛜 배포 URL
- **[BABO Web](http://contest92.s3-website.kr.object.ncloudstorage.com/)**

### ⌛ 개발 기간  
- **2025.08 ~ 2025.10** : MVP 단기 개발  
- **2025.11 ~** : 기능 개선 중  

---

## 👥 Participants

| ![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/ohofront?v=4&h=250&w=250&fit=cover&mask=circle&maxage=7d) | ![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/3759357?v=4&h=250&w=250&fit=cover&mask=circle&maxage=7d) | ![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/2SEONGA?v=4&h=250&w=250&fit=cover&mask=circle&maxage=7d) | ![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/hongjungwook1?v=4&h=250&w=250&fit=cover&mask=circle&maxage=7d) | ![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/KKangHHee?v=4&h=250&w=250&fit=cover&mask=circle&maxage=7d) |
| :-------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------: |
| [조영호](https://github.com/ohofront) | [원승혁](https://github.com/3759357) | [이성아](https://github.com/2SEONGA) | [홍정욱](https://github.com/hongjungwook1) | [신강희](https://github.com/KKangHHee) |
| PM & FE | BE | Design & BE | BE | FE & BE |

---

## 🧑🏻‍💻 Tech Stack
<table>
<tr>
<td width="50%" valign="top">

### 🖥️ Frontend
| 구분 | 사용 기술 |
|------|------------|
| **Language & Framework** | React 19, TypeScript, Vite |
| **Styling** | Tailwind CSS |
| **State Management** | Zustand |
| **Data Fetching** | React Query |
| **UI Icons** | lucide-react |
| **Animation** | Framer Motion |
| **Routing** | React Router v7 |
| **Map API** | Naver Maps JavaScript SDK |
| **Build Tool** | Yarn 4 (Berry) |

</td>
<td width="50%" valign="top">

### 🖥️ Backend
| 구분 | 사용 기술 |
|------|------------|
| **Language & Framework** | Java 21, Spring Boot 3.5+ |
| **Build Tool** | Gradle |
| **Architecture** | Spring Cloud Gateway (MSA) |
| **Database** | PostgreSQL |
| **Caching** | Redis |
| **Messaging** | Apache Kafka |
| **Authentication / Authorization** | Spring Security, OAuth 2.0 |
| **External API Integration** | TourAPI, LLM (Gemini) |
| **Email Service** | SMTP (Google) |
| **Orchestration / Deployment** | Kubernetes |

- **Gateway**에서 JWT Filter를 처리 → 서비스별 책임 분리  
- **Redis**를 사용하여 Email 인증 처리  
- **Kafka**를 통한 비동기 데이터 처리  
- **Util Service**로 LLM 호출 서비스 분리

</td>
</tr>
</table>

---

### ☁️ Infra
| 항목 | 구성 |
|------|------|
| **Cloud Platform** | Naver Cloud |
| **Containerization** | Docker |
| **CI/CD** | GitHub Actions |
- 모든 서비스를 Docker 이미지로 빌드하여 Kubernetes 배포의 일관성 확보
- PR Merge 시 자동 빌드(Gradle) $\rightarrow$ Docker 이미지 푸시 $\rightarrow$ Kubernetes Cluster 배포까지 자동화된 파이프라인을 구축

---

## 🧩 [System Architecture](https://futuristic-lillipilli-80b.notion.site/System-Architecture-2a3c75e9a74380cd8f12cebc91a7bd43)
<img width="1132" height="988" alt="jocketdan" src="https://github.com/user-attachments/assets/676f6ec9-7cf5-4557-ac2c-f8025098b9af" />

---

<div align="center">

✨ **"Better And Beautiful Outcomes — BABO"** ✨

</div>
