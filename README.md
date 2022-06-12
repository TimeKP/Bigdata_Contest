# Bigdata_Contest

## Topic
일별 심뇌혈관 질환에 영향을 미치는 기상요인과 그 상관관계를 파악하고,
지역별 기후특성에 따른 자료를 산출하여
시기별, 지역별 질환 발생 빈도를 예측하는 모델을 제안

## To-do List
1. 일별 심뇌혈관 발생 -지역적 특성 있는가?
2. 각 지역의 지상요인이 어떻지? (지연효과 고려: 약물 투입 당시 - 효과 나오는 시간이 딜레이가 있는 것)
3. 일별 질환 발생 빈도를 예측 (인구사회학적 특성 등 다른 영향 요인도 이용할 수 있다.)
4. 기상 상황에 따른 질환 발생 “가능성” 예측

## Data information
### 1. 17개 시도 일별 심뇌혈관질환으로 인한 입원 빈도
날짜: 기간 형식 (년/월/일 ~ 년/월/일)
(강원, 경기, 경남, 경북, 광주, 대구, 대전, 부산, 서울, 세종, 울산, 인천, 전남, 전북, 제주, 충남, 충북 순)
지역: 17개 시도
빈도: 심뇌혈관 질환으로 인한 입원 환자 후

## Timeframe
주어진 데이터: 2012.01.01 - 2014.12.31
검증 데이터:  2015.01.01 - 2015.12.31

## 평가지표
RMSE

## Caution

* 예보 데이터를 필수로 활용해야 함

* 다양한 기상데이터 활용, 질환 발생 가능성 예측 모델 제시 
