# [Machine Learning] (주)스카우트 Salary Prediction 프로젝트

<br>

## 프로젝트 기간
- 2022.11.11 ~ 2022.11.25

<br>

## 프로젝트 소개 

* 교내 Machine Learning 수업의 Competition으로 'Salary Prediction'을 진행
* 데이터는 (주)스카우트에서 제공을 해주었고, 경진대회의 운영 목적으로만 사용 가능하며, 제공된 데이터셋은 유출할 수 없다.

<br>

## 프로젝트 과정

1. Feature Enginerring

* 상위권 팀 소스코드 합치기
* ID, 단과대, 소프트웨어+공대, 세부직종_연봉, NaN_count, NotNull_count Feature 생성

2. 최고 성능이 나온 모델의 상관관계 확인
* 아래의 사진과 같이 상관관계가 매우 높게 나왔기 때문에 단일 모델로 합치기로 결정

<img width="399" alt="image" src="https://github.com/ge0nha0/Contests/assets/100743813/e27341dd-14be-4273-90ba-073f5f77967f">

3. 단일 모델 성능 최대화 전략 수립

4. 단일 모델 Ensemble 시도

* 가장 성능이 높은 모델 7개를 선정하여 상관관계를 확인 한 뒤, 모델 A, 모델 C, 모델 E를 뽑아서 Ensemble 시도

<img width="639" alt="image" src="https://github.com/ge0nha0/Contests/assets/100743813/e88d02f9-5235-4905-9126-af3b0efdf3b5">


5. Blending Ensemble 진행
(RandomForestRegressor, GradientBoostingRegressor, ExtraTreesRegressor, LGBMRegressor, XGBRegressor, CatBoostRegressor, NGBRegressor)

* 각 성능별로 가중치를 차등 부여함

<img width="397" alt="image" src="https://github.com/ge0nha0/Contests/assets/100743813/5ce9e656-e275-4b07-9d4e-85d0f985ed65">


6. 다양한 모델 Ensemble - 최종 모델
* CatBoostRegressor 단일 모델을 최종 모델로 선정함

<br>

## 느낀점
* 기존 Feature를 함부로 삭제해서는 안된다.
* 결측값 처리는 생각보다 성능 향상에 크게 미치지는 않는다.
* 일반화 성능을 높이기 위해 Feature를 생성할 때에는 보편적으로 합당할만한 Feature를 생성하는 것이 매우 중요하다.


