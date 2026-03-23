# 📘 Portfolio
<table> <tr> <td width="220" valign="top">

<img src="https://github.com/user-attachments/assets/0e230d34-406c-4a11-85f5-be59cd35a64f" width="200" alt="양채은 프로필 사진"/>

</td>
<td width="75%" valign="top" style="padding-left:20px;">

## 💡 모두를 연결하는 든든한 다리,  서버 엔지니어 **양채은**입니다.

안녕하세요.  
서비스의 **안정성, 확장성, 운영 효율**을 함께 고민하는 **인프라 중심 서버 엔지니어**입니다.

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
- **Blog** : https://akizakic.tistory.com/

<br/>

## 🏫 Education

**인천대학교 | 정보통신공학과 (부전공: 미래자동차연계전공)**  
📅 2021.03 ~ 2025.02  
📊 GPA : 4.0 / 4.5  

<br/>

## 📄 Certificate

- **2025.09** Certified Kubernetes Administrator (CKA)  
- **2024.09** AWS Certified Solutions Architect - Associate
- **2024.06** 정보처리기사  
- **2024.09** 리눅스마스터 2급  
- **2023.10** SQL 개발자 (SQLD)
  
<br/>

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

## 💻 Work Experience

<br/>

### 🏢 더존비즈온 | 클라우드서비스본부
📅 2025.01 ~ 재직중

#### 주요 업무
- **Kubernetes 기반 ERP 솔루션 신규 설치 및 형상 관리**
  - Ansible 기반 설치 자동화 스크립트 관리 및 표준화
  - OS / Kubernetes / DB 버전 업그레이드에 따른 설치셋 구조 개선
- **고객사 서버 이전 및 재설치 지원**
  - 서버 IP 변경, 인프라 이전, 장애 발생 시 클러스터 재구성 및 데이터 복원 지원
- **플랫폼 운영 안정화 및 구조 개선**
  - EOS 대응, 서비스 호환성 검토, 배포 오류 분석 및 운영 리스크 최소화
- **인프라 운영**
  - 네트워크 구조 개선 및 서버 이전/증설
  - SaaS SSL 인증서 적용 및 갱신 (L4 Offload)
  - Zabbix 기반 모니터링 구성

<br/>

## 주요 프로젝트

### 🔹 Amaranth10 SaaS 인프라 펌웨어 업데이트
📅 2025.04 ~ 2025.08
<br/>

**목적**  
플랫폼 모듈 및 펌웨어 EOS 대응을 통해 운영 안정성과 확장성 확보

**주요 수행**
- OS(RHEL 8.10 → 9.4) 및 Kubernetes(1.28 → 1.31) 업그레이드 기술 검토 및 안정화
- Powerflex(CSI Driver), SDS 등 펌웨어 업데이트 지원(벤더사 진행)
- 개발팀 및 벤더사와 협업해 호환성 이슈 원인 분석 및 대응

**성과**
- 서비스 안정성 강화
- 변화하는 플랫폼 환경에 대응 가능한 업그레이드 기반 확보

<br/>

### 🔹 Amaranth10 설치셋 고도화
📅 2026.01 ~ 2026.03
**목적**  
계정 보안 강화 및 설치 자동화 표준화

**주요 수행**
- `install.sh` 및 Ansible 설치 구조 개선
- 단순 YAML 기반 구조를 role / playbook 중심 구조로 정비
- DB 계정 자동 생성 로직 구현
- MariaDB 10.4 → 10.11 업그레이드 대응
- root 기반 백업 방식에서 backup 전용 계정 방식으로 전환

**성과**
- 설치 자동화 표준화 및 운영 효율 향상
- 계정/백업 구조 개선을 통한 보안성 강화
- 반복 작업 시 인적 오류 감소

<br/>

### 🔹 Amaranth10 SaaS 네트워크 아키텍처 개선
📅 2025.03 ~ 2025.06
**목적**  
Spine-Leaf 기반 확장형 구조를 통해 네트워크 병목 완화 및 확장성 확보

**주요 수행**
- 노드 이전 및 포트맵 재정비
- 네트워크 구조 개선 및 확장 대응 기반 마련
- Zabbix 기반 모니터링 구성

**성과**
- Spine 스위치 54포트 중 38포트 사용 수준으로 정비
- 향후 고객 증가에 대응 가능한 포트 여유 확보
- 전년도 대비 고객사 수 68% 증가에 대응 가능한 인프라 운영 환경 강화

---

