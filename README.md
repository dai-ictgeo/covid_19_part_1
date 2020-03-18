# covid_19_py

# Purpose

As COVID-19 continues to spread across the world, creating a global pandemic, one of the greatest challenges to disease response is a lack of data and evidence about infection rates and vulnerable populations. But as data continues to emerge, there will be much to learn about the virus, which will help both direct response efforts, but also businesses and multinational organizations whose work spans multiple countries. To help DAI and other global development organizations better understand vulnerabilities in the communities in which they work, CDA will investigate potential demographic, socio-economic, and environmental correlates to infection and mortality rates. Data will be analyzed at the country level and results have several potential uses such as to inform clients about countries with greater risk factors, to inform health programming, and to understand countries where DAI works that are  at risk for infection or mortality. This activity can showcase DAI’s data analysis capabilities and incorporate new data in near real time as it become available.
Hypotheses

To approach this research, we will examine at least two dependent variables, and multiple independent (explanatory) variables. 
Proposed Dependent Variables

1.	Mortality rates from COVID19
2.	Infection rates of COVID19

# Proposed Independent Variables
1.	High Foreign Direct Investment (FDI) between countries is correlated with heightened spread of the virus from country A to country B (https://data.oecd.org/).
2.	Shipping routes
3.	Countries with older populations are more likely to experience higher mortality rates than those with younger populations.
4.	Countries that experience high levels of air pollution are more likely to experience higher mortality rates
5.	Temperature Ranges/spread
6.	Countries with populations who experience asthmatic symptoms are more likely to experience higher mortality rates
7.	Countries with higher smoking rates are more likely to experience higher mortality rates (https://www.who.int/data/gho/data/indicators/indicator-details/GHO/current-tobacco-smoking-age-standardised)
8.	Countries with high blood pressure and or diabetes are more likely to experience higher mortality rates (BP: https://www.who.int/data/gho/data/indicators/indicator-details/GHO/mean-systolic-blood-pressure-(age-standardized-estimate), diabetes: 
9.	Country preparedness (OHAPP?) (https://www.who.int/data/gho/data/indicators/indicator-details/GHO/preparedness)
10.	Countries with more low-skilled worker are more likely to experience higher infection rates (https://ilostat.ilo.org/data/, https://data.worldbank.org/).
11.	Nuclear Threats Initiative Global Health Security Index.
12.	Currency fluctuations

# Method(s)

Given that mortality rates depend on infection rates, this analysis will take a two-step approach by first forecasting the countries (and regions?) where the virus is most likely to spread. The independent variables that focus on relationships between countries and travel will be most relied upon as predictors (FDI, shipping routes, flights, proximity to countries with high rates (Euclidean distance), etc.). Some statistical models that may be used include time-series regression, ARIMA, exponential smoothing, and neural network models. For the second part of this analysis, the mortality rates will be predicted on a country level based on health (smoking, respiratory illness rates, and non-infectious disease rates, etc.) and demographic characteristics such as age and gender distributions, climate (temperature, pollution), and labor market characteristics (variables 3-11). Two approaches can be taken for this analysis. First, using existing data on mortality rates, we will conduct a survival analysis (Cox regression model?) to assess which factors are the largest explanatory factors in mortality. Based on these results, we will model country-level mortality rates, based on the predicted infection rates and national-level data on the aforementioned variables for all countries (SRP might be a good option - https://joeornstein.github.io/papers/SRP.pdf).

# Outputs

The hypotheses and methods associated with this research effort are subject to change pending inputs from epidemiologists and public health experts, but we propose the following potential outputs:
•	Website with live risk modelling per country that can be shared with clients and partners.
•	Blog posts on the research effort, including methods, publicly available data, and key findings. 
•	Deliver results to HR and DAI security team to help identify countries most at risk.
Outputs will be delivered in a staged approach, and will be broken down by both method and grouping of factors. 

1.	Part 1: Demographic, Socio-economic, and Environmental Statistics. This will focus on demographic descriptive statistics of country level factors that MAY show vulnerable populations based on current hypotheses. For example, we hear that people over the age of 65 are at high risk of mortality. We will take this as truth (until proven otherwise) and use country level data on population distribution to highlight what countries have an older vs. younger population.  

2.	Part 2: Country preparedness. This assessment would look at scores as assessed by the Joint External Evaluations (JEE) and or Nuclear Threat Initiatives (NTI) Global Health Security Index, and highlight country level preparedness vs trends in infection/mortality.   

3.	Part 3: Factor analysis. This third paper in a series will test for correlations between the factors identified in the previous two papers, and mortality rates as reported by the CDC and other official outlets. The statistical will stay live on a website and update over time.
