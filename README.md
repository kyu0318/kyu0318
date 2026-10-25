# 김규현 | 보안·인프라 엔지니어를 준비합니다

웹 서비스를 개발하고, 서비스가 연결되는 서버·네트워크 환경을 실습하며 보안·인프라 분야 취업을 준비하고 있습니다.

## 프로젝트

### 대피할지도 — 재난 대피소 지도 서비스 · 1차 팀 프로젝트

재난 유형별 대피소를 지도에서 찾고, 현재 지도 영역과 위치를 기준으로 정보를 확인하는 웹 서비스

- **Service 개발 전담:** 사용자 화면, Kakao Maps 연동, 대피소 조회 API와 기존 재난 유형 탭 조회
- **인프라 담당 기록:** Ubuntu Docker Host 구성과 해당 호스트의 DB 연결, Python 데이터 처리용 컨테이너 실행과 Cron 설정
- **팀 역할:** Admin 관리자 페이지 개발은 다른 팀원 담당
- **사용 기술:** Java·Spring Boot·Spring Data JPA·MySQL·HTML/CSS·JavaScript·Thymeleaf·Kakao Maps API / Ubuntu·Docker·Python·Cron

[Service 코드·구현 설명](https://github.com/kyu0318/service) · [인프라 구축 기록](https://app.notion.com/p/1-Docker-Host-3c910d3ee8d380e780f7c6db82d112a8) · [Admin 원본 — 다른 팀원 담당](https://github.com/ehdgus4026-tech/admin)

### 2차 프로젝트 — 인프라 구축 · 진행 중

네트워크·서버 환경의 구축 과정과 점검 내용을 기록 중인 팀 프로젝트

[프로젝트 기록](https://app.notion.com/p/40010d3ee8d38028a22fed0c6ab2b6c9) · [팀 작업일지 · 로그인 필요](https://app.notion.com/p/3ff0ca1d4aae80eead72eea55c26f015)

## 기술스택

프로젝트·교육 실습의 사용 기술과 관련 학습 기록. 상세 버전·구현 범위는 각 저장소와 문서 기준

| 구분 | 기술 | 사용·학습 범위 |
| --- | --- | --- |
| Application & Data | Java 17, Spring Boot 4.1.0, Spring MVC, Spring Data JPA, Hibernate, MySQL, Maven | 1차 프로젝트 Service API·엔티티·조회 처리, 빌드 설정 |
| Frontend | HTML, CSS, JavaScript, Thymeleaf, Kakao Maps API | 사용자 화면, 지도·마커·장소 검색, 대피소 목록 연동 |
| Infrastructure | Ubuntu, Docker, Python, Cron | Docker Host 구성, DB 연결, 데이터 처리 컨테이너·예약 작업 설정 기록 |
| Network & Virtualization | VMware, VyOS, Rocky Linux, Windows, DNS·DHCP, VPN, Active Directory | 가상 환경의 네트워크·서버·접근 권한 설정 실습 |
| Cloud · 학습 기록 | AWS VPC·EC2·ALB 등 | AWS 복합 실습 문서의 구성 절차·학습 기록 |
| Tools | Git, GitHub | 소스·문서 버전 관리 |

Spring Boot 버전은 저장소 POM 선언 기준. 빌드·실행 성공 여부는 별도 검증 필요

## 관련 실습·문서

- [포트폴리오 허브](https://road-bloom-792.notion.site/40410d3ee8d3810a92cbc42c2bf94ee6): 프로젝트·실습·학습 기록의 통합 진입점
- [인프라 실습 기록](https://app.notion.com/p/3e110d3ee8d38062a09bea4b5cec09b6): 네트워크·서버·접근 권한 설정 실습
- [인프라 학습 정리](https://app.notion.com/p/3e110d3ee8d38038b8c8faeef5b351e3): 개념·작동 흐름·면접 대비 정리

프로젝트 구현, 교육 실습, 학습 기록을 구분해 정리
