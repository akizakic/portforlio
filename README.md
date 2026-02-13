# 📘 Portfolio
<table> <tr> <td width="220" valign="top">

<img src="https://github.com/user-attachments/assets/0e230d34-406c-4a11-85f5-be59cd35a64f" width="200" alt="양채은 프로필 사진"/>

</td>
<td width="75%" valign="top" style="padding-left:20px;">

## 💡 모두를 연결하는 든든한 다리,  서버 엔지니어 **양채은**입니다.

안녕하세요.  
서비스의 **안정성과 확장성을 설계하는 인프라 중심 서버 엔지니어**입니다.

온프레미스와 클라우드 환경에서 Kubernetes 기반 인프라 운영과 자동화를 수행하며  
**업그레이드 안정화, EOS 대응, 네트워크 구조 개선, 설치 자동화 표준화**를 통해  
운영 리스크를 줄이고 서비스 가용성을 높여왔습니다.

> “장애를 줄이고, 운영을 단순화하고, 확장 가능한 구조를 만드는 것이 제 역할입니다.”
</td>
</tr>
</table>


---

## 📞 Contact

- **Phone** : 010-4927-6206  
- **Address** : 서울특별시 영등포구  
- **Email** : akizakic@naver.com  

---

## 🏫 Education

**인천대학교 | 정보통신공학과 (부전공: 미래자동차연계전공)**  
📅 2021.03 ~ 2025.02 (졸업 예정)  
📊 GPA : 4.0 / 4.5  

---

## 📄 Certificate

- **2025.09** Certified Kubernetes Administrator (CKA)  
- **2024.09** AWS Certified Solutions Architect - Associate
- **2024.06** 정보처리기사  
- **2024.09** 리눅스마스터 2급  
- **2023.10** SQL 개발자 (SQLD)
  
---

## 🛠️ Tech Stack

### Infrastructure / Cloud
<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

### System / Tools
<p>
  <img src="https://img.shields.io/badge/Zabbix-CC0000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
</p>

---

# 💻 Work Experience


---

## 🏢 더존비즈온 | TAUnit (인프라운영Cell)
📅 2025.01 ~ 현재

#### 주요 업무
- Kubernetes 기반 솔루션 신규 설치 및 형상 관리
  - Ansible을 활용한 설치 자동화 시스템 구축
  - OS / K8s / DB 버전 업그레이드 시 자동화 스크립트 형상 변경 및 관리
- 고객사 서버 IP 변경시, 솔루션 재/이전 설치 지원
  - 서비스 장애 또는 고객사 서버 이전 시, K8s 클러스터 재구성 및 데이터 복원 지원
- 장애 분석 및 구조적 개선
- SaaS SSL 인증서 적용 및 갱신 (L4 Offload)
- zabbix 기반 네트워크 모니터링 구축
- JIRA 프로젝트 및 이슈 관리

---

# 주요 프로젝트

---

### 🔹 A10 클라우드 펌웨어 업데이트

**목적**  
EOS 대응 및 무중단 업그레이드 체계 확립  

**수행**
- RHEL 8 → 9
- Kubernetes 1.30 → 1.31
- CRI-O 전환

**성과**
- 무중단 업그레이드 안정화
- 업그레이드 표준 프로세스 수립

---

### 🔹 Amaranth10 설치셋 고도화

**목적**  
계정 보안 강화 및 설치 자동화 표준화  

**수행**
- install.sh 및 Ansible 구조 개선
- DB 계정 자동 생성 로직 구현
- MariaDB 10.4 → 10.11 업그레이드
- root 기반 백업 → backup 전용 계정 전환

**성과**
- 계정 자동화로 인적 오류 감소
- 보안 정책 반영된 표준 설치 체계 구축

---

### 🔹Amaranth10 인프라 신규 업데이트
**목적**  
- 서비스 모듈 및 OS 버전의 EOS(End of Support) 대응을 통해 서비스 운영 안정성과 확장성 확보

