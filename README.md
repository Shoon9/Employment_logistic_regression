# Employment_logistic_regression

한국 종합사회 KGSS (성균관대학교 서베이 리서치 센터) 조사 2014년도 Spss 자료’의 데이터를 활용하여 취업의 유무에 영향을 줄만한 변수의 분석을 진행하였습니다. 
 
취업 유무에 미치는 요인들에 대한 분석에서 사용된 설명 변수는 ‘성별(SEX)’, ‘연령(AGE)’, ‘응답자 학력(EDUC)’이 있습니다. 
연령을 제외한 성별과 응답자의 학력 변수들은 모두 범주형 변수로 분석을 진행하였습니다.

> - 반응변수
<br>Y. 취업유무 : 취업(1) , 미취업(2)
>- 설명변수
  <br> X1. 성별(SEX) : 남(1), 여자(2)
  <br> X2. 연령(AGE) : 연속형 변수, min = 18, max = 110
  <br> X3. 응답자 학력(EDUC) : 무학(0), 국민•초등학교(1), 중학교(2), 고등학교(3), 전문대학 2•3년제(4), 대학교 4년제(5), 대학원(6), 서당한학(7)

취업 유무와 관계가 있을 것이라 선별된 설명변수(성별, 나이, 응답자의 학력)들의 통계적 유의성을 확인하고, 모형의 적합도를 확인하기 위해서 일반화선형회귀모형을 이용한 로지스틱 회귀 모형을 적합하였습니다. 그 후 모형의 적합도가 더 좋은 모델이 어떤 경우인지 확인하기 위하여 로지스틱 모형, 프로빗 모형, 부 로그-로그 모형의 AIC와 데비언스를 비교하여 실험을 진행하였습니다.

logit 모형의 결과는 다음과 같았습니다.

>성별 : 취업했을 확률 대 미취업 확률 오즈에 대해 여자의 오즈보다 남자의 오즈가 더 크다.
<br>연령 : 나이가 증가 할수록 취업했을 확률 대 미취업 확률에 대한 오즈가 커진다.
<br>응답자 학력 : 최종학력이 높아 질수록 취업했을 확률 대 미취업 확률에 대한 오즈가 높아진다.

