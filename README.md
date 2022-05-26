# Linear Regression: GDP per Capita vs Relative Size of Service Sector

## Code and Resources Used

**Excel**
**Packages:** Analysis Toolpak - Linear Regression

## Executive Summary
Term 1 group project for Data Analytics class at IE university - part of the Masters in Management program.

### Project Scope

“Structural Transformation” is a theory in economic development that makes the following prediction: **"as a country's economic activity shifts from agriculture, to manufacturing to the services sector, gdp per capita will rise".** 

If this holds true, then the **implications for developing country policy-makers** aiming to raise gdp per capita are significant - support policies that encourage a structural transformation of the economy away from low-productivity activites to higher-productivity activities. Of course, every country must identify and execute policies tailored to its own needs and goals. However, a model describing the relationship between relative service sector size and gdp per capita may be of value to:

1. Policy makers responsible for managing fiscal and regulatory policies.
2. Researchers in the field of economic development.
3. Advocacy groups pressuring governments to invest for a country's future. 

If there is a strong linear relationship, the following policies might be of interest.

1. Investing in education by [supporting/creating STEM courses](https://www.millenniumpoint.org.uk/invest-in-stem/) and widening access to these through scholarship schemes.
2. Investing in basic technology infrastructure, such as [broadband, open sourced softwares and hardwares.](https://digital-strategy.ec.europa.eu/en/library/study-about-impact-open-source-software-and-hardware-technological-independence-competitiveness-and)
3. Creating [Business Enabling Environments (BEEs)](https://www.worldbank.org/content/dam/doingBusiness/pdf/BEE-Pre-Concept-Note---Feb-8-2022.pdf) to (1) attract foreign business and benefit from foreign technology transfers, and (2) promote local innovation clusters enabling development of local technology.

## Sample Data
<p align="center">
<img width="600" alt="Screen Shot 2022-05-26 at 12 27 20 PM" src="https://user-images.githubusercontent.com/64847974/170470183-c0b080a8-50fc-4b06-a80a-08a396a969b9.png">
</p>

## Scatter Plot

Interpretation: This chart shows a moderetaly strons positive linear relationship (Correlation 0.58) between GDP/K and Services value added; but it also shows that there is still considerable variability around the line of best-fit. We will now run a linear regression to capture more concretely the relationship between the two variables.

<p align="center">
<img width="600" alt="Screen Shot 2022-05-26 at 12 27 45 PM" src="https://user-images.githubusercontent.com/64847974/170470252-22a1ecb9-cea5-4df4-8ad5-2509e6b3be5d.png">
</p>
  
## Linear Regression

**Regression Output 1**

<p align="center">
<img width="600" alt="Screen Shot 2022-05-26 at 12 30 40 PM" src="https://user-images.githubusercontent.com/64847974/170470759-8dce8b0a-7248-4b1d-9019-aecdb1e530bc.png">
</p>

**Regression Output 2**

<p align="center">
<img width="600" alt="Screen Shot 2022-05-26 at 12 30 56 PM" src="https://user-images.githubusercontent.com/64847974/170470804-a01fd379-ab48-45a2-aa69-838fdec55677.png">
</p>

## Insights

**Model**
1. There is a positive correlation between the size of the GDP per capita and share of service sector in the countries of the sample.
2. The Structural Transformation theory just barely holds weight based on the cross-sectional data sampled.
3. The significance of the linear model allows us to infer that the relationship between the two variables can be extrapolated to the larger population and other samples within that population.

## Where to go next?

Although a first step, by only comparing one independent variable (% of gdp from service sector), our analysis is limited. The following are a just few **data-driven** methods to validate the structural transformation theory. 

1. Cross-sectional: Regression between wealth and the agriculture value added (% of GDP). A negative correlation between these two variables further supporting the theory.
2. Time-series: Regression analysis using time series data for a single country on service sector, manufacturing sector and agricultural sector (% of GDP). A positive correlation against time for services and manufacturing and a negative correlation against time for the agriculture would further support the theory. 
3.Our model explained 29% of the variation in gdp/capita. It would be interesting to run the linear regression with more features, such as:

1. Labor force with advanced education (% of total)
2. 2. Ease of doing business indicators
3. Proportion of population with internet access (% of total)