**수행**
- OS (RHEL 8.10→9.4) 및 Kubernetes(1.28→1.31) 업그레이드 기술 검토 및 안정화  
- CNI(Calico) 배포 순서 수정, CRI-O 런타임 전환 등으로 배포 오류 해결  
- JVM cgroup v2 메모리 인식 문제 분석 및 Java8 호환성 개선 방향 도출  
- SaaS 인증서 자동화 및 네트워크 구조 개선으로 배포 효율성 향상  

**성과**
- 서비스 안정성 강화 및 매출 약 7% 증가 대응 가능한 인프라 구축  

---

### 🔹Amaranth10 SaaS 네트워크 아키텍처 개선

**목적**
Spine-Leaf 기반 확장형 구조로 네트워크 병목 개선  

**주요 수행내용**  
노드 이전, 포트맵 업데이트, Zabbix 모니터링 구성  

**성과**
Spine 스위치 54포트 중 38포트 사용 → 향후 확장 대비 여유 확보 


---

## 🚀 External Projects

### ☁️ 클라우드 기반 온라인 쇼핑몰 인프라 구축 프로젝트
📅  2024.06 ~ 2024.08
<br/> **역할:** 인프라 설계 및 개발 담당
- **주요 활동내용**
  - Terraform을 활용한 IaC 도입으로 인프라 구축 시간 70% 단축  
  - AWS CloudFront + S3를 통한 정적 콘텐츠 캐싱 및 응답 속도 개선  
  - Kubernetes 기반 EKS 배포로 확장성과 가용성 확보  
  - Aurora + ElastiCache로 DB/캐시 분리, 트래픽 부하 분산  
  - CloudWatch + Slack 실시간 알림 시스템 구축으로 장애 대응 자동화  
- **성과:** 분당 20만 건 이상의 요청을 안정적으로 처리  

### 🤖 로봇 경로 예측 모델 설계
📅 2024.01 ~ 2024.11 
<br/> **역할**: 데이터 수집/전처리 및 모델 개발  

- **주요 활동내용**
  - ROS2 기반 TurtleBot4 실험 환경 구축 및 LiDAR 데이터 수집  
  - Conv-LSTM + Attention, Transformer 모델 비교 실험  
  - 시공간 패턴 학습 기반 로봇 경로 예측 모델 설계  

> **성과:** LiDAR 기반 경로 예측 가능성 입증, Conv-LSTM의 안정적 학습 성능 확인  

---

## 👣 Activities

- **CJ 올리브네트웍스 클라우드웨이브 3기 (2024.06 ~ 2024.08)**  
  - 네트워크, 리눅스, AWS, Docker, Kubernetes, IaC(Terraform) 관련 교육 및 실습  
  - 클라우드 인프라 프로젝트 수행 (Kubernetes 기반 온라인 쇼핑몰 아키텍처 설계 및 구성 경험)  
- **네이버부스트클래스 : AI Tech 준비 과정(2024.04 ~ 2024.06)**  
  - 딥러닝 네트워크 구조 및 모델 학습 원리 교육  

- **정보기술대학 '지능제어/내비게이션 연구실' 활동 (2022.09 ~ 2023.10 )**  
  -  RA(Research Assistant) 활동 (2022.11~2023.10)
      - 모션캡처(3D) 데이터를 활용한 AI 기반 캐릭터 제어 모델 연구 
      - 딥러닝 기반 모션 제어 네트워크 설계 및 애니메이션 생성 실험 수행  
      - 성과: 데이터 전처리 → 모델 설계 → 모션 출력까지의 전체 파이프라인 완성
  - TA(Teaching Assistant) 활동(2022.09~2022.11)
      - ‘프로그래밍(2)’ 수업 조교로 활동하며 Python 실습 지도 및 과제 피드백 수행  

- **KT 랜선야학 (2023.02 ~ 2023.08)**
  - 역할 : 대학생 멘토 
  -  중학생 3명 대상 AI 코디니(블록 코딩) 교육 진행  
 
- **학과 학생회 활동(2022.03 ~ 2023.12)**  
  - 역할: 임원(2022) → 부학생회장(2023)  
  - 학과 내 학생 의견 수립 및 학과 프로그램 주도 

---

> 🌱 “서버 엔지니어는 단순히 시스템을 운영하는 사람이 아니라,  
> 모두를 연결하는 든든한 다리가 되어야 한다고 믿습니다.”
