---
description: Feel free to enjoy it.
---

# ECO 205 Top 1 Report(2021)

| Student Name        | None                                                                                 |
| ------------------- | ------------------------------------------------------------------------------------ |
| Student Number      | None                                                                                 |
| Programme           | Coursework                                                                           |
| Module Title        | Econometrics I                                                                       |
| Module Code         | ECO205                                                                               |
| Assignment Title    | An empirical analysis of the influencing factors of China's domestic tourism revenue |
| Submission Deadline | December 17，2021（Friday）24:00PM                                                      |
| Module Leader       | Ming He                                                                              |

> **General feedback on the work**
>
> The motivation is strong. The data description is good. The empirical model is well justified and the econometric method is appropriate. The inferences and interpretations are good. The discussion is adequate. The format and writing are good.

| **Component**                            | **Weight** | **Mark** |
| ---------------------------------------- | ---------- | -------- |
| Motivation of research question          | 10%        | 80       |
| Data description                         | 15%        | 85       |
| Empirical model and justification        | 25%        | 85       |
| Results, interpretations, and inferences | 30%        | 80       |
| Discussion and conclusion                | 10%        | 78       |
| Structure, format, and writing           | 10%        | 80       |
| **Total**                                | 100%       | 81.8     |

## **An empirical analysis of the influencing factors of China's domestic tourism revenue**

### **Motivation**

The tourism industry, one of the essential growing economic sectors of China, has always maintained a high speed of development in recent years. It not only drives related industries and generates huge economic benefits, but also promotes China's overall economy, with the domestic tourism revenue increasing from 874.9 to 5725.1 billion yuan from 2008 to 2019 (National Bureau of Statistics, 2020). The development of tourism has a profound impact on optimizing China's economic and industrial structure, increasing employment opportunities, and accelerating new village construction. Consequently, considering the economic benefits brought from the tourism industry, the analysis of influencing factors on tourism revenue is of great economic and social value.

Over the years, many scholars have studied the influential factors of domestic tourism income, expecting to develop China's tourism in a flourishing way. Using the ridge regression method, Wang (2008) indicated that the number of tourists, domestic price level, and GDP per capita are significantly correlated with domestic tourism income. Sun, Zong and Zhang (2021) adopted panel multiple linear regression model, whose results reveal that people's education level, railway mileage density, number of domestic tourists and GDP per capita have plausible correlations with tourism income. It is illustrated by Mammadov (2012) that transportation investment promotes domestic tourism revenue based on the actual transportation situation in Azerbaijan and other countries. Particularly, Guo, Zhang and Wu (2008) found that the total tourism income in Qinhuang Island is most closely related to the total number of overnight visitors.

Therefore, this report quantitatively analyzes the influence of GDP per capita, number of domestic tourists**,** number of visitors staying overnight, transportation investment, and transportation milage density through an econometric model and formulates relevant suggestions and strategies for the development of the tourism industry according to the analysis of the impact factors.

### **Empirical Design**

#### _**Variable selection**_

In this report, the explained variable is domestic tourism revenue (DTR), which is selected as the income index of the domestic tourism industry. The gross domestic product per capita (GDPPC), number of tourists staying overnight (NON), number of domestic tourists (NOT), transportation investment (TI) and transportation mileage density (TMD) across 31 provinces, autonomous districts, and municipalities (Taiwan, Hong Kong, and Macau excluded) are selected as the explanatory variables in this report. The panel data of samples are obtained through data collection and the definition of each variable are as Table1.

The specific variables are stated below：

_a. Domestic tourism revenue (DTR)_

Domestic tourism revenue means all currency earned by selling travel-related goods and services. The main purpose of developing tourism is to gain tourism income, generate more employment opportunities as well as promote China's economic growth (Sun, Zong and Zhang, 2021). This report selects the domestic tourism revenue of each province over 12 years as the explained variables.

_b. Gross domestic product per capita (GDPPC)_

Higher GDP per capita indicates better residents' living quality which will cause the expenditure on tertiary industry to account for a larger proportion of consumption structure. Wang (2008) re-estimated the model using ridge regression and suggested that there is a greatly positive correlation between GDP per capita and domestic tourism income.

_c. Number of tourists staying overnight (NON)_

The number of tourists who stay overnight has an impact on the tourism revenue since it largely determines the accommodation income which is part of tourism revenue. From both previous studies and analytical results, accommodation revenue will change in the same direction as the number of visitors staying overnight (Guo, Zhang and Wu, 2008).

_d. Number of tourists (NOT)_

The number of tourists (NOT) measures the total number of domestic tourists respectively across 31 individuals during a specific period. To augment tourism revenue, one of the most direct ways is to enlarge its consumer group. According to Sun, Zong, and Zhang (2021), the number of domestic tourists positively correlates with domestic tourism revenue.

_e. Transportation investment (TI)_

An efficient and comprehensive transportation network is an indispensable condition for tourism. Governmental contribution to upgrading transportation infrastructure construction namely transportation investment, to a large extent, determines the superiority of this condition. TI covers the investment of nearly all aspects of transportation with renewals, extensions and upgrades included. Mammadov (2012) demonstrated that transportation investment facilitated domestic tourism revenue vitally.

_f. Transportation mileage density (TMD)_

