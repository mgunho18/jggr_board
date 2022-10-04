# 중고거래 게시판
* 스프링부트 기반의 게시판 서비스
* 3 tier architecture로 설계
* 가용영역 이중화, 무중단 배포, 오토스케일링을 바탕으로 시스템의 가용성을 높임
* 세션 저장소로 redis를 사용
* 서비스의 목표 평균 응답 시간 달성을 위한 최대 동시 접속자 수 시나리오 테스트 수행

## 구현 화면
<img width="556" alt="게시판 구현" src="https://user-images.githubusercontent.com/33826145/160826484-f26f733b-3b2f-4cd3-a16c-b46025ef8ea2.png">

## 개발/운영 환경 구성
![개발:운영환경](https://user-images.githubusercontent.com/33826145/160827428-07ba9da5-3b33-45f0-aa1f-30eb4002a73b.jpg)

## 개발 환경 상세
![개발환경](https://user-images.githubusercontent.com/33826145/160827442-f20fa145-7f2a-43c7-bc90-44c8cbf1b317.jpg)

## 운영 환경 상세
![운영환경](https://user-images.githubusercontent.com/33826145/160827464-a2f595ea-eb70-4e77-b634-59bb791b21bc.jpg)

## CI/CD flow
![CI:CD](https://user-images.githubusercontent.com/33826145/160827476-c630f457-8275-4c7d-b4bb-fd0f2ecaed59.jpg)
