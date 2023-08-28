# CAPSTONE-PHASE-5
ANALYZING & FORECASTING GROSS DOMESTIC PRODUCT (GDP) TRENDS
(Case Study - Kenya)
Introduction
Kenyan Parliament recently, on the 26th June 2023, passed to law the contentious Finance Bill 2023 proposing a raft of tax policy measures which aim to yield additional revenue and explore more effective measures to enhance Country's revenue collection.

The House argued that, in comparison to other comparable African countries’ Tax revenue as a percentage of Gross Domestic Product (GDP) like Botswana’s 24 percent, Mauritius’ 18 percent and Zambia’s 17 percent, Kenya was falling behind in terms of tax revenue collection at 13 percent as at 2021. The mentioned countries have since managed to achieve higher tax revenue collection rates thus highlighting the need to reassess Country's tax policies and explore more effective measures to enhance revenue collection.

The Government feels the ratio of tax revenue as a percentage of Gross Domestic Product (GDP) being well below acceptable levels to enable spur economic growth & reduce cost of living in the long term. (According to the World Bank, tax revenues above 15% of a country’s GDP are a key ingredient for economic growth and, ultimately, poverty reduction)

Taxes are a critical measure of a nation’s development and governance. The tax-to-GDP ratio is used to determine how well a nation's government directs its economic resources. Higher tax revenues mean a country is able to spend more on improving infrastructure, health, and education—keys to the long-term prospects for a country’s economy and people.

Some of the questions a taxpayer might ask based on the proposed bill might include:

Is GDP level growing proportionately to the projected tax revenue collections to enable government meet its target?

What are the alternatives or other focus areas in case government fails to meet its tax projections?

Policymakers use the tax-to-GDP ratio to compare tax receipts from year to year because it offers a better measure of the rise and fall in tax revenue than simple amounts.

Hence GDP becomes a critical factor to explore, predict and assist determine if the country is in line to achieve its bold aspirations within the next 3-4 years as committed.

Business Understanding
The tax-to-GDP ratio is a measure of a nation's tax revenue relative to the size of its economy. GDP is a vital economic indicator that reflects the overall economic performance of countries and guides policy-making, investment decisions, and strategic planning.

*Project shall aim to analyse Country's historical GDP trends and forecast future GDP growth. The analysis shall assist provide insights into economic growth patterns, identify emerging trends, and support evidence-based decision-making for various stakeholders.*

Data Understanding & Preparation
Data downloaded from The World Bank website database (https://datatopics.worldbank.org/world-development-indicators) and saved remotely for preprocessing. Our target variable (GDP) & other features/indicators columns collected over a period of time explained as below: Daily data aggregated (Weighted average aggregation method); annualized & expressed in U.S. Dollars for each period unless stated otherwise.

Year: Annual periodicity (62 year trend analysis obtained between 1960 & 2022)
GDP: Gross Domestic Product
Exports: Total transactions value in goods and services from residents to non-residents
Imports: Total transactions value in goods and services from non-residents to residents.
ExchRate: Exchange Rate - Local currency per U.S. Dollar period average expressed in National Currency Unit
InfRte: Inflation Rate
Population: Total Population of a country
TaxRev: Total tax revenue collected.
LbrFrce: Labor Force
UnEmpRte: Unemployment Rate
EmpRte: Employment Rate
GrossDomSavg: Gross Domestic Savings
GrossConsump: Gross Consumption/Expenditure
IntPen:Individuals using the Internet (% of population): Internet Penetration Rate
AgriOutput: Agriculture, forestry, and fishing, value added; generally focuses on production or manufacturing processes, marketing or services that increase the value of primary agricultural commodities
Noting that Time Series Analysis Models work on Uni-variate data; and for a deeper mastering of topic at hand; we shall go an extra step to explore all the columns & their relationships, with our predictor/target variable (GDP) & with each other.
