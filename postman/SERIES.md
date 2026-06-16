# Postman 실무 가이드 시리즈

따라하기형 실무 자료집입니다. Vol·Part별 PDF와 함께 **시리즈 전체 구성**만 안내합니다.

---

## 시리즈 구성

이 README는 전체 시리즈 중 메인 라인 첫 번째 시리즈(Vol.1)에 해당한다.
전체 로드맵은 SERIES_ROADMAP.md 참고.

### 변경 배경
- 기존 단일 Vol.1~4 구성을 메인 라인(Vol.1~4)과 심화 사이드(Vol.S1~S5)로 전면 재편
- 이 README가 커버하는 범위: Vol.1(입문) — Postman 조작 익숙화부터 Environment·변수까지
- **Vol.1 · Vol.2에서는 Mock Server를 사용하지 않음** — Vol.S1 전용
- 로그인 자동화 · Runner는 Vol.2(자동화)로 분리

### 실습 API 정책

| Vol | 목적 | 실습 API | 기본 URL |
|-----|------|----------|----------|
| Vol.1 | Postman 조작 익숙화 | Postman Echo | `https://postman-echo.com` |
| Vol.2 | 로그인 · 토큰 · 자동화 | DummyJSON | `https://dummyjson.com` |
| Vol.S1 | Mock Server 심화 | (자체 Mock) | Vol.S1에서 다룸 |

Vol.1에서는 API를 배우기보다 **요청 보내기 · Params · Body · 저장**에 집중한다.  
Environment·변수는 **1-9 · 1-10**에서 처음 등장한다 (1-4 이전에 다루지 않음).

### 📘 Vol.1 — Postman 입문

| 파트 | 제목 | 주요 흐름 |
|---|---|---|
| 1-1 | Postman이 뭔가요 | 개요 · 앱 설치 |
| 1-2 | Postman 시작하기 | 회원가입 · 로그인 · 화면 구성 |
| 1-3 | Workspace 만들기 | Workspace 개념 · 생성 · 기본 세팅 |
| 1-4 | 실습 Collection 가져오기 | Collection JSON 다운로드 · Import · Echo 연결 확인 |
| 1-5 | Collection 만들기 | Collection 개념 · 생성 · 이름 설정 |
| 1-6 | 기본 GET 요청 보내기 | `GET postman-echo.com/get` · Send · 응답 확인 · 저장 |
| 1-7 | Query Params 포함 요청 보내기 | Params 탭 · `?name=kim` · 결과 비교 · 저장 |
| 1-8 | Body 데이터 포함 POST 요청 보내기 | Body 탭 · `POST postman-echo.com/post` · 응답 확인 · 저장 |
| 1-9 | Environment 만들기 · 변수 등록하기 | Environment 개념 · 생성 · Key-Value 입력 · 저장 |
| 1-10 | 요청에서 변수 사용하기 | `{{변수명}}` 문법 · URL에 적용 · 확인 |

> ※ Response(JSON), 상태 코드, 실패 응답 확인은  
>   각 요청 실습 내부에서 함께 설명

---
