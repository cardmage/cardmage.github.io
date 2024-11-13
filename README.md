
---

# **Heechul Kim**

**Contact**  
- Name: 김희철
- Phone: 010-2830-8962  
- Email: cardmage@naver.com  

## Introduce
- 14년차 풀스택 개발자로 여러 프로젝트들을 리딩해왔습니다.
- 팀 내 개발문화 개선 및 기술 리뷰를 하고 있습니다.
- 요구사항을 넘어 더 좋은 서비스를 제공하기 위해 노력합니다.
- 이런 점들을 인정 받아 첫 회사부터 모든 직급에서 빠른 진급을 해왔습니다.

## Work Expreience
- 지마켓 Post Purchase 팀 (2017.12 - )   
- 3D Systems (2016.9 - 2017.12)   
- 삼성중공업 중앙연구소 선박해양ICT (2010.1 - 2016.6)

## Education
- 경북대학교 컴퓨터 공학과 (2004 - 2010)

## Technical Expertise
- **Languages:** Java, C#, C++, Javascript
- **Frameworks:** Spring boot, ASP.NET, React, Next.js
- **Databases:** Oracle, MS SQL, Elasticsearch, Redis, Mongo, Kafka, Hive
- **Infra:** Kubernetes, Nginx, IIS, Tomcat
- **Others:** Agile, Git, DDD, Microservice

## **Selected Projects**
### **Gmarket Projects**
#### SSG 주문 연동
- SSG API 를 통해 양 사이트 주문상태 동기화
- 전체 시스템 설계 및 개발 리드
    - 일정 제한된 상황에서 스펙 조율
    - 이벤트 순서가 보장되지 않는 상황에서 최종 상태 일치
#### ESM+ V2 (판매자 사이트) 개발
- 판매자 사이트 고도화 작업 중 주문/배송/클레임 영역 개발
    - 전체 시스템 설계 및 프로토타입 작성
    - FE 테이블 라이브러리 성능 개선
#### 주소 찾기
- 주소 검색 속도 개선
    - ES 데이터 구조, tokenizer, query, aggre 개선으로 즉시 응답
    - 동의어 사전 추가로 검색 퀄리티 개선
#### 클레임 도메인 생성
- 레거시 환불 SP 코드화
    - DDD 적용하여 설계
    - 여러 타 팀 코드와 직접 결합된 구조를 메세지 큐를 사용하여 분리
    - 유지보수가 불가능하던 아무도 모르는 코드를, 테스트 가능한 코드로 변경
    - 환불금액에 대한 모든 경우 테스트 코드 작성. 장애 발생시 실제 데이터로 부터 테스트 코드 자동 생성.
- 클레임 FE/BE 고도화
    - 애자일 PO/개발리더
    - 국가/플랫폼별 사이트 통합하여 비지니스 룰 정리 및 코드 공통화. 국제화 적용
    - 다른 도메인에서 활용할 수 있도록 주문 상태별 이벤트 발행

### **3D Systems Projects**  
#### Geomagic for Solidworks
- 개요 : Solidworks 에서 3D 스캔한 Mesh 를 편집하고 Cad 형상을 추출하는 플러그인 개발
- 기술 : C++, MFC, CLR C++, C#
- 담당업무
    - 3D Deviation 분석 모듈 개선
    - Cad-Mesh Align 모듈 개선

### Control X
- 개요 : Inspect 프로그램 개선
- 기술 : C++, MFC
- 담당업무
    - 특정 그래픽카드에서 발생하는 OpenGL 버그 수정
    - 타 회사 Airfoil/2D Twist 분석 시스템 포팅
    - Tolerance 기본값을 ISO 표준
    - 여러 분석 결과를 한 화면에서 동시에 볼 수 있는 MFC Multi view 개발

### **Samsung Heavy Industries Projects**  
### 스마트쉽 - 선단 관리 시스템 (2016.2 ~ )
- 개요 : 여러 선박의 운항 정보 등을 육상에서 실시간으로 모니터링 / 제어하는 시스템
- 기술 : ASP.NET MVC, WPF, WCF, Require, Knockout, Bootstrap, Googlemap, Cesium, MSSQL, NHibernate, Spring.NET, GDAL, C#, AWS
- 담당업무
    - 선박 실시간 위치/위험지역/기상/운항 경로/선박 정보 구글맵 마커
    - 미 기상청 데이터(파고/풍속) 여러 종류의 기상 데이터 이미지 생성 / 맵 타일 생성
    - 선박 데이터(회전수, 연료 소모 등 수백가지) 비교 차트
    - 선박 내부 설치 프로그램 원격 관리

