# 🚍 AutocarZ - 자율주행 중 로드킬 안전 강화 및 자동 신고 서비스

# 🙋‍♂️🙋‍♀️ 팀원 소개

<table>
  <tr>
    <th>김지영</th>
    <th>이유석</th>
    <th>사석훈</th>
    <th>신윤서</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/3c347b94-3b95-4d42-82ea-ee20c7dfcc45" width="100"/></td>
    <td><img src="https://github.com/user-attachments/assets/44c93308-1e79-4dc5-8ac0-a2dbd30785e8" width="100"/></td>
    <td><img src="https://github.com/user-attachments/assets/26c18044-d8ab-4b8b-a5a9-fb6ccd8b1071" width="100"/></td>
    <td><img src="https://github.com/user-attachments/assets/9b3cd675-6764-4b3e-bca3-7a356b20843f" width="100"/></td>
  </tr>
  <tr>
    <td>PM<br>데이터 파이프라인</td>
    <td>DB 구축<br>클라우드 관리</td>
    <td>AI<br>프론트엔드</td>
    <td>AI<br>백엔드</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/jiyoung1634">
        <img src="https://img.shields.io/badge/GitHub-Link-black?logo=github&style=flat"/>
      </a>
    </td>
    <td>
      <a href="https://github.com/LYSS-LGU">
        <img src="https://img.shields.io/badge/GitHub-Link-black?logo=github&style=flat"/>
      </a>
    </td>
    <td>
      <a href="https://github.com/Clear-head">
        <img src="https://img.shields.io/badge/GitHub-Link-black?logo=github&style=flat"/>
      </a>
    </td>
    <td>
      <a href="https://github.com/irisyshin">
        <img src="https://img.shields.io/badge/GitHub-Link-black?logo=github&style=flat"/>
      </a>
    </td>
  </tr>
</table>

-------------------------------------------------------------

# 프로젝트 기획서


## 1. 프로젝트 개요
- 프로젝트 주제 : **도로 위 야생동물 실시간 인식 및 대응 시스템 : AI기반 자율주행 안전 강화 솔루션 설계**
- 문제정의 : **주행 중 도로에 갑자기 나타나는 "야생동물"을 효과적으로 감지하여 사고 예방과 충돌 이후 신속하게 대응할 수 있는 체계 부재**
- 목표 : **데이터 기반 인사이트 도출 및 시각적 보고**

---------------------------------------------------------------------------------------------