Transportation convenience is a crucial role in the development of tourism. The more convenient it is to travel, the more attractive the destinations are for tourists. Additionally, the vast majority of domestic travel is by highway and railway whose mileage, as a result, are two typical factors representing transportation convenience. However, transportation mileage in two districts is discrepant due to their different areas, so we represent the degree of transportation convenience by utilizing the ratio TMD = (0.6\*railway mileage+0.4\*highway mileage)/area of each province (Wang, Du and Yang, 2020). Moreover, Sun, Zong, and Zhang (2021) illustrated that there exists a positive relationship between transportation mileage density and domestic tourism income.

**Table 1: Definition of variables**

| **Variable**                        | **Definition**                                                                                          | **Unit**                       |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------ |
| Domestic tourism revenue(DTR)       | All currency earned by selling travel-related goods and services of 31 provinces from 2008 to 2019      | Yuan in hundred million        |
| GDP per capita (GDPPC)              | The gross domestic product per capita of 31 provinces from 2008 to 2019                                 | Yuan in ten thousand           |
| Number of nights (NON)              | number of tourists staying overnight of 31 provinces from 2008 to 2019                                  | In ten thousand                |
| Number of tourists (NOT)            | The number of domestic tourists of 31 provinces from 2008 to 2019                                       | In ten thousand                |
| Transportation investment (TI)      | Governmental investment in the upgrading of transportation facilities of 31 provinces from 2008 to 2019 | Yuan in hundred million        |
| Transportation milage density (TMD) | (0.6\*railway mileage+0.4\*highway mileage)/area of each province from 2008 to 2019                     | 10 thousand km/10 thousand km2 |

#### _**Establishment of econometric model**_

In view of analyzing the elasticity influence of explanatory variables on the explained variable, all variables in this report are in the form of a natural logarithm and independent of the measurement units chosen for the variables.&#x20;

Furthermore, we introduced the combined entity and time fixed effects regression model to eliminate omitted variables bias arising from unobserved variables that vary only over time or across the province. Therefore, on the basis of the above previous analysis, a panel regression model established for Econometric analysis is

where i represents for the provinces (i =1,2,...,31); t represents for the years (t =2008,2009,...,2019); is the error term. The specific definitions and the units of explanatory variables are in Table 1.

#### _**Sample and data**_

Due to the serious missing part of relevant data during other years, the sample selection is based on the yearly data from 2008 to 2019 across 31 provinces/autonomous districts/municipalities (Taiwan, Hong Kong, and Macau excluded). The sample above is used for regression analysis of panel data and in consideration of the authority of data, all data originates from the “China Statistical Yearbook”, the National Bureau of Statistics and the Provincial Bureau of Statistics. The strongly balanced panel data of samples are obtained through data collection and the descriptive statistics for each variable are displayed in Table 2.

**Table2: Descriptive statistics of the variables**

| **Regressor** | **Obs** | **Min**  | **Median** | **Max**    | **Mean**  | **SD**    |
| ------------- | ------- | -------- | ---------- | ---------- | --------- | --------- |
| **DTR**       | 355     | 20.424   | 2253.650   | 13902.210  | 3182.999  | 2958.104  |
| **GDPPC**     | 372     | 8824.000 | 41370.583  | 164000.000 | 47835.773 | 26432.208 |
| **NON**       | 372     | 1.159    | 176.300    | 3748.057   | 327.392   | 586.312   |
| **NOT**       | 281     | 217.800  | 19836.000  | 87611.700  | 24592.611 | 20547.090 |
| **TI**        | 364     | 87.117   | 941.017    | 3759.600   | 1149.390  | 713.080   |
| **TMD**       | 372     | 0.017    | 0.360      | 0.863      | 0.360     | 0.196     |

Table 2 shows the results of descriptive statistics for the main variables. In terms of DTR, the mean is still at the relatively low level and the range varies considerably. Furthermore, it presents a positively skewed distribution, which displays the fact that there are obvious gaps in the tourism situations among different provinces. With regard to NON and NOT, it is evident that the extent to which local tourism develops among different provinces varies considerably, and this may conclude that some local governments with relatively backward economies focus still on secondary industry rather than tertiary industry.

Table 3 exhibits the correlation between relevant variables. According to Table 3, a positive correlation between the explained variable and each explanatory variable in the model can be preliminarily inferred to reach a significant level with other things equal and there exists no strong multicollinearity using a 0.8 determination coefficient. Additionally, in order to test the multicollinearity precisely, we then check the variance inflation factors and all VIFs are much less than 10 so we consider it is a weak multicollinearity that can be ignored. The results are shown in Table 4.

**Table3: Correlation**

| Variables                              | (1)         | (2)         | (3)         | (4)         | (5)   | (6)   |
| -------------------------------------- | ----------- | ----------- | ----------- | ----------- | ----- | ----- |
| (1) lnDTR                              | 1.000       |             |             |             |       |       |
| (2) lnGDPPC                            | 0.591\*\*\* | 1.000       |             |             |       |       |
| (3) lnNON                              | 0.730\*\*\* | 0.444\*\*\* | 1.000       |             |       |       |
| (4) lnNOT                              | 0.913\*\*\* | 0.450\*\*\* | 0.712\*\*\* | 1.000       |       |       |
| (5) lnTI                               | 0.209\*\*\* | 0.106\*\*   | 0.148\*\*\* | 0.202\*\*\* | 1.000 |       |
| (6) lnTMD                              | 0.661\*\*\* | 0.386\*\*\* | 0.555\*\*\* | 0.658\*\*\* | 0.048 | 1.000 |
| _\*\*\* p<0.01, \*\* p<0.05, \* p<0.1_ |             |             |             |             |       |       |

