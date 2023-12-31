# [경찰대학교 치안정책연구소] '충청남도⋅대전시⋅세종시의 사고다발지역 분석을 통한 교통사고 위험요인 파악과 해결방안 제시' 프로젝트

<br>

## 프로젝트 기간
- 2023.01.20 ~ 2023.02.15

<br>

## 프로젝트 소개 
* 충청남도, 대전광역시, 세종특별자치시의 교통사고를 예방하기 위해 지금까지 일어난 교통사고를 분석함.
* 사고다발지역을 중점적으로 분석하여 교통사고 건수를 줄이고자 프로젝트를 진행함.
* 데이터는 가로등, 주차장, 무인단속카메라, 신호등, 사고다발지역, 유동인구현황, KP20, KP21 데이터를 활용함.

<br>

## 프로젝트 과정

1. 주어진 'KP20', 'KP21' 데이터를 활용해 사건종별, 경도, 위도, 동일사건발생을 기준으로 중복값을 제거하고 첫번째 값만 남김

2. 2019~2021년 지차제별 사고다발지역 데이터를 활용하여 세 지역을 각각 시각화 진행

<img width="386" alt="image" src="https://github.com/ge0nha0/Contests/assets/100743813/f9bd646e-6845-4064-bdbe-7f32a1be60c7">
<img width="372" alt="image" src="https://github.com/ge0nha0/Contests/assets/100743813/f49776b8-3104-48d3-9aa8-90b08e2e696a">



3. 2019~2021년 세 지역의 교통사고 데이터를 각각 시각화 진행

4. 가로등, 차량 신호등, 무인교통단속카메라, 주차장을 'KP20'과 'KP21'의 사고지점과 함께 지도에 시각화
* 파이썬 지도 시각화 도구인 folium 활용
* QGIS를 통해 시각화 진행

<img width="301" alt="image" src="https://github.com/ge0nha0/Contests/assets/100743813/715d245f-f3f6-4ac3-ae64-8b4c8329e672">
<img width="262" alt="image" src="https://github.com/ge0nha0/Contests/assets/100743813/7bdd2898-507c-4c14-9f87-b64690d1d21e">


5. 현장 답사 진행

<img width="481" alt="image" src="https://github.com/ge0nha0/Contests/assets/100743813/a2ef941f-f61e-4eb7-93fb-0785636b48ab">
<img width="372" alt="image" src="https://github.com/ge0nha0/Contests/assets/100743813/667d6951-2167-4cc5-b1c4-18ecaa73ff94">


6. 데이터분석과 현장답사를 통해 각 지역의 해결책 제시


<br>

## 느낀점
* 지자체별 데이터가 다른 경우가 있어 연구에 통일성이 부족함
* 데이터를 수집이 매우 어려움
