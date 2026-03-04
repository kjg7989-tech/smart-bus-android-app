# smart-bus-android-app
 - Overview
    1. 공공 버스 API와 Firebase를 활용한 위치 기반 광고 송출 안드로이드 애플리케이션.
    2. Android Studio 기반 Kotlin으로 단독 개발.

 - Problem
    3. 기존 버스 기존 버스 및 대중교통의 비효율적 광고 방식을 개선하기 위해 실시간 위치 시각화 중심의 모바일 앱 설계.

 - Tech Stack
    1. Kotlin (Java 일부)
    2. Android Studio
    3. Firebase Realtime Database
    4. REST API
    5. Google Maps SDK

 - Key Features
  1. 실시간 버스 위치 추적
    공공 API 기반 위치 데이터 수집 및 지도 위 실시간 위치 시각화 구현
  2. Firebase 데이터 연동
    사용자 데이터 및 버스 정보 동기화
    실시간 데이터 업데이트 구조 설계
  3. 직관적인 UI/UX 설계
    사용자 흐름 기반 화면 구성
    위치 확인 → 정보 확인 → 새로고침 구조 최적화
  4. My Role
    5인 팀 프로젝트 중 모바일 앱 단독 개발
    전체 UI/UX 설계
    Firebase 데이터 구조 설계
    API 연동 및 데이터 처리 로직 구현
    교수 및 팀 대상 테스트 후 기능 개선
![main-screen png](https://github.com/user-attachments/assets/832392a8-59f7-4546-9ffc-0bed9cc9027f)
<img width="432" height="640" alt="map-tracking" src="https://github.com/user-attachments/assets/87646a0e-1b45-4d0b-bafb-cce8f4add0a2" />

 - Technical Considerations
   1. API 호출 빈도 증가 시 발생하는 응답 지연 문제를 고려하여 비동기 처리 구조 설계
   2. Firebase 실시간 데이터 동기화 구조 이해 및 적용
   3. 사용자 중심 화면 흐름 설계 (위치 확인 → 정보 확인 → 갱신)