**Table4：Variance inflation factor**

|           |   VIF |   1/VIF |
| --------- | ----- | ------- |
|  lnNOT    | 2.842 | .352    |
|  lnNON    | 2.249 | .445    |
|  lnTMD    | 1.941 | .515    |
|  lnGDPPC  | 1.354 | .738    |
|  lnTI     | 1.065 | .939    |
|  Mean VIF | 1.89  | .       |

### **Empirical analysis**

#### _**Model selection**_

In order to explain the reasons for selecting the model in detail, we demonstrate it from two aspects: its realistic meanings and statistical verifications.

From the economic point of view, this model may include two additional features to capture the key drivers of domestic tourism revenue. To account for entity effects, we add a deterministic linear trend to the model and assume that some of the omitted variables are constant over time, but vary across provinces, such as tastes, marketing, expectations, and habit persistence (see Sequeira and Nunes, 2008 b; Song et al., 2009; Croes, 2012; and Ridderstaat et al., 2014, for example).

Besides, the second feature of the model is the existence of component that leads to a better understanding of the whole model and its characteristics. Some factors are constant across provinces but vary over time, such as the government's policy of supporting tourism. Nowadays, China is at a stage of vigorous economic development, where the tertiary industry acts as an important pillar. Hu (2013) declared that the proportion of the tertiary industry in the economic structure of a country or region has become one of the essential indicators to measure its economic development. However, China's tertiary industry accounts for 54.5% of GDP, far lower than 70% in most developed countries. Therefore, in order to promote economic development, the national government's support for tourism and other tertiary industry will continue to increase.

In order to further determine the validity of the model, the stata test is used. We apply the heteroskedasticity test and its results indicate that the sample is heteroscedasticity at 1% significant level. It turns out that the cluster-robust standard error should be used to eliminate the effect of heteroscedasticity on the regression results.

To determine which panel data model (i.e., the fixed-effect model or the random-effects model) is suitable for the following analysis, here we use and Hausman test to establish the panel data regression model and the results are shown in Table 5. The testing results illustrate that the p-value is 0 in which case we are able to reject the null hypothesis of the individual effect at 1% significant level. Therefore, we adopt the fixed effect model.

After that, we measure the overall significance of T-1 dummy variables by F test whose results（ shown in Table 6）demonstrate that the T-1 dummy variables cannot be 0 simultaneously at 1% significant level. Thus, the time-fixed effect should not be ignored. Ultimately, we choose the combined entity and time fixed effects model rather than just entity fixed effects model.

**Table 5: Hausman Test**

|              | (1)                            | (2)                            |
| ------------ | ------------------------------ | ------------------------------ |
| Regressor    | FE                             | RE                             |
| lnGDPPC      | <p>1.221***</p><p>(0.087)</p>  | <p>1.173***</p><p>(0.061)</p>  |
| lnNON        | <p>0.064</p><p>(0.045)</p>     | <p>0.128***</p><p>(0.040)</p>  |
| lnNOT        | <p>0.273***</p><p>(0.038)</p>  | <p>0.419***</p><p>(0.040)</p>  |
| lnTI         | <p>0.066***</p><p>(0.024)</p>  | <p>0.087***</p><p>(0.027)</p>  |
| lnTMD        | <p>1.149***</p><p>(0.239)</p>  | <p>0.298***</p><p>(0.087)</p>  |
| Constant     | <p>-7.498***</p><p>(1.077)</p> | <p>-9.904***</p><p>(0.557)</p> |
| Observations | 266                            | 266                            |
| R-squared    |  0.935                         |                                |
| Hausman      | 76.05                          |                                |
| p-value      |  0                             |                                |

`Standard errors in parentheses`

`*** p<0.01, ** p<0.05, * p<0.1`

#### _**Regression results of the panel model**_

**Table6: Regression Result**

