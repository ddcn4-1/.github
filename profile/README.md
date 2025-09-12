# 
구름 딥다이브 클라우드 네이티브 4회차

# 1. 프로젝트

|단계|중점 구현|기간|
|:-:	|:-:	|:-:	|
|1차 (최적화 중심)|아키텍처, 리소스, 배포 구조 최적화 설계 및 기본 MVP 구현 |2025.08.28~2025.09.23|
|2차 (트랜잭션 무결성 중심)|데이터 일관성과 안정성 강화|2025.09.23~|
|3차 (자동화 및 안정화)|모니터링 등으로 오류, 장애 대응 프로세스 안정화 및 운영 자동화 ||

## 1차 클라우드 퍼포먼스 최적화
### 프로젝트 소개

### 상세 레포

## 2차 
### 프로젝트 소개
### 상세 레포

## 3차
### 프로젝트 소개
### 상세 레포

# 2. 개발 환경



# 3. 깃 컨벤션 및 브랜치 전략

## Commit Convention

구조 : `type(domain): body footer`

예시 `feat(auth): 카카오 로그인 api 추가 #1`

### Domain
```text
auth
admin
performance
seat
booking
```

### Type 

```text

setup :	aws 환경변수 세팅 등
feat :	새로운 기능 추가
fix :	버그 수정
docs :	문서 수정
chore :	코드 포맷팅, 오타 수정, 주석 수정 및 삭제 등
build :	CI/CD 파이프라인/ 테스트 등
test :	테스트 코드
refactor :	코드 리팩토링

```
### Body 
- 변경사항에 대해 요약하여 작성
- 한글 작성을 권장, 한 줄에 간결하게 작성

ex) `카카오 로그인 api 추가`
### Footer 
- 이슈 번호 태그

## PR Convention
```
### PR 타입(하나 이상의 PR 타입을 선택)
-[] Feat : 새로운 기능 추가
-[] Fix : 버그 수정
-[] Docs : 문서 수정
-[] Chore : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
-[] Refactor : 코드 리펙토링

### 반영 브랜치
ex) feat/login -> dev

### 변경 사항
ex) 로그인 시, 구글 소셜 로그인 기능을 추가했습니다.

### 테스트 결과
ex) 메인 브랜치에 포함되기 위한 코드는 모두 정상적으로 동작해야 합니다. 결과물에 대한 스크린샷, GIF 등

```

## 브랜치 전략
**Git Flow 전략**

`main` : 운영환경에 배포된 안정적인 코드가 있는 브랜치

`dev` : 배포 전 기능을 통합/테스트 하는 브랜치 

`feat` : dev 에서 브랜치를 분기하여 새로운 기능을 개발하는 브랜치

`hotfix` : main에서 발생한 버그 픽스를 빠르게 수정하기 위한 브랜치

**브랜치 프로세스**

<img width="521" height="402" alt="image" src="https://github.com/user-attachments/assets/bd52bc2a-bf4c-4248-89f6-76ab9c26fda5" />


# 4. 팀원
|이름|| 담당 |
|-----------------|-----------------|-----------------|
| 김현송    |  <img src="https://github.com/user-attachments/assets/67d80433-e382-4833-9671-6bda6a116bc5" alt="김현송" width="100"> | <ul><li>aa</li><li>bb</li><li>cc</li></ul>     |
| 국다혜   |  <img src="https://github.com/user-attachments/assets/56d20aad-2132-42b4-aa69-afa1875c1641" alt="국다혜" width="100">| <ul><li>aa</li><li>bb</li><li>cc</li></ul> |
| 박진영   |  <img src="https://github.com/user-attachments/assets/de9ff1ec-f113-43ad-921b-c565409b3598" alt="박진영" width="100">    |<ul><li>aa</li><li>bb</li><li>cc</li></ul>  |
| 윤효정    |  <img src="https://avatars.githubusercontent.com/u/77730511?v=4" alt="윤효정" width="100">    | <ul><li>aa</li><li>bb</li><li>cc</li></ul>    |
