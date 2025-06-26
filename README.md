# BDA_Final_Assignment
😊 😎 🛠️ 🔍 ✅ ❌ 💡 🚀 📊 🗂️ 📌

🎯 📦 🤖 🧠 📝 🕒 📁 🔧 🏁 🧩
## 1. Overview

### 프로젝트 소개

BDA 학회원 이탈률 감소 및 수료율 증대를 위한 아이디어 및 전략 제시

### 프로젝트 목적
BDA (Big Data Analysis 학회) 의 학회 운영 과정 속에서 매 기수마다 반복적으로 발생하는 학회원 이탈 문제는 운영의 효율성을 저하시킬 뿐 아니라, 학회원들에게 제공할 수 있는 경험의 질을 낮추는 요인이 됩니다. 따라서 학회원들의 이탈률은 줄이고 수료율을 높이기 위한 아이디어 및 전략을 도출하고자 합니다. 


#### 목적

| 항목       | 내용                                                                 |
|------------|----------------------------------------------------------------------|
|수료율 증가|프로그램의 실효성에 대한 의문이 제기될 수 있으므로 BDA 학회원들의 수료율을 높입니다|
|이탈률 감소|BDA 학회원들의 이탈률을 감소시킵니다|

#### 기대 효과

| 항목       | 내용                                                                 |
|------------|----------------------------------------------------------------------|
|학회의 안정적인 운영|학회원의 적극적인 참여와 더불어 다양한 행사를 진행하고 참여율을 높임으로써 안정적인 운영을 추진할 수 있습니다|
|학회원이 만족감 상승|학회원들의 경험의 질을 높임으로써 BDA 정규 수업 과정을 수료율을 높일 수 있습니다|

## 2. 팀원 소개

|<img src="image/김혜원_사진.jpeg" width="200px">|<img src="https://github.com/B2O1/BDA_Final_Assignment/issues/1" width="200px">|사진|
|:---:|:---:|:---:|
|김혜원|박찬우|변해민|

---

## 3. 프로젝트 기간 및 수행 내용

| 기간               | 수행 내용                                                   |
|--------------------|------------------------------------------------------------|
| 2025.02.06 ~ 2025.02.12 | - 데이터 탐색적 분석(EDA) 수행 <br>- merge 관련 이슈 정리|
| 2025.02.12 ~ 2025.02.16 | - 관련 논문 및 통계 이론 탐색<br>- 세그먼트 분류 요소 정리 <br>- 학회원 ID 관련 이슈 정리 <br> - 학회 수료율, 이탈률 관련 문제점 정리          |
| 2025.02.16 ~ 2025.02.19 | - 세그먼트별 특성 분석 <br>- 가설 설정 <br>- 인사이트 도출 및 시각화|
| 2025.02.19 ~ 2025.02.21 | - 아이디어 최종 정리 <br>- BDA 최종과제 보고서 작성 |


---
## 4. 프로젝트 환경 및 구성 요소 

### Tech stack
#### 사용 프로그램

| 항목            | 내용                                               |
|-----------------|----------------------------------------------------|
| Language        | <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">                                             |
| Development     | <img src="https://img.shields.io/badge/googlecolab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white">    <img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">   |
| Collaboration   |    <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">                          |

#### 사용 라이브러리

| 항목            | 내용                                               |
|-----------------|----------------------------------------------------|
| <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">         | <img src="https://img.shields.io/badge/pandas-3776AB?style=for-the-badge&logo=python&logoColor=white">            <img src="https://img.shields.io/badge/numpy-3776AB?style=for-the-badge&logo=python&logoColor=white">   <img src="https://img.shields.io/badge/matplotlib-3776AB?style=for-the-badge&logo=python&logoColor=white">   <img src="https://img.shields.io/badge/seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white">  <img src="https://img.shields.io/badge/sklearn-3776AB?style=for-the-badge&logo=python&logoColor=white">   |


### 사용 데이터

#### member

※ re_registration 아래 피처들의 결측치 값들은 설문조사를 제출하지 않은 학회원

| 속성명 | 속성 설명 |
| --- | --- |
| id | 처리된 학회원 번호 |
| class_id | 분반 코드 |
| major1_1 | 제 1전공 |
| major1_2 | 제 2전공 |
| job | 직업 |
| re_registration | 재등록 여부 |
| whyBDA | 학회에 들어온 이유 |
| time_input | 투자 가능 시간 |
| what_to_gain | 학회에서 얻고자 하는 것 |
| desired_job | 희망 직무 |
| desired_job_data_ability | 희망 직무 데이터 필요 역량 |
| proficiency_sql | sql 활용 능력 |
| proficiency_python | python 활용 능력 |
| study_experience | 데이터 관련 스터디 참여 횟수 |
| club_experience | 데이터 관련 동아리 참여 횟수 |
| society_experience | 데이터 관련 학회 참여 횟수 |
| contest_count | 공모전 참여 횟수 |
| project_count | 프로젝트 참여 횟수 |

