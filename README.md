### <새로운 도박과제 설계를 통한 참가자들의 수행 개선> 
**프로젝트 상세 소개:** [포트폴리오 링크](https://drive.google.com/file/d/1gaaUSv0DohvbZj0okcUg6aW6-UAgo_UI/view?usp=drive_link)
<br>
### 프로젝트 소개  
기존 도박과제에서 참가자들은 시간이 지남에 따라 4개의 카드 세트에서 보상/손실 점수가 나올 확률을 간접적으로 학습하며 좋은 카드를 선택하는 비율이 높아지는 경향을 보이지만 전체적으로 좋은 카드를 선택하는 비율은 절반도 안된다.    
<br>

**데이터셋**  
연구실에서 심리학 학부생 모집. 실험 시작 전, 성별, 인종, 나이에 대해 조사.  
<br>

**분석 방법론**  
Rstudio(tidyverse, brms)를 이용하여 참가자들이 좋은 카드를 선택한 비율을 계산(1블록당 25회의 시행), 통제조건과 실험조건에서 좋은 카드 선택 비율을 비교. 
각 카드마다 통제조건과 실험조건에서 좋은카드를 선택한 비율을 비교.
혼합효과 로지스틱 회귀를 이용하여 주효과인 실험조건과 블록 각각이 좋은 카드 선택 비율에 유의미한 영향을 미치는지 알아봄.     
<br>

**연구결과**  
마지막 실험3을 통해 마우스클릭(또는 버튼누르기)이라는 조작과 함께 점수를 분할했을 때 수행 개선 효과가 나타난다는 것을 알 수 있었다. 
즉, 점수분할과 마우스클릭 조작은 각 카드가 제시하는 보상/손실 점수의 빈도에 더 민감한 참가자들의 주의를 점수의 크기(규모)에 기울이게 하여 좋은 카드를 더 많이 선택하게 만든다