## 🚀 External Projects

### ☁️ 클라우드 기반 온라인 쇼핑몰 인프라 구축 프로젝트
📅 2024.06 ~ 2024.08
**역할:** 인프라 설계 및 구축 담당

#### 주요 수행
- Terraform 기반 IaC 도입으로 인프라 구축 시간 단축
- AWS CloudFront + S3를 활용한 정적 콘텐츠 캐싱 구조 설계
- Kubernetes 기반 EKS 배포 환경 구성
- Aurora + ElastiCache를 통한 DB/캐시 분리
- CloudWatch + Slack 실시간 알림 시스템 구축

#### 성과
- 약 20만 건 규모의 사용자 요청 처리 가능한 구조 설계
- 대용량 트래픽 환경에서의 안정성과 확장성 고려 경험 확보

<br/>

### 🤖 로봇 경로 예측 모델 설계
📅 2024.01 ~ 2024.11
**역할:** 데이터 수집/전처리 및 모델 개발

#### 주요 수행
- ROS2 기반 TurtleBot4 실험 환경 구축 및 LiDAR 데이터 수집
- Conv-LSTM + Attention, Transformer 모델 비교 실험
- 시공간 패턴 학습 기반 경로 예측 모델 설계
- 다양한 센서/위치/이미지 데이터 수집 구조 설계 및 전처리

#### 성과
- LiDAR 기반 경로 예측 가능성 확인
- 데이터 구조와 학습 환경의 중요성 체감
- 구현과 운영 환경의 차이를 이해하며 인프라 관심으로 확장
  
<br/>

### 🎧 위험 소리 감지 헤드셋 시스템 개발
📅 2024.03 ~ 2024.06  
**역할:** 라즈베리파이 기반 음성 수집, MQTT 통신, AI 분류 모델 연동

#### 주요 수행
- USB 마이크와 라즈베리파이를 활용해 주변 소리 수집 및 전처리
- MQTT 프로토콜 기반으로 라즈베리파이와 로컬 서버 간 음성 데이터 송수신 구현
- MFCC 기반 특징 추출 및 MLP 모델을 활용한 위험 소리 분류
- 분류 결과를 라즈베리파이로 다시 전달해 경고음 출력 구조 구현

#### 성과
- 위험 소리 감지부터 경고 출력까지 이어지는 IoT 기반 실시간 처리 흐름 구현
- AI 모델, 네트워크 통신, 디바이스 연동을 하나의 시스템으로 통합한 경험 확보

---

## 👣 Activities

### ☁️ CJ 올리브네트웍스 클라우드웨이브 3기
📅 2024.06 ~ 2024.08
- 네트워크, Linux, AWS, Docker, Kubernetes, Terraform 관련 교육 및 실습
- Kubernetes 기반 온라인 쇼핑몰 인프라 프로젝트 수행
- 클라우드 환경에서의 아키텍처 설계 및 운영 흐름 학습

### 🤖 네이버 부스트캠프 AI Tech 준비과정
📅 2024.04 ~ 2024.06
- 딥러닝 네트워크 구조 및 학습 원리 교육 이수
- 모델 구조에 대한 이해와 실습 중심 학습 수행

### 🧪 정보기술대학 지능제어/내비게이션 연구실
📅 2022.09 ~ 2023.10
#### RA (Research Assistant) 
- 모션캡처(3D) 데이터를 활용한 AI 기반 캐릭터 제어 모델 연구
- 딥러닝 기반 모션 제어 네트워크 설계 및 애니메이션 생성 실험 수행
- 데이터 전처리부터 모델 설계, 출력 검증까지 전체 파이프라인 경험

#### TA (Teaching Assistant) 
- ‘프로그래밍(2)’ 수업 조교 활동
- Python 실습 지도 및 과제 피드백 수행

### 🎓 KT 랜선야학
📅 2023.02 ~ 2023.08
- 대학생 멘토로 활동
- 중학생 3명 대상 AI 코디니(블록 코딩) 교육 진행

### 🤝 학과 학생회 활동
📅 2022.03 ~ 2023.12
- 역할: 임원(2022) → 부학생회장(2023)
- 학과 프로그램 기획 및 학생 의견 수렴
- 소통과 협업을 기반으로 학과 분위기 활성화에 기여

---

> 🌱 “서버 엔지니어는 단순히 시스템을 운영하는 사람이 아니라,  
> 모두를 연결하는 든든한 다리가 되어야 한다고 믿습니다.”
