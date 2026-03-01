## Syllabus

### 1. 학습 목표

--> 단순한 “앱 개발”이 아니라 AI-연계 API 중심 풀스택 실전역량을 보유하여 Application Builder로 !

1️⃣ 네트워크 + REST API 이해 및 실습, FastAPI 기반 백엔드 설계 능력 확보

2️⃣ AI 기반 API 앱 바이브코딩 + Figma–DB–Node 연계 프로젝트

### 2. 교과목 목표

- HTTP/REST 구조를 이해하고 직접 API 서버를 설계
- FastAPI 기반 비동기 백엔드를 구축
- SQLlite3 혹은 MariaDB와 연동한 데이터 중심 API를 구현
- LLM AI 서비스 앱 개발 구현
- Figma MCP → 프론트엔드 → FastAPI → DB 전체 파이프라인을 설계
- Cline AI를 활용해 설계-코딩-디버깅 자동화 워크플로우를 구축

### 반드시 개인 github를 만들어 과제를 제출하라

### 3. 교과목 일정

| 주차 | 핵심 주제              | 이론 핵심                           | 실습 내용                    | 산출물(과제)         |
| -- | ------------------ | ------------------------------- | ------------------------ | ----------- |
| 1 | ETL     | URL에서 데이터를 추출-변환-로딩, [데이터플랫폼의 진화](https://github.com/ancestor9/2026_Spring_Application_Programming/blob/main/1-1_The%20Overview%20of%20Data%20Engineering%20Ecosystem.pdf) | 파이썬 [함수](https://realpython.com/defining-your-own-python-function/), [클라스/모듈](https://realpython.com/python-classes/) 강의 및 실습 | [로켓발사 이미지 ETL](https://github.com/ancestor9/2026_Spring_Application_Programming/blob/main/%5BTask_01%5D%20API%EB%A5%BC%20%ED%99%9C%EC%9A%A9%ED%95%9C%20%EB%A1%9C%EC%BC%93%20%EB%B0%9C%EC%82%AC%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20ETL%20%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4%20%EA%B5%AC%ED%98%84.pdf), 고양이와 강아지 사진 ETL(과제)  |
| 2  | 네트워크 & 웹 구조 이해 I    | Vscode 설치, 가상환경 구현 | Postman API 호출, 패킷 흐름 분석 | API 호출 리포트  |
| 3  | 네트워크 & 웹 구조 이해 II    | Client–Server, HTTP, REST, JSON | Postman API 호출, 패킷 흐름 분석 | API 호출 리포트  |
| 4  | Front End 개발  | Streamlit & gradio : UI 설계 구현 | python 기반 UI tools | UI 개발  |
| 5  | Back End 개발         | FastAPI 기초, uv 가상환경, 라우팅, Path/Query, Pydantic       | FastAPI 기본 CRUD 구현       | 기본 API 서버   |
| 6  | FastAPI 심화         | REST 설계, 예외처리, Swagger          | 구조화된 API 설계              | RESTful API |
| 7  | Fast API 실습   | Iris 데이터 머신러닝 모델 앱서비스 구현                 | 머신러닝, UI        | Model-Controller-View 아키텍쳐   |
| 8  | FastAPI + DB 연동    | ORM, SQLAlchemy                 | MariaDB 연동 CRUD, AdventureWorks-Sales 데이터를 다운받아 sqlite3에 저장한 후 앱 서비스          | DB 연결 API   |
| 9  | Chinook DB 앱 개발 서비    | Chinook DB ETL, CRUD                 | DB CRUD 로직을 만들고 Fast API와 연동하여 앱 개발(ngrok)         | DB 연동 앱서비스 개   |
| 10  | LLM adk 실습    | google ADK 실습                 | Gemini API Key완 연동하여 비지니스 로직을 만들고 앱 서비스 개발         | LLM + FastAPI + Streamlit/gradio + ngrok  |
| 11  | LLM RAG    | google ADK 로 RAG 앱 서비스 구현                 | Gemini API Key완 연동하여 비지니스 로직을 만들고 앱 서비스 개발         | LLM + FastAPI + Streamlit/gradio + ngrok  |
| 12  | Langchain 개발 I  | Gemini API로 Langchain 개발 1               | Gemini API Key완 연동하여 비지니스 로직을 만들고 앱 서비스 개발         | LLM + FastAPI + Streamlit/gradio + ngrok  |
| 13  | Langchain 개발 II   | Gemini API로 Langchain 개발 2               | Gemini API Key완 연동하여 비지니스 로직을 만들고 앱 서비스 개발         | LLM + FastAPI + Streamlit/gradio + ngrok  |
| 14 | AI Vibe Coding       | UX Flow, 컴포넌트 설계, Stitch, Figma MCP-> Figma UI 설계, Node.js 기초     | 서비스 화면 설계                | Figma 파일    |
| 15 | Full Stack 통합 & 발표 | 아키텍처 분석 (게시판, to do list 및 LLM 등 백엔드로 UI 앱서비스 구현)                        | 전체 연결 프로젝트 시연            | 최종 웹앱       |


[UV : Super Fast and Easy to use Package Manager for Python](https://www.youtube.com/watch?v=1kZ-touiEQ8&t=64s)
