# Economic Freedom Analysis

## Objective
This study analyzes the the relationship between a country's Economic Freedom compared to GDP, CPI, education enrollment of women, population structure, landlocked, Least Developed Country as defined by the IMF.

## Storyboard
https://public.tableau.com/views/EconomicFreedom_16995902560790/DeterminantsofEconomicFreedom?:language=en-US&:display_count=n&:origin=viz_share_link

## Data

### Dependent Variable

I use an Economic Freedom index published by the Fraser Institute for my dependent variable. The Fraser Institute (https://www.fraserinstitute.org) is a research and educational organization that studies and measures the effects of government policies, entrepreneurship, and choice. The Fraser Institute datasets are used by many academic disciplines including development economists. 

The Economic Freedom index measures the economic freedom of individuals – their ability to make their own economic decisions. Economic Freedom involves personal choice, voluntary exchange coordinated by markets, freedom to enter and compete in markets, and protection of persons and their property from aggression by others. In other words, an individual has economic freedom when their property is protected by the government and they can easily and voluntarily participate in markets. In economically free countries, the government’s primary role is protecting personal property from aggression by others. A highly ranked country’s government and systems will protect property, have a fair justice system, have even enforcement of contracts, and a stable monetary environment. Taxes will be relatively low, there will be relatively few barriers to domestic and international trade, and the allocation of goods and resources will primarily be performed by markets rather than government spending and regulation. 

Economists are very interested in measures such as the Fraser Institute’s Economic Freedom index because economic freedom is a one of the most important determinants of an economy’s growth. A small (per capita) economy is much, much more likely to grow when people have economic freedom. Many studies have shown that Economic Freedom is the key determinant when a relatively poor country begins to step up the poverty ladder and its GDP per capita begins to grow. 

The Fraser Institute studies and indexes several components such as size of government, legal systems and personal property rights, monetary stability, freedom of trade, and market regulations. Each country (or state, or province) receives a weighted rating in each area, thus giving the index. Countries such as Singapore, Hong Kong (SAR – separately from China), Switzerland, and New Zealand tend to have the highest Economic Freedom ratings. Countries such as Venezuela, Zimbabwe, Syria, Sudan, Yemen, and Iran tend to have the lowest Economic Freedom ratings. 

The data set includes data from 1970-2021 and includes 165 countries. The Fraser Institute includes indexes for many of the components of Economic Freedom, but I focus only on the final Economic Freedom Index. This data is readily available for research on the Fraser Institute’s website. 

### Independent Variables

I use several independent variables from the United Nations website (http://data.un.org). 

•	GDP (Gross Domestic Product) refers to the general size of a country’s economy. <br>
•	Population variables, including some gender separated.<br>
•	CPI (Consumer Price Index) is a measure of inflation.<br>
•	Labor Force data includes unemployment as well as labor force participation.<br>
•	Education includes enrollment data. <br>
•	A list of countries and their continents on Statistics Times, which cites the UN Statistics Division. <br>
•	The World Bank categorizes economies by income: High, Upper-Middle, Lower-Middle, and Low based on GNI (Gross National Income). <br>
•	I created a variable that equals 1 if the country is landlocked and 0 otherwise as well as a variable that equals 1 if the country is an LDN (Least Developed Nation, as defined by the UN based on the net income per capita of a nation.  (This data is from UNCTAD, UN Conference on Trade and Development,  https://unctad.org/topic/landlocked-developing-countries/list-of-LLDCs. )<br>
•	I created a variable that equals 1 if the country has English as an official language or if it is widely spoken. This data came from the CIA World Factbook. (https://web.archive.org/web/20070613004519/https://www.cia.gov/library/publications/the-world-factbook/fields/2098.html) <br>

## Tools
I use Excel and Python: Jupyter notebooks via the Anaconda Navigator to complete this project. I used the following libraries: Pandas, Numpy, matplotlib, and seaborn. I use Tableau Public for the final Storyboard.

## Results
* GDP and CPI are correlated with economic freedom. 
* In addition to the two main indices supporting conomic freedom, female upper secondary enrollment and percent of population under 14 years old, there are several other variables that also impact women’s Economic Rights and are incredibly important to a nation’s economic prosperity. 
* My finding suppor the hypothesis that women's Economic Freedom is particularly import to a nation's success!
