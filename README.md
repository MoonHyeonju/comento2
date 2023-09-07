# 코멘토 2차 과제


## REST API란
- REST 아키텍쳐 스타일을 따르는 API

-REST: 분산 하이퍼미디어 시스템을 위한 아키텍쳐 스타일

-아키텍쳐 스타일: 제약조건의 집합

---

### HTTP 통신

사용자가 서버에 요청을 보내는 통신

#### HTTP 특징
- 클라이언트 서버 구조

-클라이언트는 서버에 요청을 보내고 응답을 대기

-서버가 요청에 대한 결과를 만들어서 응답

- 무상태(Stateless) 프로토콜
  
-서버가 클라이언트의 상태를 보존하지 않음

-장점: 서버 확장성 높음

-단점: 클라이언트 추가 데이터 전송

#### HTTP 메서드
- GET: 리소스 조회
- POST: 요청 내역 처리

---

### 브라우저에 URL을 입력 후 요청하여 서버에서 응답하는 과정

1. 브라우저에 URL 입력
   
ex) https://comento.kr

-https:// : 통신 프로토콜

-comento.kr : 웹 사이트의 도메인 이름

2. 브라우저가 도메인명으로 IP주소 조회

3. 브라우저가 서버와의 TCP 연결 시작

4. 브라우저가 HTTP 요청을 서버로 전송

5. 서버가 요청을 처리하고 응답 전송

6. 브라우저가 콘텐츠 렌더링

(렌더링: 서버로부터 HTML파일을 받아 브라우저에 표시하는 과정)

