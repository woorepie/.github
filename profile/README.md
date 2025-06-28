
<h1 align="center">WOOREPIE</h1>

![image](https://github.com/user-attachments/assets/a996c240-0328-4d5f-9819-f3cadc572571)

<br>

## 📌 목차

1. [**프로젝트 개요**](#1-프로젝트-개요)
2. [**팀원 소개**](#2-팀원-소개)
3. [**프로젝트 설명**](#3-프로젝트-설명)
4. [**기술 스택**](#4-기술-스택)  
5. [**아키텍처**](#5-아키텍처)
6. [**테스트**](#6-테스트)
7. [**향후 개선 방향**](#7-향후-개선-방향)

<br>

---

<br>

## 1. 프로젝트 개요

### 🏠 배경

기존의 토큰 증권(STO)은 **샌드박스 규제 아래 시범적으로 운영**되어 왔으나, 최근 **관련 법제화가 본격적으로 추진**되면서 **STO 시장의 제도권 진입이 가시화**되고 있습니다. 이에 따라 주요 증권사들이 빠르게 진입하고 있으며, 다양한 기업들도 **상용 서비스 출시를 준비**하고 있습니다.

### 💡 WOOREPIE의 방향성

아직 시장 점유율이 낮은 **우리투자증권**은 이번 STO 흐름을 **새로운 투자 시장의 트리거**로 삼아, **잠재 고객을 확보할 수 있는 전략적 기회**를 가지게 되었습니다. 이에 따라 우리는 **우리금융그룹의 계열사 시너지**를 적극 활용한 \*\*부동산 조각 투자 플랫폼 ‘WoorePIE’\*\*를 기획 및 개발하였습니다.

### 🆚 기존 플랫폼(Kasa)과의 차별점

기존 STO 플랫폼인 대신증권의 **Kasa**는 **자체 매입한 매물에 한해 투자 기회를 제공**하기 때문에 **선택의 폭이 제한적**입니다.

### 💪 WOOREPIE만의 구조적 강점

WOOREPIE는 **다양한 공급자와 매물 구조**를 통해 보다 풍부한 투자 기회를 제공합니다.

1. **자체 매물 등록**

   * 우리에프앤아이의 보유 부동산 매물 등록
   * 우리금융그룹 기반의 자산으로 **안정성 확보**

2. **외부 대행인 매물 등록**

   * 누구나 **투자 대행인 등록 후 매물 등록 가능**
   * 내부 심사(감정평가 + 자료 진위 여부) 진행
   * 검증된 매물은 **우리자산신탁 명의로 이전**, **관리신탁 체결**

### 🛡️ 투자자 보호 장치

* 투자금은 **우리은행 예치금 계좌에 보관**되며
  **투자금 사용계획서 기반**으로만 인출 가능
* **자산 검증, 신탁 관리, 자금 보관**까지 우리금융그룹 계열사들이 협업하여
  **투명성과 안정성**을 보장

<br>

---

<br>


## 2. 팀원 소개
|<img src="https://github.com/CooolRyan.png" width="220" />|<img src="https://github.com/imhaeunim.png" width="220" />|<img src="https://github.com/Aunsxm.png" width="220" />|<img src="https://github.com/letmeloveyou82.png" width="220" />|
|:-:|:-:|:-:|:-:|
|나원호<br/>[@CooolRyan](https://github.com/CooolRyan)|임하은<br/>[@imhaeunim](https://github.com/imhaeunim)|장수현<br/>[@Aunsxm](https://github.com/Aunsxm)|최윤정<br/>[@letmeloveyou82](https://github.com/letmeloveyou82)|


<br>

---

<br>


## 3. 프로젝트 설명

**WOOREPIE**는 STO(Security Token Offering, 증권형 토큰 발행) 기반의 **부동산 조각 투자 플랫폼**입니다.
사용자는 소액으로 부동산에 투자하고, **보유한 토큰에 따라 배당금과 매각 차익** 등의 수익을 얻을 수 있습니다.

### 📌 STO란?

STO는 실물 자산(부동산, 미술품, 저작권 등)을 **블록체인 기술로 디지털화한 증권형 토큰을 발행**하는 방식입니다.

* 자본시장법상 '증권'으로 인정되어 **법적 보호 및 효력**을 가짐
* 블록체인 기반으로 **소유권 이전, 배당, 거래, 권리 행사**가 디지털로 처리됨

### 🔄 시스템 흐름

1. 사용자가 **본인 인증 및 회원가입**
2. 플랫폼이 **사용자 지갑 생성**
3. 사용자가 **청약 참여** → 거래 체결 시 **토큰 발행**
4. 토큰 보유자는 **배당 및 매각 수익 분배**

> ![서비스 흐름도](https://github.com/user-attachments/assets/431f03e4-08ac-4538-b30d-f9581114270a)


### 주요 기능

#### 💸 청약

* 대행인이 등록한 매물에 대해 사전 모집
* 모집 완료 시 **청약 성공**, 이후 거래 가능
* **선착순 토큰 발행** 방식


#### 🔁 거래

* **매수**: 특정 건물에 대한 토큰 구매
* **매도**: 보유 토큰 판매

#### 💰 배당금

* **분기별 임대 수익을 배당금으로 지급**
* 보유 토큰 비율 기준 자동 분배

#### 🏷️ 매각

* 매물 매각 시 **지분 비율에 따라 매각 금액 입금**
* 처분권 보호 위해 **49% 미만 지분만 토큰화**

#### 🔐 로그인 및 회원가입

* 고객확인절차(KYC) 기반 사용자 인증
* 일반 사용자 / 투자 대행인 구분하여 가입

### 주요 화면
https://github.com/woorepie/woorepie-front

### 시연 영상
https://drive.google.com/drive/folders/1g1LGctpGMvINiX8P1-q-zzggafwJznJ5?usp=sharing

<br>

---

<br>


## 4. 기술 스택

> ![기술 스택 이미지](https://github.com/user-attachments/assets/943499a3-bbdb-406a-9301-81f1afa2feb2)


### 📌 주요 기술

#### 📨 Kafka

* **3개 브로커 기반 클러스터 구성**으로 고가용성 확보
* **Key 기반 파티셔닝**을 통해 **순서 보장 및 처리량 확장성 확보**
* 청약 및 거래 데이터의 **실시간 스트리밍 처리**
* **디스크 기반 저장 + 복제 기능**으로 데이터 손실 방지
* **비동기 메시지 브로커**로 서비스 간 **확장성과 독립성** 확보


#### ⚡ Redis (Amazon ElastiCache)

* **Sorted Set** 구조와 **분산 락**으로 **주문 체결 순서 보장**
* **Lua 스크립트**를 통한 **원자성 있는 트랜잭션 처리**
* Kafka 기반 비동기 처리와 결합하여 **안정적 고성능 주문 처리**
* **DB 부하 감소 + 거래 처리 속도 향상**


#### ☁️ Amazon EKS

* **2개 AZ 구성**으로 데이터센터 장애 발생 시에도 **서비스 안정성 확보**
* \*\*HPA(Horizontal Pod Autoscaler)\*\*를 통한 **자동 Pod 확장**
* **EC2 Auto Scaling Group**을 통한 **노드 자동 증설**


#### 🛢️ Database

> ##### 🐘 PostgreSQL
* **pgpool2 + watchdog**을 통한 고가용성 클러스터 구성
* **Streaming + Logical Replication**을 활용한 이중 복제
* **Master/Replica 라우팅 분리**로 읽기/쓰기 최적화
* **Connection timeout 조정**으로 성능 개선
* **AWS RDS와의 실시간 복제**로 On-Prem 장애 대응

> ##### 🍃 MongoDB
* **HAProxy + Keepalived**를 통한 **가상 IP(VIP)** 구성
* **Replica Set 구성**으로 데이터 **실시간 동기화 및 고가용성 확보**


#### ⛓️ Blockchain (Polygon Amoy)

* **ERC-1400 + ERC-3643 기반 구조**로 설계된 **증권형 토큰(STO)**
* **레지스트리 컨트랙트에 사용자 인증정보 등록**

  * 토큰 관련 로직 실행 시 **신원 및 자격 검증**
* 주요 기능:

  * `issue` : 토큰 발행
  * `transferWithData` : 조건 기반 전송
  * `redeem` : 토큰 소각


<br>

---

<br>


## 5. 아키텍처

### 📦 서비스 흐름

> ![서비스 아키텍처](https://github.com/user-attachments/assets/d4c859f6-6d96-4a73-9b56-33a3acb1bd8b)

### ⚙️ CI/CD 파이프라인

> ![CI/CD](https://github.com/user-attachments/assets/6b025c69-18e5-483e-96fd-c3462806b334)

### ☁️ AWS 구성

> ![AWS](https://github.com/user-attachments/assets/308354d7-f86f-4bcb-897f-5a623dd5369e)

### 🖥️ On-Premise 구성

> ![On-Prem](https://github.com/user-attachments/assets/eca0c73f-7793-44c6-9c58-57bb13621af6)


<br>

---

<br>


## 6. 테스트

### ✅ 단위 테스트

* JUnit

### ✅ 통합 테스트

* K6

### ✅ 부하 테스트

* JMeter: 초당 100건 × 30초 (총 3,000건) 요청
* 결과:
> ![image](https://github.com/user-attachments/assets/4160088b-5cab-4b1d-9aee-89f730ff88f5)
> ![image](https://github.com/user-attachments/assets/3df535b3-2276-4f28-ac38-029394eec522)

  * 최소 응답 시간: **0.3초**
  * 평균 응답 시간: **16.2초** → 사용자 체감 대기 시간 큼
  * 요청 실패율: **0%**
  * Pod HPA 설정으로 Pod 수 3 → 10 자동 증가
  * EC2 Auto Scaling으로 노드 1개 추가
  * **DB는 On-Prem, WAS는 AWS로 분리되어 WireGuard로 연결 중** → **속도 이슈 존재**

### ✅ 가용성 테스트

#### Kafka

* 브로커 1 중단 시, 리더가 다른 브로커로 재선출되어 서비스 유지
> ![Kafka](https://github.com/user-attachments/assets/76e0e559-e9dc-4818-8b1b-3902d8d4faf6)
> ![Kafka Failover](https://github.com/user-attachments/assets/d601b69b-4665-46dc-8547-694e2d741f20)

#### DB

* Master 노드 중단 시, pgpool2의 **Failover**로 자동 전환 → 서비스 정상 유지

> ![DB Failover](https://github.com/user-attachments/assets/2f4a9894-30d1-4744-b142-3d1462cf70de)
> ![DB Failover](https://github.com/user-attachments/assets/615d0b4f-7fca-488e-9fa6-09b01fae55e2)


<br>

---

<br>

## 7. 향후 개선 방향

### ☁️ 네트워크 구조 개선

* 현재 WAS와 DB는 **다른 클라우드에 위치**하며, WireGuard를 통해 연결되어 있어 **Latency 이슈**가 발생하고 있음
* 향후 **온프레미스 서버에 공인 IP를 할당**, **Site-to-Site VPN** 구성으로 전환 시 **더 빠르고 안정적인 통신**이 가능할 것으로 예상

### ⛓️ 블록체인 구조 개선
* 폴리곤 네트워크 속도가 매우 느려 이를 개선하고 금융 데이터의 보안을 위해 프라이빗 네트워크 구축의 필요성을 느낌
* 실제 엔터프라이즈에서 사용되는 하이퍼렛저 베수와 같은 네트워크를 서버에 직접 구축하는 과정을 통해 가스비 절감과 속도 개선, 데이터 보안을 달성할 수 있을 것이라 생각
