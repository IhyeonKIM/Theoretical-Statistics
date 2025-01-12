# Theoretical Statistics Project 

수리통계학의 핵심 이론 및 방법론을 이용하여, 매주 다양한 주제로 R을 통해 프로젝트를 진행 후 R-shiny Application을 개발하고 발표하는 시간을 가졌다. 

***


## Contents


 No. | Subject | Data | Model | App |
| ------ | -- | -- |-----|------|
|  1 | Diffusion Model을 이용한 수요예측 |· 256K,1M DRAM<br>· COVID19사망자수, AIDS감염자수<br>· 영화 관람객:기생충, 모가디슈 | · BASS<br>· Logistic<br>· Gumbel<br>· Exponential | [Shiny1](https://ewhastat.shinyapps.io/demand_forecast/) |
| 2 | 한도(Limit)에 따른 손해보험료 산정 |· 국내운전자보험<br>· 국내아파트화재보험<br>· 국내학교화재보험 |· Frechet<br>· Pareto<br>· Weibull<br>· Loglogistic |  [Shiny2](https://ewhastat.shinyapps.io/nonlife_insurance)|
|  3 | 생명표를 이용한 생명보험-연금 산정  |· 2010년연앙인구<br>· 2010년연령별사망자수<br>· 2010년각세별경험생명표 | · Gompertz | [Shiny3](https://ewhastat.shinyapps.io/life_insurance/) |
|  4 | Black-Scholes Option 가격 산정 | · 2019-2020년삼성전자종가 |· Geometric Brownian Motion Process<br>· Monte-Carlo<br>· Black-Scholes-Merton | [Shiny4]( https://2hyeon.shinyapps.io/asian_option_price/) |
|  5 | Optimal Portfolio 계산 및 수익률 비교  |· 2011-01~2020-12 월별금리<br>· 삼성전자 월별종가<br>· KT&G 월별종가<br>· NAVER 월별종가<br>· KAKAO 월별종가<br>· 한국가스공사 월별종가 |· Modern Portfolio Theory(MPT)| [Shiny5](https://soohyeonlee.shinyapps.io/Optimal_Portfoliio/?_ga=2.54491947.2032026875.1633944412-1419575806.1633341072) |
|  6 | GLM을 이용한 자동차보험료 산정 | · 1977년 스웨덴 자동차 보험 자료 | · GLM | [Shiny6](https://2hyeon.shinyapps.io/Car_Insurance/?_ga=2.231842646.890041282.1646883062-891940177.1646883062) |
|  7 | 생명보험 해지방지(예측) CRM | · 생명보험계약 해지여부자료 | · GLM<br>· GAM<br>· CoxPHM<br>· RandomForest<br>· SVM<br>· XGBoost | [Shiny7](https://ewhastat.shinyapps.io/insurance_cancel/) |
| 8 | 기업부도예측 | · 기업 부도발생 여부 및 기업정보 자료 | · GLM<br>· GAM<br>· CoxPHM<br>· KNN<br>· SVM<br>· XGBoost  | [Shiny8](https://ewhastat.shinyapps.io/bankruptcy/) |
|  9 | 심장병 발생예측 | · Framingham 심장병 자료 | · CoxPHM<br>· ALT | [Shiny9](https://soohyeonlee.shinyapps.io/Heart_Disease/) |




## Members & Rshiny Address
* 박지윤([@stat-yoon](https://github.com/stat-yoon))
  * [Option Price](https://stat-jyp.shinyapps.io/option_price/)
  * [Optimal Portfolio](https://stat-jyp.shinyapps.io/project_portfolio/)
  * [Life Insuarance](https://stat-jyp.shinyapps.io/life_insuarance/)

* 김이현([@IhyeonKIM](https://github.com/IhyeonKIM))
  * [Default Forecast](https://2hyeon.shinyapps.io/bankruptcy)
  * [Life_Insurance](https://2hyeon.shinyapps.io/insuarance/)
  * [Heart Disease](https://2hyeon.shinyapps.io/heart_disease)


## Reference

* a)  Generalized Linear Models, , (1989) Chapman and Hall, McCullagh and Nelder,  2nd ed.
* b)  All of Statistics (2004) Springer, Larry Wasserman.


***