| <p><strong>Dependent variable: Domestic Tourism Revenue (DTR).</strong></p><p>                                                     (1)</p><p>Regressor                                           lnDTR</p> |                                   |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- |
| lnGDPPC                                                                                                                                                                                                    | <p>0.703**</p><p>(0.278)</p>      |
| lnNON                                                                                                                                                                                                      | <p>0.173**</p><p>(0.071)</p>      |
| lnNOT                                                                                                                                                                                                      | <p>0.214**</p><p>(0.081)</p>      |
| lnTI                                                                                                                                                                                                       | <p>0.163***</p><p>(0.041)</p>     |
| lnTMD                                                                                                                                                                                                      | <p>0.648</p><p>(0.410)</p>        |
| cons                                                                                                                                                                                                       | <p>-3.513</p><p>(3.122)</p>       |
| Years                                                                                                                                                                                                      | 2008-2019                         |
| Entity effects?                                                                                                                                                                                            | Yes                               |
| Time effects?                                                                                                                                                                                              | Yes                               |
| Clustered standard errors?                                                                                                                                                                                 | Yes                               |
| Observations                                                                                                                                                                                               | 266                               |
| R-squared                                                                                                                                                                                                  | 0.954                             |
| F-Statistics and p-Values Testing Exclusion of Groups of Variables                                                                                                                                         |                                   |
| Time effects = 0                                                                                                                                                                                           | <p>9.30</p><p>(&#x3C;0.001)</p>   |
| All the regressors = 0                                                                                                                                                                                     | <p>136.41</p><p>(&#x3C;0.001)</p> |

`Standard errors in parentheses`

`*p < 0.1, **p < 0.05, *** p < 0.01,`

The results of DTR panel regression (Table 6) show that the regression coefficients of the GDPPC, NON, NOT, TI are highly significant, while the TMD is not statistically significant. All the variables positively correlate with DTR. In our regression model, the R-square is 0.954 which is close to 1. This means the regression model fits our observation well.

F-test is introduced to measure the overall significance of the regressors. It turns out that p-value is extremely colse to 0, which indicates that their joint effect is significant.

### _**Regression results analysis**_

Table 6 shows the regression results for the estimation. According to what has been mentioned theoretically, all estimated coefficients have the expected signs, except that TMD is not strongly statistically significant.

GDPPC has the greatest impact on DTR, followed by NOT and NON, which all pass 5% significance test. In a slightly different manner, TI is statistically significant at 1% significant level. However, there may be a non-significant correlation between DTR and TMD and the 95% confidence interval (-0.1889144,1.485035) contains 0 which means the transportation milage density does not have a phenomenal effect on DTR.

The estimated coefficients of lnGDPPC, interpreted as the elasticity of GDPPC, is equal to 0.703, which means that every 1% increase in GDP per capita will contribute to a 0.703% rise in DTR, other factors being equal. The impact of NOT and NON are also strongly significant, but their marginal effects on the growth of DTR are obviously lower than that of GDPPC. A 1% increase in NOT and NON will raise DTR by 0.214% and 0.173% respectively. Likewise, with controlling other things equal, for every 1% increase in TI, DTR will increase by 0.163%. From the statistical analysis above, it is evident that the growth of GDP per capita, the number of domestic tourists and ones staying overnight as well as the transportation investment in each individual mount the domestic tourism revenue.

In terms of economic sense, higher GDP means higher living standards of residents, which indicates more money will be spent on recreational activities such as sightseeing. In order to increase tourism income, a larger consumer group is necessary, which is the foundation of creating economic inflows. Moreover, given that the number of tourists staying overnight reflects the accommodation level, accommodation facilities of high quality along with pleasing surroundings and convenient locations can contribute greatly to improving the retention of tourists, which in turn enhances tourism revenue. This point of view explains the significance of NON. But its weaker marginal effect can be possibly due to the fact that consumers are more inclined to pay attention to sightseeing and exotic experiences rather than accommodation. Besides, if local governments scale up transportation input to improve public traffic networks, such as rebuilding old highways, buying faster trains, and constructing new railroads, tourists' traveling experience will be more unforgettable. Ultimately, the increment of the transportation milage density has no obvious influence on the growth of tourism income in China. The possible reason is that in recent years, with the rapid development of transportation in China, the coverage of railway and highway has reached a relatively high level so that their mileage has approached saturation. Therefore, increasing the mileage density of railways and highways has little influence on tourism income, which, in other words, shows a spillover effect.

### **Conclusion and Discussion**

This report analyses the influence of five factors, namely transportation investment, number of tourists staying overnight, GDP per capita, number of tourists and transportation mileage density on the domestic tourism revenue, for a panel of 31 provinces/autonomous districts/municipalities (Taiwan, Hong Kong and Macau excluded) in China observed from 2008 to 2019.

Firstly, as the Hausman test conducted shows the rejection of the null hypothesis, the fixed-effect model is chosen over the random-effect model. Secondly, the comparative analysis of applying the entity fixed model or the combined entity and time fixed model through F-test revealed that the latter model was optimal. Based on this, a specific multiple linear regression model has been established. The regression results have indicated that, at a 5% significance level, there is strong evidence that growth in the number of domestic tourists and the number of visitors staying overnight, an increase in the GDP per capita and the transportation investment do help boost the domestic tourism revenue as expected. Among these, the GDP per capita is most influential with the highest elasticity (estimate of 0.895). It suggests that the overall economic development plays an indispensable role in the increase of tourism revenue and implies that the residents' consumption structure is transforming to enjoy consumption, which is resonated by Sun, Zong and Zhang (2021). However, transportation mileage density does not significantly affect the domestic tourism income at 10% significance level which may be caused by the approaching saturation of the transportation mileage and this viewpoint is consistent with the theoretical argument of Yang et al. (2020).

However, there exists several flaws in this model. First of all, the panel data we use in this paper is relatively complete at the province level since it covers essentially all provinces in China. Nevertheless, the time-series information is somewhat limited because data in some earlier years are hard to capture and some variables are not observed in some provinces over different periods of time. Secondly, our model also suffers from measurement error bias to some extent. For example, the ratio TMD = (0.6\*railway mileage+0.4\*highway mileage)/area of the province is utilized to measure transportation convenience, without considering aeronautical data limited by its availability and comparability. Finally, there may still exist omitted variables bias. While we have already covered five main impact factors in our regression model, it is difficult to reflect the complex macroeconomic market comprehensively.

Although the current research has the above three limitations, we have tried our best to collect as many reasonable variables and accessible data as possible and adopted the two-way fixed effects model to minimize omitted variable bias. Furthermore, we can introduce a larger database and more related explanatory variables to make our model more reliable when more observations become available.

Combined with the comprehensive analysis of this report, some measures should be taken into consideration in the promising future.&#x20;

**1) **_**Loosen restrictions on tourism financing**_

Tourism belongs to the tertiary industry, with its main aim to enrich consumers' spiritual life. The local service industry to a large extent would be an essential attraction for tourists. From one specific perspective, raising the accommodation level nearby may have a strongly positive effect on improving tourists' traveling experience. Concerning its economic meaning, higher investment is likely to bring in higher profits in the tertiary industry. So, depending merely on tourism developers is not enough, which means local governments should encourage banks and financial departments to provide subsidies for them.

**2) **_**Pursue superior transportation facilities and innovate tourism experience**_