### 빅데이터 기반 선박 운항 성능 분석 (2015.10 ~ )
- 개요 : 선박 운항 로그를 분석할 수 있는 플랫폼 구축, 성능 개선 방안 탐색 / 성능 측정 지표 개발
- 기술 : Centos/Ubuntu, Postgresql, Hadoop 2.6, Hive, Tez, Sqoop, Oozie, Spark, Hue, R, C#, TestStack.White
- 담당업무
    - 하둡 에코시스템 구성
    - 운항 로그/기상 데이터 데이터베이스화(External, Sqoop)
    - HIVE 성능 최적화(ORC, Partition, Tez 등)
    - 하둡 접근 편의성 개선(NFS->Mount->SFTP, R/Python/C# Connector, Hue)
    - 선박 성능 보고서 템플릿(R markup) 작성

### 방사선 추적 관리 시스템 (2014.5 ~ 10)
- 개요 : 방사선 장비, 작업자의 위치를 추적하고 개인별 피폭량을 관리하는 시스템
- 기술 : ASP.NET, IBatis, Oracle, ArcGis, Require
- 담당업무
    - 방사선원, 피폭범위, 작업자의 위치를 지도에 실시간으로 표시
    - 작업자별 연간 기준 대비 피폭량 관리
    - 작업량 / 피폭량 통계 SMS 전송

### 작업 지시 시스템 (2013.3 ~ 2014.6)
- 개요 : 조선소의 용접반에서 블록의 3D 형상을 확인하고, 구역별로 작업자를 배치/관리하는 프로그램
- 기술 : MFC, OpenGL, CLR C++, WCF, gSOAP, Oracle
- 담당업무
    - CAD 모델을 화면에 표시하고 확대, 회전 등을 통해 작업할 블록의 모양을 미리 확인
    - CAD 모델을 분석하여 용접선 생성
    - 용접선의 모양을 바탕으로 작업 구역 생성, 작업량 계산, 용접 난이도별 예측 시간 계산
    - 반원들을 구역별/시간별로 배치하여 작업지시서 생성

### 정도 분석 관리 시스템 (2011.6 ~ 2014.12)
- 개요 : 블록 조립 단계마다 누적되는 용접시 비틀림 등 오작을 추적/원인 분석/현상태 분석하는 시스템
- 기술 : C#, ASP.NET, MiPlatform, Oracle
- 담당업무
    - 자동화 설비/사용자가 생성한 문서를 실시간 감지하여 DB화
    - 작업 문서 등록/관리, 작업 일정/결과(주/월) 등록/수정, 작업신청, 도면/오차 조회 등의 페이지 개발
    - 타 개발자 쿼리 튜닝. DB 관리. 시스템 성능 개선.

### 임직원 평가 시스템 (2011.5 ~ 2013.11)
- 개요 : 연구원들의 업적/역량을 다수의 평가자가 월별/분기별 평가하고 고과를 배분할 수 있는 시스템
- 기술 : ASP.NET, NHibernate, Oracle
- 담당업무
    - 사내 정보와 연계하여 연구원의 지표(인사정보, 외국어, 봉사활동 등) 반영
    - 월별 평가 점수를 바탕으로 고과 배분 모듈
    - 직급별 승격 기준으로 연구원들의 승격 가능 여부, 부족한 항목 확인

### 예방정비시스템 (2010.6 ~ 2013.7)
- 개요 : 공장의 각종 자동화 설비의 고장을 미리 예측/정비하도록 하여 생산 지연을 막는 시스템. 설비 관리, 창고 관리, 설비 모니터링
- 기술 : C#, ASP.NET, Silverlight, Oracle
- 담당업무
    - 설비관리 기능 (설비정보 / 이력 / 입출고 / BOM 관리)
    - 예방정비 기능 (BOM별 MTBF 등 입력, 점검 주기를 계산하여 보전 계획을 수립)
    - 작업자 관리 기능 (작업 내용 / 시수 / 통계)
    - 창고 관리 기능 (부품 입출고 / 구입 / 예산 관리 / 설비관리시스템과 연계)
    - 사내 메일, 결제, 예산 신청 등 시스템과 연결
    - 모니터링(로그, 통계, 현상태 지도)
