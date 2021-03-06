---
title: CI/CD 란?
date: "2019-11-09"
description: CI/CD 에 대해 알아보자 

---

## 1. 개념
  
    - 어플 개발 단계를 자동한 하여 짧은 주기로 배포하는 전략 또는 방법
    - 코드통합,테스트,릴리즈, 배포, 등(CI/CD 파이프 라인)의 라이프 사이클을 자동화한다.
    - 해당 과정을 모니터링 할수있다.
    - 개발자가 아니더라도 쉽게 빌드 ,배포 가능
    - 한번에 많이 수정하지 말고, 조금식 수정하여 여러번 배포하라!

## 2. 전략
    - 개발/배포 단계에 적용되는 전략이 달라진다.
    - CI: continuous Integration
        +빌드 -> 테스트 -> 병합
        + 개발자를 위한 자동화 프로세스
        + 개발자간의 코드 충돌 방지
        + 정기적인 빌드 및 테스트를 거쳐 공유 레포지티에 병합되는 과정
        
    - CD: Continuous Delivery
        + 병합 -> 버그 테스트 -> 릴리즈
        + 어플에 적용한 변경사항이 버그 테스트를 거쳐 레포지터리에 자동으로 업로드 되는 것
        + 운영팀은 언제든지 실시간으로 이 레포지터리에서 실시간으로 프로덕션 환경으로 배포 가능

    - CD: Continuous Deployment
        + 어플을 프로덕션 환경으로 배포하는 작업을 자동화 하는 것
        + 서버가 여러 대 일 경우 더욱 중요

## 3. 기타사항
    - 지원툴: bamboo



> 참고 사이트  
    -www.onlywis.tistory.com/9
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI5MTk5ODI0Nl19
-->