#### point

| 속성명 | 속성 설명 |
| --- | --- |
| id | 처리된 학회원 번호 |
| class_id | 분반 코드 |
| bonus | 상점 |
| minus | 벌점 |
| point_date | 상/벌점 부여 날짜 |

#### attendance

| 속성명 | 속성 설명 |
| --- | --- |
| id | 처리된 학회원 번호 |
| class_id | 분반 코드 |
| week_n | n주차 출석 여부(2: 출석, 1: 지각, 0: 결석) |

#### assignment

※ 결측치의 경우 결석과 동일

| 속성명 | 속성 설명 |
| --- | --- |
| id | 처리된 학회원 번호 |
| class_id | 분반 코드 |
| week_n | n주차 과제 제출 여부(2: 제출, 1: 지각 제출: 0: 미제출) |

#### class

| 속성명 |
| --- |
| class_id |
| class_name |
| class_lang |

#### group_activity

| 속성명 | 속성 설명 |
| --- | --- |
| id | 처리된 학회원 번호 |
| class_id | 분반 코드 |
| group_master | 조장 여부 |
| on_offline | 온/오프라인 |
| group_leave | 조별활동 이탈 여부 |

#### event_participation

| 속성명 | 속성 설명 |
| --- | --- |
| id | 처리된 학회원 번호 |
| class_id | 분반 코드 |
| event_name | 참여한 행사 이름 |
| event_date | 행사 날짜 |

#### satisfaction_survey

※ 행사, 조별활동, 카페 점수 피처의 결측치는 학회원이 참여 하지 않아서 점수 부여를 하지 않은 값들

| 속성명 | 속성 설명 |
| --- | --- |
| survey_month | 설문조사 월 |
| class_id | 분반 코드 |
| id | 처리된 학회원 번호 |
| class_recommendation | 분반 추천 점수 |
| operating | 학회 운영 점수 |
| bda_wave | wave 행사 점수 |
| bda_study | study 행사 점수 |
| bda_job | job 행사 점수 |
| bda_bootcamp | bootcamp 행사 점수 |
| overall_bda | 전반적인 학회 점수 |
| group_project | 조별활동 점수 |
| cafe_recommendation | 네이버 카페 추천 점수 |

#### report_participation

| 속성명 | 속성 설명 |
| --- | --- |
| id | 처리된 학회원 번호 |
| class_id | 분반 코드 |
| report | 참여한 설문 조사 이름 |
| report_date | 설문조사 날짜 |

---
## 5. 프로젝트 내용

### 데이터 전처리

| 항목               | 수행 내용                                                   |
|--------------------|------------------------------------------------------------|
| 결측값 처리 | - ㅇㅇㅇ<br>- ㅇㅇ         |
| 2025.04.08 ~ 2025.04.14 | - 고객 세분화 기준 설정<br>- K-means 등 클러스터링 모델링 수행         |
| 2025.04.15 ~ 2025.04.21 | - 세그먼트별 특성 분석<br>- 인사이트 도출 및 시각화                   |
| 2025.04.22 ~ 2025.04.28 | - 마케팅 전략 수립 및 제안서 작성<br>- 프로젝트 최종 발표 준비         |

### EDA

| 항목               | 수행 내용                                                   |
|--------------------|------------------------------------------------------------|
| 결측값 처리 | - ㅇㅇㅇ<br>- ㅇㅇ         |
| 2025.04.08 ~ 2025.04.14 | - 고객 세분화 기준 설정<br>- K-means 등 클러스터링 모델링 수행         |
| 2025.04.15 ~ 2025.04.21 | - 세그먼트별 특성 분석<br>- 인사이트 도출 및 시각화                   |
| 2025.04.22 ~ 2025.04.28 | - 마케팅 전략 수립 및 제안서 작성<br>- 프로젝트 최종 발표 준비         |

### dd

| 항목               | 수행 내용                                                   |
|--------------------|------------------------------------------------------------|
| 결측값 처리 | - ㅇㅇㅇ<br>- ㅇㅇ         |
| 2025.04.08 ~ 2025.04.14 | - 고객 세분화 기준 설정<br>- K-means 등 클러스터링 모델링 수행         |
| 2025.04.15 ~ 2025.04.21 | - 세그먼트별 특성 분석<br>- 인사이트 도출 및 시각화                   |
| 2025.04.22 ~ 2025.04.28 | - 마케팅 전략 수립 및 제안서 작성<br>- 프로젝트 최종 발표 준비         |


---
## 6. 한 줄 소감 

| 팀원               | 소감                                                  |
|--------------------|------------------------------------------------------------|
| 김혜원 | ㅇㅇㅇ       |
| 박찬우 | ㅇㅇㅇ       |
| 변해민 | ㅇㅇㅇ       |
