# BDA_Final_Assignment

## 1. Overview

### 😎 프로젝트 소개

BDA 학회원 이탈률 감소 및 수료율 증대를 위한 아이디어 및 전략 제시

### 🚀 프로젝트 목적
BDA (Big Data Analysis 학회) 의 학회 운영 과정 속에서 매 기수마다 반복적으로 발생하는 학회원 이탈 문제는 운영의 효율성을 저하시킬 뿐 아니라, 학회원들에게 제공할 수 있는 경험의 질을 낮추는 요인이 됩니다. 따라서 학회원들의 이탈률은 줄이고 수료율을 높이기 위한 아이디어 및 전략을 도출하고자 합니다. 


#### 목적

| 항목                                                                                                                 |내용                  |
|---|---|
| 수료율 증가 | 프로그램의 실효성 및 교육적 가치를 대내외적으로 입증하기 위해, <br> BDA 학회원들의 수료율을 체계적으로 높이고자 합니다. 이를 통해 학회원 개개인의 목표 달성뿐만 아니라, <br> 프로그램의 신뢰성과 지속 가능성을 강화할 수 있습니다. |
| 이탈률 감소 | 학회원들이 프로그램 중도에 이탈하는 비율을 최소화하여, <br> 교육 과정의 연속성과 참여자들의 몰입도를 높이고자 합니다.<br>  이탈률 감소는 학회원의 만족도 향상은 물론, 학회의 명성과 대외 경쟁력 제고에도 기여합니다. |

#### 기대 효과

| 항목                                                                              | 내용                                                                 |
|---|---|
| 학회의 안정적인 운영 | 학회원들의 적극적인 참여와 다양한 행사 및 프로그램 운영을 통해, <br> 학회 전반의 조직 안정성과 지속적인 성장 기반을 마련할 수 있습니다. <br> 이는 참여율 증진, 소속감 강화, 그리고 학회 내외부의 신뢰도 제고로 이어져, <br> 장기적으로 학회의 발전과 영향력 확대에 기여할 것입니다. |
| 학회원의 만족감 상승 | 학회원들에게 양질의 교육 경험과 다양한 성장 기회를 제공함으로써, 학회원들의 전반적인 만족도를 크게 향상시킬 수 있습니다. <br> 이는 수료율 증가와 더불어, 학회원들의 긍정적인 피드백과 추천을 유도하여 새로운 인재 유입 및 학회의 지속적인 발전을 촉진할 것으로 기대됩니다. |

</br>

---


## 2. 팀원 소개

|<img src="https://github.com/user-attachments/assets/6414e203-68b9-439e-b582-eb04db032889" width="200px">|<img src="https://github.com/user-attachments/assets/f03cd9c5-824e-41f2-868f-ee2a234e59bd" width="200px">|사진|
|:---:|:---:|:---:|
|김혜원|박찬우|변해민|

</br>

---

## 3. 프로젝트 기간 및 수행 내용

| 기간               | 수행 내용                                                   |
|--------------------|------------------------------------------------------------|
| 2025.02.06 ~ 2025.02.12 | - 데이터 탐색적 분석(EDA) 수행 <br>- merge 관련 이슈 정리|
| 2025.02.12 ~ 2025.02.16 | - 관련 논문 및 통계 이론 탐색<br>- 세그먼트 분류 요소 정리 <br>- 학회원 ID 관련 이슈 정리 <br> - 학회 수료율, 이탈률 관련 문제점 정리          |
| 2025.02.16 ~ 2025.02.19 | - 세그먼트별 특성 분석 <br>- 가설 설정 <br>- 인사이트 도출 및 시각화|
| 2025.02.19 ~ 2025.02.21 | - 아이디어 최종 정리 <br>- BDA 최종과제 보고서 작성 |


</br>


---
## 4. 프로젝트 환경 및 구성 요소 

### 👩‍💻 Tech stack
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

</br>


### 📊 사용 데이터

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

### 👾 데이터 전처리

| 항목 | 내용 |
|------|------|
| null 값 처리 | member 테이블의 job 컬럼에서 null 값을 'Unknown'으로 대체하여 데이터 완전성 보장 및 분석 오류 최소화 |
| 학과별 전공자/비전공자 구분 | major1_1과 major1_2 컬럼 병합 후 major 컬럼 생성 (null → 빈 문자열), 전공 여부 식별 용이화 |
| 전공 카테고리 매핑 | 정의된 키워드 기반으로 map_major 컬럼 생성 (전공 키워드: '전공', 미존재: '비전공'), null 값 'X' 처리 |
| what_to_gain 데이터 정리 | 매핑 딕셔너리 활용해 컬럼 값 간략화 및 표준화, 학회 참여 목적 효과적 분류 구현 |
| 유효 코드(A~G) 필터링 | desired_job 컬럼 값 중 A~G 코드만 filtered_job으로 추출, 비유효 값은 '기타'로 통합 |
| 중복 ID 정리 | 중복 행 식별 후 동일 그룹 ID 통합, 데이터 중복 제거 및 정보 일관성 확보 |
| 포인트 계산 | bonus/minus 포인트 합산 연산 수행, point_df 생성으로 학회원 총점 평가 시스템 구축 |

