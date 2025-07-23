# springvue2

이 프로젝트는 Spring Boot 백엔드와 Vue 2 프론트엔드를 사용하는 예제입니다. 데이터베이스는 MySQL을 사용하며 빌드 도구로는 Gradle을 사용합니다.

## 백엔드 설정

1. JDK 17 이상을 설치합니다.
2. 로컬 MySQL 서버를 준비하고 `src/main/resources/application.properties`의 접속 정보를 수정합니다.
3. 프로젝트 루트에서 다음 명령으로 테스트 및 빌드를 수행할 수 있습니다.
   ```bash
   gradle build
   ```

## 프론트엔드 설정

1. Node.js 16 이상과 npm을 설치합니다.
2. `frontend` 디렉터리에서 의존성을 설치하고 개발 서버를 실행합니다.
   ```bash
   cd frontend
   npm install
   npm run serve
   ```

## 프로젝트 구조

- `build.gradle` & `settings.gradle`: Spring Boot Gradle 설정
- `src/main/java`: 백엔드 Java 코드
- `frontend`: Vue 2 프론트엔드 코드

초기 환경 구성이 완료되면 백엔드와 프론트엔드 개발을 진행할 수 있습니다.
