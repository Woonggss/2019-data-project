# 🚴‍♂️ 따릉이 데이터 분석 및 전략 제안

2019년 2학기 교내 수업에서 진행한 Term Project 입니다. 주제 선정부터 implication까지 데이터 분석 프로젝트의 모든 과정을 수행하였습니다.

## 1. 주제 선정, 데이터 탐색, 데이터 가공 및 전처리

### 1.1. 주제 선정

따릉이는 서울시에서 운영하는 무인 공공자전거 대여 서비스입니다. 일상 속에 자리잡은 스마트 모빌리티의 대표적인 사례이며, 이용자 수가 매년 꾸준히 증가해왔습니다. 

이러한 배경에 근거하여 사회적 유용성이 있을 것으로 생각하고, "따릉이 이용자 분석을 통한 따릉이의 지속적인 성장 방안 제시"를 주제로 선정하였습니다.

### 1.2. 데이터 탐색

데이터를 탐색하면서, 분석 주제를 구체화하였습니다. 1.1과 1.2는 순서대로 정확히 나뉜 과정은 아니며, 데이터 분석 기법을 적용할 수 있도록 구체화 될 때까지 두 과정을 반복하였습니다.

따릉이 이용 데이터는 [서울 열린데이터광장](https://data.seoul.go.kr/dataList/datasetList.do) 에서 내려받아 활용하였습니다.

#### 1.2.1. 현황 조사

데이터를 어떻게 활용할 수 있을 지 생각해보기 위해, 현황 조사를 수행하였습니다. 조사에 따르면, 이용 시간대를 기준으로 평일 퇴근 시간대와 휴일 오후 시간대의 이용자가 많았습니다. 따릉이가 통근용으로 많이 활용되고, 또 한강 공원에서의 여가용으로도 활용이 많이 되고 있다고 판단하였습니다. 

#### 1.2.2. 분석 대상 및 분석 기법 선정

이에 따라 분석 대상으로 관련 있는 5개의 구(종로구, 중구, 영등포구, 서대문구, 마포구)를 선정하였습니다. 분석 기법은 다음의 두 가지를 채택하였습니다.

* 따릉이 이용자 건수를 종속 변수로 두고, 여러 독립 변수들과의 관계를 알아보는 회귀 분석
* 이용자들의 연령대 코드, 이용 건수, 운동량, 탄소량, 이동 거리, 이동 시간를 변수로 하여 clustering 분석

### 1.3. 데이터 가공 및 전처리

이후에는 각 구에 속한 행정동 별로 데이터를 가공하였으며, 활용 가능한 형태로 전처리하였습니다. 

1.2.1. 현황 조사 에 근거해서, 행정동이 속한 5개의 구를 출근 지역과 퇴근 지역으로 나누고, 또 한강 지역과 한강이 없는 지역으로도 나누었습니다. 나눈 이유는 사전 조사를 하며 판단한 가설을 검증하기 위함입니다.

## 2. 변수 설정

1.2.2. 분석 대상 및 분석 기법 선정의 회귀 분석을 수행하기 위해, 종속 변수인 따릉이 이용자 건수와 연관이 있을 것으로 기대되는 여러 가지 독립 변수를 설정하였습니다. 설정된 독립 변수는 다음과 같습니다.

## 3. 회귀분석 및 Clustering 해석



