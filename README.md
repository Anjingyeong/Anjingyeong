<div align="center">

# 안진경 · Jin-kyeong An

### Full-Stack Developer · AI Engineer · Automation Builder

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1200&color=38BDF8&center=true&vCenter=true&width=760&lines=Building+AI+into+working+products.;Full-stack+%C2%B7+Automation+%C2%B7+QA+%C2%B7+Deployment;From+research+to+real-world+systems.)](https://git.io/typing-svg)

[![GitHub followers](https://img.shields.io/github/followers/Anjingyeong?style=flat-square&logo=github&color=38BDF8&labelColor=0F172A)](https://github.com/Anjingyeong)
[![GitHub User's stars](https://img.shields.io/github/stars/Anjingyeong?style=flat-square&logo=github&color=FBBF24&labelColor=0F172A)](https://github.com/Anjingyeong)
[![Profile views](https://komarev.com/ghpvc/?username=Anjingyeong&style=flat-square&color=64748B)](https://github.com/Anjingyeong)

**AI를 사용하는 것보다, AI로 만든 결과가 실제로 동작하게 만드는 과정에 관심이 있습니다.**

`Idea → Build → Deploy → QA → Automate`

</div>

---

## About me

의료영상 AI와 실시간 Vision AI 프로젝트를 시작으로, 현재는 **AI를 실제 서비스로 연결하는 Full-Stack 개발과 개발 자동화**에 집중하고 있습니다.

모델 정확도만 보는 것보다 프론트엔드, 백엔드, 배포, QA, 운영까지 이어지는 전체 흐름을 직접 만들고 개선하는 것을 좋아합니다.

```text
Research / Idea
      ↓
AI · Backend
      ↓
Frontend
      ↓
Deployment
      ↓
Monitoring · QA
      ↓
Automation
```

최근에는 특히 **AI/Vibe Coding으로 빨라진 개발 속도에 맞춰 QA와 운영도 자동화할 수 있는가**를 실험하고 있습니다.

---

## Tech stack

### Application

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</div>

### AI / Computer Vision

<div align="center">

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

`YOLO · RF-DETR · VAE · LSTM · RAG · Vector Search`

</div>

### Infrastructure · QA · Automation

<div align="center">

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

`MCP · Browser Automation · CI/CD · Cloud Deployment · REST API`

</div>

---

# Featured projects

## 🎛️ [JK — AI Development Control Plane](https://github.com/Anjingyeong/jk-mcp)

> **ChatGPT가 내 개발 환경에서 실제 작업을 수행하도록 연결하는 개인용 개발 브리지 / 대시보드**

AI Coding Agent를 쓰다 보면 코드 생성 자체보다 **로컬 프로젝트 접근, 명령 실행, 승인, Git, 배포, 작업 상태 확인**이 여러 곳으로 흩어지는 문제가 생깁니다.

JK는 이 흐름을 하나로 연결하기 위해 만들고 있는 개발 인프라입니다.

```text
ChatGPT
   ↓
JK / MCP
   ├─ Workspace
   ├─ Terminal / Test
   ├─ Git
   ├─ Approval
   ├─ Dashboard
   └─ Automation
```

ChatGPT가 판단하고 JK가 실제 개발 환경에서 작업을 수행하도록 역할을 분리하고, 민감하거나 파괴적인 작업에는 승인과 안전장치를 둡니다.

**Stack**

`Node.js 22 · MCP · Custom GPT Actions · REST API · PowerShell · Git · Cloudflare · OCI`

---

## 🧪 [VibeCheck — Evidence-first QA for Vibe Coding](https://github.com/Anjingyeong/vibe_QA)

> **“AI가 코드를 빠르게 만들었다면, 누가 그 결과가 정말 동작하는지 확인할까?”**

Vibe Coding을 사용하면서 개발 속도는 크게 빨라졌지만 새로운 병목이 생겼습니다.

```text
코드는 만들어졌다.
      ↓
빌드도 성공했다.
      ↓
하지만 실제 사용자가 눌러보면 안 된다.
```

그리고 같은 LLM에게 코드를 다시 보여주며 **“문제 없어?”**라고 확인하는 것만으로는 충분하지 않았습니다.

그래서 코드를 읽고 평가하는 AI가 아니라, **실제 브라우저에서 서비스를 사용하고 증거를 수집하는 QA 시스템**을 만들기 시작했습니다.

### How it works

```text
URL
 ↓
Real browser
 ↓
Desktop / Mobile exploration
 ↓
Network · Console · Screenshot · Assertion
 ↓
Independent repeated runs
 ↓
Reproducible findings only
 ↓
QA Report
```

VibeCheck에서 AI는 버그를 **확정하지 않습니다.**

AI는 테스트 후보를 제안하는 discovery 역할만 맡고, 실제 브라우저에서 수집된 **machine-verifiable evidence와 반복 재현성**이 확보되어야 confirmed finding으로 승격됩니다.

### Why I built it

Vibe Coding의 장점은 개발 속도입니다. 하지만 개발 속도가 빨라질수록 사람이 모든 화면과 기능을 직접 확인하는 QA가 병목이 됩니다.

> **AI가 개발 속도를 높였다면, QA 역시 자동화되어야 한다.**

VibeCheck는 제가 여러 웹 서비스를 직접 만들고 배포하면서 반복해서 겪었던 **“구현은 끝났는데 실제 사용에서는 깨지는 문제”**를 자동으로 찾고 검증하기 위해 시작했습니다.

**Stack**

`Node.js 22 · Playwright · Browser Automation · Evidence-based QA · Optional LLM Discovery`

---

## 👁️ Smart Safety Monitoring

실시간 CCTV 영상에서 이상행동을 탐지하고 관제 화면까지 전달하는 AI 시스템.

```text
RTSP → Vision AI → Tracking / LSTM → MQTT → Backend → Dashboard
```

`Python · YOLO · ByteTrack · LSTM · MQTT · React`

---

## 🩺 [RF-DETR Endoscopy](https://github.com/Anjingyeong/RF-DETR-project)

대장 내시경 영상에서 용종을 실시간 탐지하고 영상 처리 결과를 실제 애플리케이션으로 연결한 의료 AI 프로젝트.

`Python · PyTorch · RF-DETR · OpenCV · PyQt5`

---

## 📚 [LLM Wiki](https://github.com/Anjingyeong/llm_wiki_strange)

프로젝트 문서를 정적 Wiki와 서버사이드 RAG 질의응답으로 연결한 지식 시스템.

`TypeScript · RAG · Vector Search · RRF`

---

## Current interests

```text
AI Coding / Vibe Coding
Developer Tools
Browser Automation & QA
Agent Infrastructure
Full-Stack Product Development
Cloud Deployment & Automation
Real-time Vision AI
```

> **Building tools that turn AI-generated code into working products.**

---

<div align="center">

<a href="https://github.com/Anjingyeong"><img height="165" src="https://github-readme-stats.vercel.app/api?username=Anjingyeong&show_icons=true&hide_border=true&bg_color=00000000&title_color=38BDF8&text_color=94A3B8&icon_color=FBBF24&rank_icon=github&include_all_commits=true" alt="Anjingyeong's GitHub statistics"></a>
<a href="https://github.com/Anjingyeong?tab=repositories"><img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anjingyeong&layout=compact&hide_border=true&bg_color=00000000&title_color=38BDF8&text_color=94A3B8&langs_count=8" alt="Anjingyeong's top languages"></a>

<br><br>

[Portfolio](https://anjingyeong.github.io/) · [GitHub](https://github.com/Anjingyeong)

</div>