### 프로젝트 기획서 다이어그램
![image](https://github.com/user-attachments/assets/33eac463-c086-4af8-87b1-f4d72e2dea94)






## 2. 프로젝트 일정 

| 작업 항목                  | 시작 날짜   | 종료 날짜   | 기간(일) |
|---------------------------|------------|------------|---------|
| 프로젝트 정의 및 계획 수립  | 2025-06-25 | 2025-06-25 | 1       |
| 자료 조사 및 벤치마킹       | 2025-06-25 | 2025-06-25 | 1       |
| 아이디어 도출 및 시나리오 작성 | 2025-06-25 | 2025-06-26 | 2       |
| 요구사항 도출 및 WBS 작성   | 2025-06-25 | 2025-06-26 | 2       |
| Prototype 개발 및 검토     | 2025-06-25 | 2025-06-06 | 2       |
| 최종 검토 및 발표 준비     | 2025-06-26 | 2025-06-27 | 2       |
| 프로젝트 발표              | 2025-06-27 | 2025-06-27 | 1       |
 
  --------------------------

# 작업 분할 구조 (WBS)


| 구분         | 역할분류 | 작업                           | 기능 상세          | 담당자   |  완료 여부  |
|--------------|----------|-------------------------------|-------------------|----------|--------------|
| **기획 및 설계** | 공통     | 기획서 작성                   |                 | 홍길동   |               |
|              | 공통     | 기능명세서 작성               |                     | 홍길동   |               |
|              | 공통     | API 연동 규격서 작성          |                     | 홍길동   |               |
|              | 공통     | ERD 작성                      |                    | 홍길동   |               |
|              | 공통     | WBS 작성                      |                    | 홍길동   |               |
|              | 공통     | Sequence Diagram 작성         |                    | 홍길동   |               |
|              | 공통     | 사용자 요구사항 명세서 작성   |                     | 홍길동    |                |
|              | 공통     | 제공자 요구사항 명세서 작성   |                     | 홍길동    |                |
|              | FE      | 기술 스택 선정               |                     | 홍길동     |                |
|              | BE      | 기술 스택 선정                |                     | 홍길동    |                |
|              | 공통     | Git 커밋 컨벤션 정의          |                     | 홍길동   |                |
|              | 공통     | Git 브랜치 전략 정의          |                     | 홍길동   |                |
|              | 공통     | 코드 컨벤션 정의              |                     | 홍길동   |                |
|              | 공통     | 디자인 concept 정의          |                     | 홍길동   |                |
|              | FE      | 프로젝트 디렉토리 구조 설정   |                     | 홍길동    |                |
|              | BE      | 프로젝트 디렉토리 구조 설정   |                     | 홍길동    |                |
|              | FE      | 프로젝트 생성                |                     | 홍길동    |                |
|              | BE      | 프로젝트 생성                |                     | 홍길동    |                |
|              | FE      | 프로젝트 설정                |                     | 홍길동    |                |
|              | BE      | 프로젝트 설정                |                     | 홍길동    |                |

  ------------------------------

# 요구사항 정의서

## 1. 기능 요구사항
- [ ] 영상 기반 객체 인식 기능
- [ ] 객체 미인식 시 자동 패스 처리 기능
- [ ] 객체 상태 분석 기능 (정지 상태 vs 움직임 상태 분류)
- [ ] 움직임 상태일 경우, 다음 타이밍 기준 재판단 기능
- [ ] 객체 인식 시 사용자 알림 기능
- [ ] 인식된 이미지를 DB에 저장 및 향후 학습 데이터로 활용 가능
- [ ] 서버에서 일괄 사용자 알림 발송 기능
- [ ] 객체 인식 위치 확인 기능
- [ ] 객체 분류 기능
- [ ] 자주 인식되는 위치 식별 기능

## 2. 비기능 요구사항
- [ ] 객체 인식 시 1초 이내 응답 처리
- [ ] 객체 인식은 실시간 처리 동작
- [ ] 객체 종류 확장 가능
- [ ] 다중 수신 요청에 대해 병렬 처리
- [ ] 객체 인식 후 알림까지 5초 이내 수행
- [ ] DB 외부 접근 불가, 오직 서버만 가능 (보안성 강화)

----------------------------

# 프로젝트 설계서

## 1. 시스템 아키텍처
- **구성 요소**:
  - 데이터 수집 모듈
  - 데이터 전처리 모듈
  - 데이터 분석 및 시각화 모듈

## 2. 데이터 설계
- **데이터 흐름**: 원천 데이터 → 전처리 → 분석 → 결과
- **주요 데이터 속성**:
  - 속성 이름: [예: user_id, timestamp, value]
  - 데이터 유형: [정량, 정성]

## 3. 기술 스택
### **📌 데이터 수집**
- 사용 언어 : ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
- 사용 도구 : ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white) ![API](https://img.shields.io/badge/API-005571?style=flat&logo=api&logoColor=white)

### **📊 데이터 분석**
- 분석 라이브러리 : ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/Numpy-013243?style=flat&logo=numpy&logoColor=white)
- 머신러닝 : ![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

### **📈 시각화**
- 시각화 도구 : ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-1E3C72?style=flat) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

### **🤖 딥러닝 / AI**
- 모델 : ![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat&logo=YOLO&logoColor=black) ![ResNet50](https://img.shields.io/badge/ResNet50-FF5959?style=flat)
- 프레임워크 : ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

### 🗃️ 인프라 & 배포
- 클라우드 : ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) ![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat&logo=amazon-ec2&logoColor=white)
- 데이터베이스 : ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)


## 4. 예상 문제 및 해결 방안
- **문제**: 도로공사 API 미제공  
- **해결 방안**: 로컬 테스트 서버 구현해 자동 신고 시스템 구축