Transportation mileage has already been improved to a relatively great level, in which case the quality of transportation infrastructure construction should now be prioritized. Renewing the metro lines and system, buying new technologically advanced planes, and other related improvements may be a better choice. With more entrants to tourism, they compete to maintain existing scenic spots and exploit novel ones. In this way, consumers are more willing to allocate their deposits to tourism.

**3) **_**Publicize and build tourist attractions catering to trend of times**_

Recently, we media is one of the most prevalent ways via the Internet to publicize one's characteristics, which creates a platform for local governments to make their featured culture and attractions available to outsiders. Additionally, the youngster tends to visit internet-famous places to enrich their profile at this time. For instance, Disney Town is one of the successful precedents featuring internet-famous elements which provide a series of tourism services from accommodation to amusement. This kind of integrated and comprehensive theme tourism spot can enlarge the number of tourists and ones staying overnight, which in turn strongly boost the domestic tourism revenue.&#x20;

### **References**

Croes, R. (2012) 'Assessing tourism development from Sen's capability approach, Journal of Travel Research, 51(5), 542-554 \[Online]. Available at: [https://journals.sagepub.com/doi/10.1177/0047287511431323](https://journals.sagepub.com/doi/10.1177/0047287511431323) (Accessed: 5 December 2021)

Guo, W., Zhang, Q. J. and Wu, J. (2008) ‘The influencing factors of tourism income are analyzed based on grey correlation’, Productivity Research \[Online]. Available at: [http://cnki.sdll.cn:85/kcms/detail/detail.aspx?QueryID=13\&CurRec=2\&DbCode=CJFQ\&dbname=CJFD0608\&filename=SCLY200816037\&uid=V2JyZDk1ZEtLZmFlN3NhdjhndnF0NGhDaXl4Y1NzSDRRc0RZK3JBb2NnLzJkQUNV](http://cnki.sdll.cn:85/kcms/detail/detail.aspx?QueryID=13\&CurRec=2\&DbCode=CJFQ\&dbname=CJFD0608\&filename=SCLY200816037\&uid=V2JyZDk1ZEtLZmFlN3NhdjhndnF0NGhDaXl4Y1NzSDRRc0RZK3JBb2NnLzJkQUNV) (Accessed: 5 December 2021)

Hu, L. (2013) ‘The study on the relationship between China’s tertiary industry development and employment growth’, Northwest Normal University, Wanfang Data \[Online]. Available at: [https://d.wanfangdata.com.cn/thesis/D359485#](https://d.wanfangdata.com.cn/thesis/D359485) (Accessed: 5 December 2021)

Mammadov, R. (2021) 'The Importance of Transportation in Tourism Sector', Academia.edu \[Online]. Available at: [https://www.academia.edu/2628130/The\_Importance\_of\_Transportation\_in\_Tourism\_Sector](https://www.academia.edu/2628130/The\_Importance\_of\_Transportation\_in\_Tourism\_Sector) (Accessed: 12 December 2021)

Ridderstaat, J., Croes, R., & Nijkamp, P. (2014) 'The tourism development quality of life nexus in a small island destination', Journal of Travel Research \[Online]. Available at: [https://journals.sagepub.com/doi/10.1177/0047287514532372](https://journals.sagepub.com/doi/10.1177/0047287514532372) (Accessed: 12 December 2021)

Sequeira, T. N., & Nunes, P. M. (2008b) 'Does country risk influence international tourism? A dynamic panel data analysis', Economic Record, 84, 223-236 \[Online]. Available at: [https://onlinelibrary.wiley.com/doi/10.1111/j.1475-4932.2008.00464.x](https://onlinelibrary.wiley.com/doi/10.1111/j.1475-4932.2008.00464.x) (Accessed: 12 December 2021)

Song, H., Witt, S., & Li, G. (2009) 'The advanced econometrics of tourism demand', New York: Routledge \[Online]. Available at: [https://scholar.google.com/scholar\_lookup?title=The%20advanced%20econometrics%20of%20tourism%20demand\&author=H.%20Song\&publication\_year=2009](https://scholar.google.com/scholar\_lookup?title=The%2520advanced%2520econometrics%2520of%2520tourism%2520demand\&author=H.%2520Song\&publication\_year=2009) (Accessed: 12 December 2021)

Sun, L., Zong, Q. H. and Zhang H. H. (2021) ‘An empirical analysis of the influencing factors of China's domestic tourism income’, Shanxi Youth, 2021(4), pp.78-79.

Wang, D. Y., Du, C. C. and Yang, L. X. (2020) 'The influencing factors of tourism income in China —— Analysis based on inter-provincial panel data', Estate Observation, 2020(8), pp.177-180 \[Online]. Available at: [http://cnki.sdll.cn:85/kcms/detail/detail.aspx?QueryID=1\&CurRec=1\&DbCode=CJFQ\&dbname=CJFDLAST2020\&filename=SYJJ202008047\&uid=WFVveDRZL1RONGdVdUFyT3VWbEk4ZDYyQWJ2RVA2b0orUTVwYmgyRStJay9yZFRx](http://cnki.sdll.cn:85/kcms/detail/detail.aspx?QueryID=1\&CurRec=1\&DbCode=CJFQ\&dbname=CJFDLAST2020\&filename=SYJJ202008047\&uid=WFVveDRZL1RONGdVdUFyT3VWbEk4ZDYyQWJ2RVA2b0orUTVwYmgyRStJay9yZFRx) (Accessed: 5 December 2021)

Wang, Z. X. (2008) ‘Analysis on the influencing factors of China's domestic tourism income’, Commercial Modernization, 2008(561), pp.239 \[Online]. Available at: [http://cnki.sdll.cn:85/kcms/detail/detail.aspx?QueryID=12\&CurRec=2\&DbCode=CJFQ\&dbname=CJFD0608\&filename=SCXH200836168\&uid=V2JyZDk1ZEtLZmFlN3NhdjhndnF0NGhDaXl4Y1NzSDRRc0RZK3JBb2NnLzJkQUNV](http://cnki.sdll.cn:85/kcms/detail/detail.aspx?QueryID=12\&CurRec=2\&DbCode=CJFQ\&dbname=CJFD0608\&filename=SCXH200836168\&uid=V2JyZDk1ZEtLZmFlN3NhdjhndnF0NGhDaXl4Y1NzSDRRc0RZK3JBb2NnLzJkQUNV) (Accessed: 5 December 2021)

Yang, Y. X. et al. (2020) 'Analysis of tourism income sources and influencing factors based on multiple linear regression model', Rural Economy and Technology, 2020(31), pp.118-120 \[Online]. Available at: [http://cnki.sdll.cn:85/kcms/detail/detail.aspx?QueryID=1\&CurRec=1\&DbCode=CJFQ\&dbname=CJFDLAST2020\&filename=NCJI202007056\&uid=WDUrZ2VGU2FabVVIRU1oVkI4anl5dkhTdDdOOE5XRzN0eEJxT29EZ3VQVjE3U3d6](http://cnki.sdll.cn:85/kcms/detail/detail.aspx?QueryID=1\&CurRec=1\&DbCode=CJFQ\&dbname=CJFDLAST2020\&filename=NCJI202007056\&uid=WDUrZ2VGU2FabVVIRU1oVkI4anl5dkhTdDdOOE5XRzN0eEJxT29EZ3VQVjE3U3d6) (Accessed: 12 December 2021)

```stata
// Appendix
1) STATA code
import excel "C:\Users\shihao\Desktop\ECO\panel data）.xlsx", sheet("Sheet1") firstrow
xtset code Year
gen lnDTR =ln(DTR)
gen lnGDPPC = ln(GDPPC)
gen lnNON = ln(NON)
gen lnNOT =ln(NOT)
gen lnTI = ln(TI)
gen lnTMD = ln(TMD)
//Export Chart Section
//Descriptive statistics
ssc install sum2docx
sum2docx DTR GDPPC NON NOT TI TMD using"Table1.docx",replace stats(N min median  max mean sd) title(Table1:Descriptive statistics)
//Correlation analysis
asdoc pwcorr lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD, star(all) bonferroni save(table1.doc) title(Table2: Correlation) append
//VIF
reg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD
estat vif
asdoc vif
//Modified Wald statistic for groupwise heteroskedasticity
xtreg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD, fe
xttest3
//Regression result
xtreg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD i.Year, fe vce(cluster code)
outreg2 using "regression.doc" , replace
//hausman
//FE
xtreg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD, fe
outreg2 using "outreg2-pd", word ctitle(FE) dec(3) replace
estimate store fe
//RE
xtreg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD, re
outreg2 using "outreg2-pd", word ctitle(RE) dec(3) append
estimate store re
//hausman output
hausman fe re, sigmamore
outreg2 using "outreg2-pd", word ctitle(FE) dec(3) adds(Hausman, `r(chi2)', p-value, `r(p) ') append
shellout using `"outreg2-pd.rtf"'
2) Regression output
asdoc sum DTR GDPPC NON NOT TI TMD, stat(N min median max mean sd)
             |         N        min        p50        max       mean         sd 
-------------+------------------------------------------------------------------
     DTR |       355    20.4237    2253.65   13902.21   3182.999   2958.104 
 GDPPC |       372       8824   41370.58     164222   47835.77   26432.21 
     NON |       372     1.1586      176.3   3748.057    327.392   586.3116 
     NOT |       281      217.8      19836    87611.7   24592.61   20547.09 
         TI |       364    87.1172    941.017     3759.6    1149.39   713.0803 
    TMD |       372   .0173231   .3595845   .8634877   .3598825    .195757 
asdoc pwcorr lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD, star(all) bonferroni
             |    lnDTR  lnGDPPC    lnNON    lnNOT     lnTI    lnTMD
-------------+------------------------------------------------------
       lnDTR |   1.0000
     lnGDPPC |   0.5910***  1.0000
       lnNON |   0.7298***  0.4439***  1.0000
       lnNOT |   0.9127***  0.4502***  0.7115***  1.0000
        lnTI |   0.2090***  0.1057**  0.1479***  0.2016***  1.0000
       lnTMD |   0.6615***  0.3861***  0.5553***  0.6583***  0.0483   1.0000
 reg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD
Linear regression        Number of obs   =       266
                                  F(5, 260)       =    467.32
                                  Prob > F        =    0.0000
                                  R-squared      =    0.8999
                                Adj R-squared   =    0.8979
                                  Root MSE      =    .40332
------------------------------------------------------------------------------
       lnDTR |      Coef.   Std. Err.      t    P>|t|     [95% Conf. Interval]
-------------+----------------------------------------------------------------
     lnGDPPC |   .5161808   .0503057    10.26   0.000     .4171223    .6152392
       lnNON |    .126647   .0256753     4.93   0.000     .0760891     .177205
       lnNOT |   .7771765   .0371199    20.94   0.000     .7040825    .8502704
        lnTI |   .1079064   .0363226     2.97   0.003     .0363825    .1794303
       lnTMD |   -.010427   .0421666    -0.25   0.805    -.0934585    .0726045
       _cons |  -6.932272   .6000184   -11.55   0.000    -8.113786   -5.750758
------------------------------------------------------------------------------
estat vif
    Variable |       VIF       1/VIF  
-------------+----------------------
       lnNOT |      2.84    0.351803
       lnNON |      2.25    0.444581
       lnTMD |      1.94    0.515111
     lnGDPPC |      1.35    0.738494
        lnTI |      1.06    0.939000
-------------+----------------------
    Mean VIF |      1.89
xtreg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD, fe
Fixed-effects (within) regression    Number of obs     =        266
                              Number of groups  =         31
                           R-sq:      within  = 0.9348
                                        between = 0.6834
                                         overall = 0.7016
                               corr(u_i, Xb)  = -0.6788
                               F(5,230)          =     659.39
                               Prob > F          =     0.0000
------------------------------------------------------------------------------
       lnDTR |      Coef.   Std. Err.      t    P>|t|     [95% Conf. Interval]
-------------+----------------------------------------------------------------
     lnGDPPC |    1.22066   .0870955    14.02   0.000     1.049053    1.392267
       lnNON |   .0637942   .0454696     1.40   0.162    -.0257961    .1533845
       lnNOT |   .2726727   .0377331     7.23   0.000     .1983259    .3470195
        lnTI |   .0660315   .0239281     2.76   0.006     .0188851    .1131778
       lnTMD |   1.149408   .2388988     4.81   0.000     .6786984    1.620118
       _cons |  -7.497847   1.077198    -6.96   0.000    -9.620285    -5.37541
-------------+----------------------------------------------------------------
     sigma_u |  .93770347
     sigma_e |  .19696226
         rho |  .95774437   (fraction of variance due to u_i)
------------------------------------------------------------------------------
F test that all u_i=0: F(30, 230) = 28.67                    Prob > F = 0.0000
xttest3
H0: sigma(i)^2 = sigma^2 for all i
chi2 (31)  =   25165.75
Prob>chi2 =      0.0000
xtreg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD, fe
Fixed-effects (within) regression    Number of obs     =        266
                              Number of groups  =         31
R-sq:      within  = 0.9348
                                        between = 0.6834
                                         overall = 0.7016
                               corr(u_i, Xb)  = -0.6788
                               F(5,230)          =     659.39
                               Prob > F          =     0.0000
------------------------------------------------------------------------------
       lnDTR |      Coef.   Std. Err.      t    P>|t|     [95% Conf. Interval]
-------------+----------------------------------------------------------------
     lnGDPPC |    1.22066   .0870955    14.02   0.000     1.049053    1.392267
       lnNON |   .0637942   .0454696     1.40   0.162    -.0257961    .1533845
       lnNOT |   .2726727   .0377331     7.23   0.000     .1983259    .3470195
        lnTI |   .0660315   .0239281     2.76   0.006     .0188851    .1131778
       lnTMD |   1.149408   .2388988     4.81   0.000     .6786984    1.620118
       _cons |  -7.497847   1.077198    -6.96   0.000    -9.620285    -5.37541
-------------+----------------------------------------------------------------
     sigma_u |  .93770347
     sigma_e |  .19696226
         rho |  .95774437   (fraction of variance due to u_i)
------------------------------------------------------------------------------
F test that all u_i=0: F(30, 230) = 28.67                    Prob > F = 0.0000
estimate store fe
xtreg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD, re
Random-effects GLS regression    Number of obs     =        266
                              Number of groups  =         31
R-sq:      within  =  0.9265
                                        between =  0.7673
                                         overall =  0.8111
                               corr(u_i, X)   = 0 (assumed)
                               Wald chi2(5)      =    2559.75
                               Prob > chi2       =     0.0000
------------------------------------------------------------------------------
       lnDTR |      Coef.   Std. Err.      z    P>|z|     [95% Conf. Interval]
-------------+----------------------------------------------------------------
     lnGDPPC |   1.172638   .0614931    19.07   0.000     1.052114    1.293162
       lnNON |   .1278188   .0395108     3.24   0.001     .0503791    .2052586
       lnNOT |   .4194841   .0399541    10.50   0.000     .3411754    .4977927
        lnTI |   .0871481   .0272035     3.20   0.001     .0338302    .1404659
       lnTMD |   .2979754   .0866877     3.44   0.001     .1280706    .4678803
       _cons |  -9.904091   .5570972   -17.78   0.000    -10.99598   -8.812201
-------------+----------------------------------------------------------------
     sigma_u |  .29946803
     sigma_e |  .19696226
         rho |  .69804193   (fraction of variance due to u_i)
------------------------------------------------------------------------------
estimate store re
 hausman fe re, sigmamore
                 ---- Coefficients ----
             |      (b)          (B)            (b-B)     sqrt(diag(V_b-V_B))
             |       fe           re         Difference          S.E.
-------------+----------------------------------------------------------------
     lnGDPPC |     1.22066     1.172638        .0480218        .0819491
       lnNON |    .0637942     .1278188       -.0640246        .0360542
       lnNOT |    .2726727     .4194841       -.1468114         .019337
        lnTI |    .0660315     .0871481       -.0211166        .0072303
       lnTMD |    1.149408     .2979754        .8514329        .2673253
------------------------------------------------------------------------------
                           b = consistent under Ho and Ha; obtained from xtreg
            B = inconsistent under Ha, efficient under Ho; obtained from xtreg
    Test:  Ho:  difference in coefficients not systematic
                  chi2(5) = (b-B)'[(V_b-V_B)^(-1)](b-B)
                          =       76.05
                Prob>chi2 =      0.0000
xtreg lnDTR lnGDPPC lnNON lnNOT lnTI lnTMD i.Year, fe vce(cluster code)
Fixed-effects (within) regression   Number of obs     =        266
                              Number of groups  =         31
R-sq:      within  =  0.9544
                                        between =  0.7663
                                         overall =  0.8156                               
corr(u_i, Xb)  = -0.2736
                               F(16,30)          =     136.41                                
Prob > F          =     0.0000
                                  (Std. Err. adjusted for 31 clusters in code)
------------------------------------------------------------------------------
             |               Robust
       lnDTR |      Coef.   Std. Err.      t    P>|t|     [95% Conf. Interval]
-------------+----------------------------------------------------------------
     lnGDPPC |   .7028765   .2779354     2.53   0.017     .1352568    1.270496
       lnNON |   .1730453   .0712523     2.43   0.021     .0275286    .3185619
       lnNOT |   .2135663   .0814952     2.62   0.014     .0471308    .3800018
        lnTI |   .1629536   .0407305     4.00   0.000     .0797707    .2461364
       lnTMD |   .6480602   .4098251     1.58   0.124    -.1889144    1.485035
             |
        Year |
       2009  |   .0129219   .0377038     0.34   0.734    -.0640794    .0899232
       2010  |  -.0062154   .0795923    -0.08   0.938    -.1687645    .1563337
       2011  |   .0581546   .1263811     0.46   0.649      -.19995    .3162592
       2012  |   .0845382   .1696582     0.50   0.622    -.2619502    .4310265
       2013  |   .1965519   .1953573     1.01   0.322    -.2024209    .5955247
       2014  |    .261176    .220284     1.19   0.245    -.1887039     .711056
       2015  |   .3497311   .2416806     1.45   0.158    -.1438465    .8433088
       2016  |   .3956291   .2487222     1.59   0.122    -.1123293    .9035875
       2017  |   .4986863   .2824596     1.77   0.088    -.0781733    1.075546
       2018  |   .7565021   .3245185     2.33   0.027     .0937469    1.419257
       2019  |   .6082879   .3629864     1.68   0.104    -.1330291    1.349605
             |
       _cons |  -3.513117   3.122339    -1.13   0.269    -9.889784     2.86355
-------------+----------------------------------------------------------------
     sigma_u |  .55831684
     sigma_e |  .16871401
         rho |  .91632594   (fraction of variance due to u_i)
------------------------------------------------------------------------------
. testparm i.Year
 ( 1)  2009.Year = 0
 ( 2)  2010.Year = 0
 ( 3)  2011.Year = 0
 ( 4)  2012.Year = 0
 ( 5)  2013.Year = 0
 ( 6)  2014.Year = 0
 ( 7)  2015.Year = 0
 ( 8)  2016.Year = 0
 ( 9)  2017.Year = 0
 (10)  2018.Year = 0
 (11)  2019.Year = 0
       F( 11,    30) =    9.30
            Prob > F =    0.0000
```