</br>

### 🫛 EDA

| 항목 | 내용 |
|------|------|
| 세그먼트 별 지원 동기 | 각 세그먼트의 학회원들이 BDA에 지원한 동기를 시각화 |
| 세그먼트 별 이벤트 만족도 | 각 세그먼트 별로 BDA와 관련된 다양한 이벤트에 대한 만족도를 시각화 (bda_bootcamp, bda_wave, bda_job 항목별, 만족도 조사에 참여하지 않은 경우 제외) |
| 세그먼트 별 이벤트 참여 횟수 | 각 세그먼트가 다양한 이벤트에 얼마나 참여했는지 시각화 |
| X 항목 제외 세그먼트 별 이벤트 참여 횟수 | 'X' 항목을 제외한 각 세그먼트가 이벤트에 얼마나 참여했는지 시각화 |
| 세그먼트 별 전체적인 학회 점수 | 각 세그먼트의 학회원들이 BDA에 대한 전반적인 만족도를 시각화 (만족도 조사에 참여하지 않은 경우 제외) |
| 세그먼트 별 학회 운영 점수 | 각 세그먼트의 학회원들이 BDA 운영에 대해 어떻게 평가하는지 시각화 (만족도 조사에 참여하지 않은 경우 제외) |
| 세그먼트 별 스터디 점수 | 각 세그먼트의 학회원들이 스터디에 대해 어떻게 평가하는지 시각화 (만족도 조사에 참여하지 않은 경우 제외) |
| 세그먼트 별 네이버 카페 추천 점수 | 각 세그먼트의 학회원들이 카페에 대해서 어떻게 평가하는지 시각화 (cafe_recommendation) |
| 세그먼트 별 조별활동 점수 | 각 세그먼트의 학회원들이 조별활동에 대해 어떻게 평가하는지 시각화 (만족도 조사에 참여하지 않은 경우 제외) |
| 기존 카테고리 그룹 재정의 후 각 카테고리의 학회원 수 비교 | '우수 + 수료 학회원'과 '미수료 학회원'의 수를 비교하여 두 그룹의 규모를 확인 |
| filtered_job 컬럼의 값을 쉼표로 분리하여 각 카테고리별 직업 개수 시각화 | 각 카테고리에서 어떤 직업이 얼마나 많은지 분석하여 분포를 파악 |
| 정수형 데이터를 문자열로 변환 후, 여러 컬럼별 데이터 분포를 시각화하여 카테고리별 비교 | 여러 생활 주기에 걸쳐 데이터 값을 시각화하여 각 카테고리의 특징을 파악하고 비교 |
| 카테고리별 주간 평균 값을 선 그래프로 시각화하여 주간 트렌드 분석 | 카테고리별 주가 시계열 데이터를 분석하여 시간이 지남에 따라 변화하는 경향성을 확인 |
| 카테고리별 주간 과제 평균 값을 선 그래프로 시각화 | 각 카테고리의 학회원들이 주간 과제에 대해 평균적으로 어떻게 수행했는지 분석 |
| 카테고리별 주간 출석 평균 값을 선 그래프로 시각화 | 각 카테고리의 학회원들이 주간 출석에 대해 평균적으로 어떻게 수행했는지 분석 |
| 그룹과 카테고리별 주간 출석 평균 값을 선 그래프로 시각화 | 그룹과 카테고리별로 학회원들이 주간 출석에 대해 평균적으로 어떻게 수행했는지 세부적으로 분석 |
| 그룹과 카테고리별 주간 과제 평균 값을 선 그래프로 시각화 | 그룹과 카테고리별로 학회원들이 주간 과제에 대해 평균적으로 어떻게 수행했는지 세부적으로 분석 |


</br>

---
## 6. 한 줄 소감 

| 팀원               | 소감                                                  |
|--------------------|------------------------------------------------------------|
| 김혜원 | ㅇㅇㅇ       |
| 박찬우 | 항상 공부를 하거나 시험을 볼 때 정제되어 있는 데이터만 만져봤었다. 하지만 학회에서 제공하는 날 것의 데이터를 만져보니 생각할 것이 여간 많은 게 아니었다. 학회원 ID 중복 문제부터 어떤 가설을 세우고 원하는 바를 찾아낼지 많은 고민을 할 수 있는 과제였다.   |
| 변해민 | ㅇㅇㅇ       |
