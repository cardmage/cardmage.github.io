
---

# **Heechul Kim**

**Contact**  
- Name: 김희철
- Phone: 010-2830-8962  
- Email: cardmage@naver.com  

## Introduce
- 14년차 풀스택 개발자로 여러 프로젝트들을 리딩해왔습니다.
- 팀 개발문화 개선 및 기술 리뷰를 하고 있습니다.
- 요구사항을 넘어 더 좋은 서비스를 제공하기 위해 노력합니다.
- 이런 점들을 인정 받아 첫 회사부터 모든 직급에서 빠른 진급을 해왔습니다.

## Work Expreience
- 지마켓 Post Purchase 팀 (2017.12 - )   
    - 배송/클레임 도메인 여러 프로젝트 리드 
    - My Page, 주소검색, 판매자 API 속도개선을 통해 사용자 경험 향상
    - 레거시 개선 및 클라우드 전환
- 3D Systems (2016.9 - 2017.12)
    - 계측 프로그램 신기능 개발 및 오류 수정
- 삼성중공업 중앙연구소 선박해양ICT (2010.1 - 2016.6)
    - 선박 블록 계측 CAD 시스템 개발
    - WMS, 평가시스템 등 사내 여러 웹 시스템 개발
    - 빅데이터 분석 시스템 구축

## Education
- 경북대학교 컴퓨터 공학과 (2004 - 2010)

## Technical Expertise
- **Languages:** Java, C#, C++, Javascript
- **Frameworks:** Spring boot, ASP.NET, React, Next.js
- **Databases:** Oracle, MS SQL, Elasticsearch, Redis, Mongo, Kafka, Hive
- **Infra:** Kubernetes, Nginx, IIS, Tomcat
- **Others:** Agile, Github, DDD, MSA, JUnit, Spock

## **Selected Projects**

### **Gmarket Projects**

#### SSG 주문 연동
- 개요 : 지마켓 상품을 SSG 에서 판매하고 양 사이트 주문 상태 동기화
- 기술 : Spring boot, Kubernetes, Elasticsearch
- 담당업무
    - 시스템 설계 및 개발 리드
    - 촉박한 일정을 극복하기 위해 이해 당사자들과 스펙 조정 및 태스크 분할
    - SSG 이벤트 순서 보장이 불가능할 때 상태 동기화 방안
    - 이벤트 재처리 및 로깅 모듈 개발

#### 판매자 사이트 개편
- 개요 : 판매자 사이트 고도화 작업 중 주문/배송 영역 개발
- 기술 : Next.js, Typescript, Spring boot, Kubernetes, Redis, Kafka
- 담당업무
    - 시스템 설계 및 개발 리드
    - 500x100 크기 테이블 조작 성능 개선
    - virtual thread, kafka stream 등 팀원들이 새로운 경험해 보도록 돕고 리뷰
    - A/B, canary 동시에 하기위한 nginx controller 구성

#### 클레임 신청 개편
- 개요 : 클레임 신청 UX 개선
- 기술 : React, Spring boot, Kubernetes
- 담당업무
    - 애자일 PO/개발리더
    - 언어/플랫폼별 분산되어 있던 레거시 BE 코드 통합
    - 클레임 비지니스 룰 및 도메인 모델 생성
    - 국제화, 클라우드 전환
    - 타 도메인 결합 제거. api/event 제공.

#### 환불 개편
- 개요 : 환불 프로세스 개편
- 기술 : Spring boot, Kubernetes, Spring config, Sql server, Kafaka, Mongo
- 담당업무
    - 거대한 SP 를 MSA 기반 클라우드 시스템으로 전환
    - 확장 가능하도록 DDD 설계
    - 결제 등 타 도메인과 강력한 결합을 이벤트 기반 분리
    - 환불금액 test code coverage 100% 달성
    - Fail point 들에 대한 분석 및 대처 방안 수립

### **3D Systems Projects**  

#### Geomagic for Solidworks
- 개요 : Solidworks 에서 3D 스캔한 Mesh 를 편집하고 Cad 형상을 추출하는 플러그인 개발
- 기술 : C++, MFC, OpenGL, CLR C++, C#
- 담당업무
    - 3D Deviation 분석 모듈 개선
    - Cad-Mesh Align 모듈 개선

#### Control X
- 개요 : Inspect 프로그램 개선
- 기술 : C++, MFC, OpenGL
- 담당업무
    - 특정 그래픽카드에서 발생하는 OpenGL 버그 수정
    - 타사 Airfoil/2D Twist 분석 시스템 포팅
    - Tolerance 기본값을 ISO 표준
    - 여러 분석 결과를 한 화면에서 볼 수 있는 MFC Multi view 개발

### **Samsung Heavy Industries Projects**  

#### 선단 관리 시스템
- 개요 : 여러 선박의 운항 정보 등을 육상에서 실시간으로 모니터링 / 제어하는 시스템
- 기술 : ASP.NET MVC, WPF, WCF, Require, Knockout, Bootstrap, Googlemap, Cesium, MSSQL, NHibernate, Spring.NET, GDAL, C#
- 담당업무
    - 선박 정보 Googlemap marker/overlay
    - 미 기상청 데이터(파고/풍속)로 이미지(Map Tile) 생성 및 Tile server 생성
    - 선박 데이터 수백개 차트 생성

#### 선박 운항 성능 분석
- 개요 : 선박 운항 로그를 분석할 수 있는 플랫폼 구축, 성능 개선 방안 탐색 / 성능 측정 지표 개발
- 기술 : Centos/Ubuntu, Postgresql, Hadoop 2.6, Hive, Sqoop, Oozie, Spark, Hue, R, C#, TestStack.White
- 담당업무
    - Hadoop ecosystem 구성 및 Connector 등으로 연구원들의 시스템 접근 편의성 개선
    - HIVE 성능 최적화(ORC, Partition, Tez 등)
    - 선박 성능 보고서 템플릿(R markup) 작성

#### 작업 지시 시스템
- 개요 : 조선소의 용접반에서 블록의 3D 형상을 확인하고, 구역별로 작업자를 배치/관리하는 프로그램
- 기술 : C++, MFC, OpenGL, CLR C++, WCF, gSOAP, Oracle
- 담당업무
    - CAD 모델을 분석하여 용접선 생성
    - 용접선의 모양을 바탕으로 작업 구역 생성, 작업량 계산, 용접 난이도별 예측 시간 계산
    - 반원들을 구역별/시간별로 배치하여 작업지시서 생성
    - 팀원들의 쿼리 튜닝하여 성능 개선

#### 예방정비시스템
- 개요 : 공장의 각종 자동화 설비의 고장을 미리 예측/정비하도록 하여 생산 지연을 막는 시스템. 설비 관리, 창고 관리, 설비 모니터링 기능.
- 기술 : C#, ASP.NET, Silverlight, Oracle
- 담당업무
    - Webform 구조를 ajax 사용으로 page rerendering 최소화
    - 20개 이상 복잡한 페이지 구현
    - 메일, 결제, 예산 신청 등 시스템과 연결
