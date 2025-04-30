## 과거 서비스 했던 블랙 서바이벌 게임을 자바+스프링부트 최신 기술로 리메이크 하여 새로 만들어보는 백엔드 프로젝트 입니다 

### 사용하는 기술 스택은 아래와 같습니다
+ Java 17
+ Spring Boot 3.4.5 
+ Gradle
+ JPA
+ JWT
+ WebSocket
+ Redis

### 1차 목표: 로그인 및 로비쪽 구현

#### 로비 영역 (HTTP + JWT)
+ 기술: Spring Boot + REST API
+ 통신: HTTP + JWT (헤더 Authorization: Bearer 토큰)

#### 기능:
+ 유저 로그인 / 인증 (JWT 발급)
+ 유저 정보 조회 (프로필, 재화, 캐릭터 등)
+ 매칭 요청 (POST /match)
+ 저장소: H2 (추후 MySQL 사용)

#### 개발 환경
+ Mac에서 IntelliJ를 사용해서 개발 진행