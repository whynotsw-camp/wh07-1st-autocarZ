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

## 1. 단계별 작업 구성
### 1. 기획
1.1. 문제 정의  
1.2. 데이터 요구사항 정의  

### 2. 데이터 수집 및 준비
2.1. 데이터 소스 조사  
2.2. 데이터 수집 및 저장  
2.3. 데이터 전처리  

### 3. 데이터 분석 및 모델링
3.1. 데이터 탐색 및 시각화  
3.2. 모델 선택 및 학습  
3.3. 성능 평가  

### 4. 결과 도출 및 보고
4.1. 결과 요약  
4.2. 보고서 작성  
4.3. 최종 발표

  ------------------------------

# 요구사항 정의서

## 1. 기능 요구사항
- [ ] 데이터 수집 기능: [수집 대상 및 방식]
- [ ] 데이터 전처리 기능: [결측치 처리, 이상치 제거 등]
- [ ] 분석 기능: [사용할 알고리즘 또는 분석 기법]
- [ ] 시각화 기능: [대시보드, 차트, 그래프]

## 2. 비기능 요구사항
- [ ] 시스템 안정성: 데이터 처리 시 오류 발생 최소화
- [ ] 성능: 데이터 처리 및 분석 시간 최소화
- [ ] 확장성: 새로운 데이터 추가 및 확장 가능

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

---
### **📊 데이터 분석**
- 분석 라이브러리 : ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/Numpy-013243?style=flat&logo=numpy&logoColor=white)
- 머신러닝 : ![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

---
### **📈 시각화**
- 시각화 도구 : ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-1E3C72?style=flat) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

---
### **🤖 딥러닝 / AI**
- 모델 : ![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat&logo=YOLO&logoColor=black) ![ResNet50](https://img.shields.io/badge/ResNet50-FF5959?style=flat)
- 프레임워크 : ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

---
### 🗃️ 인프라 & 배포
- 클라우드 : ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) ![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat&logo=amazon-ec2&logoColor=white)
- 데이터베이스 : ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)


## 4. 예상 문제 및 해결 방안
- **문제**: 데이터 불균형  
  **해결 방안**: SMOTE 기법 활용
