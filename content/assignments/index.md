---
title: Assignments
---
## Overview

| Component                             | Undergraduate | Master's   | Doctoral   | Due Date |
|---------------------------------------|---------------|------------|------------|----------|
| [National Housing Market Analysis Memo](#national-housing-market-analysis-memo) | 10%    | 10% |            | February 11 |
| [Local Housing Market Analysis Memo](#local-housing-market-analysis-memo)    | 10%    | 10% |            | March 11|
| [Housing Needs Analysis Memo](#housing-needs-analysis-memo)           | 10% | 10% |            | April 8 |
| [Housing Policy Analysis Memo](#housing-policy-analysis-memo)          | 30% |            |            | May 6 |
| [Housing Policy Platform](#housing-policy-platform)               |               | 40% |            | May 6 |
| [Term Paper](#term-paper)                            |               |            | 75% | May 11 |
| [Op Ed](#op-ed)                                 |               |            | 15% | May 11 |
| [Discussion Facilitation](#discussion-facilitation)               | 10% | 10% | 10% | Varies |
| [Midterm and Final Exams](#midterm-and-final-exams)               | 30% | 20% |            | March 21 and May 11 |

## National Housing Market Analysis Memo

### Assignment:

The environment for housing is ever-evolving. One challenge facing housing policy practitioners is understanding the changing context for the nation's housing, as well as the evolving needs of housing consumers. In class, you have examined several important sources of information that describe the national housing environment in the United States, many of them summarized in the Joint Center for Housing Studies’ [State of the Nation’s Housing](https://www.jchs.harvard.edu/sites/default/files/reports/files/Harvard_JCHS_State_Nations_Housing_2021.pdf) report. For your first assignment, you will produce your own analysis and summary of current housing market trends for the nation. Unlike the JCHS report, your analysis need not be comprehensive, but it should provide a detailed profile of *a component* of the nation's housing.

Drawing from available secondary data such as the [American Community Survey](https://www.census.gov/programs-surveys/acs), [Census Public Use Microdata](https://www.census.gov/programs-surveys/acs/microdata.html), the [Census Household Pulse Survey Measuring Household Experiences during the Coronavirus (COVID-19) Pandemic](https://www.census.gov/data/experimental-data-products/household-pulse-survey.html), produce an analysis of a component of the national housing environment, paying particular attention to three themes as they relate to this component:

* **Housing Supply:**	What is the composition of the housing stock, how many units are owned? Rented? How many units are in single-family or multi-family structures? How many units are occupied and vacant?

* **Housing Demand:**	What is the demographic composition of the population with respect to their housing? Who owns? Who rents? Who can afford what housing? 

* **Theme of Your Choice:**	Explore a third theme of your choice that builds upon your analysis of supply and demand. Focus on building an analysis and narrative that provides a detailed examination of a particular issue or question of your choice.

Prepare your profile as a memorandum of approximately 3,000 words (6 single-spaced pages, excluding tables, illustrations, and references). Your memorandum should include sufficient analysis and properly referenced evidence for another housing expert to measure the strength and validity of your assertions. The judicious use of maps, imagery, and tables should be included to support your analysis.

As you set out to develop your memorandum, keep in mind that your national analysis will serve as valuable context for your remaining assignments in this class which will all focus on building a more in-depth profile of a local housing market in the U.S.

### Data Resources and Analytical Guidance

For this assignment, you may draw upon a range of available data sources. Because many of you are not familiar with some of the common sources of housing data, I have pre-downloaded and prepared some basic data for the nation, states, and at the census tract scale which may be useful to you:

* [Class Data Repository](https://github.com/agreen4/UP-473-S22-Code) includes R scripts as well as data tables for the primary indicators mentioned in this assignment. Please note that scripts are posted for your reference. You are not expected to know or use R in this class.

* **American Community Survey:** The Census Bureau’s American Community Survey (ACS) is the first place to look for data that will help you to describe your housing market and housing consumers. The [data.census.gov](https://data.census.gov) website allows you to query data for different survey years and geographies. To help you get started, I have downloaded data for the 2010 and 2019 5-year American Community Surveys for the U.S. as a whole, and for each state in the U.S.. Cross referencing the data in these CSVs with the tables they come from on data.census.gov will be useful in producing your summaries.

* **Other Data Sources:** Depending upon what you choose to focus on for this assignment, you may want to draw from other data sources. We'll set aside some time in class to discuss approaches to information in more detail and to workshop your individual approaches to the assignment.

Below, you will find helpful information including ACS table numbers (e.g. the population table is B01003) as well as some guidance on initial analysis steps that will help you get started with your analysis:

### Population Demographics 	

* Examine the demographic characteristics for your place and describe who lives here. In addition to the provided tables, explore other ACS tables that may prove insightful. In reporting out demographic conditions, produce your own summaries of elements from ACS tables instead of reporting tables verbatim.

| Indicator | Table Number |
|-----------|--------------|
| Population| B01003 |
| Race			|	B02001 |
| Latino Ethnicity | B03002 |
|	Age				| B01001 |
|	Average Household Size | B25010|
|	Foreign Born Population	| B05002|

* **Economic Conditions:**	Use the median household income statistics to describe the incomes for households earning 120%, 80%, 50%, and 30% of median income

| Indicator | Table Number |
|-----------|--------------|
| Median Household Income| B19013 |

* **Trends by Tenure:**	Determine housing affordability for renters and owners at median income, 120%, 80%, 50%, and 30% of median income (remember that the federal standard for housing affordability is 30% of median income). Your analysis should compare monthly income to the median rent and owner costs (which are also reported as monthly costs) to determine for which percentages of median income the median priced housing unit is affordable.

Determine what percentage of median income is required to be able to afford the median rent and mortgage payments in your housing market.

| Indicator | Table Number |
|-----------|--------------|
| Tenure | B25003 |
| Median Rent | B25064|					
| Median Owner Costs | B25088 |
|	Vacancy Rate	|	B25002 |

**Public Use Microdata Series (PUMS):** The American Community Survey is distributed both as a series of pre-generated summary tables (which you are making use of above), but another data product, the Public Use Microdata Series, can also be useful for exploring housing relationships. PUMS data allow you to look at a set of records that are reflective of the entire population, but also allow you to drill down into more detail on relationships that describe those households. I have downloaded and prepared some PUMS data for you consolidated to the entire U.S. and to states by racial identity. Use these data to help describe elements of supply and demand, and to explore other issues you’d like to look at.

| Indicator | Description |
|-----------|--------------|
| Population | The total number of people in the geography |
| P_Female | Proportion of population that is female |
| Bedrooms | Average number of bedrooms per housing unit |
| Type_	|	Total population by housing type. <br> Type_House encompasses the population living in owned or rented housing units. <br>Type_IGroup encompasses the population living in institutional group settings (correctional facilities, nursing homes, mental hospitals). <br>Type_NIGroup encompasses the population living in non-institutional group settings (college dorms, military barracks, group homes, shelters).|
| HU_ |		Population living in housing units by number of units in building (Single Family, 2-4 unit, 5-9 unit, 10-19 unit, 20-49 unit, 50 plus units). |
| Rent |		Average rent (for rented units) |
| Owner_Costs |	Owner monthly costs (for owner-occupied units; mortgage and other expenses).|
| Property_Value_Mean |	Average property value for owner-occupied housing units.|
|Household_Income|	Average Household Income|
|Tenure_|	Housing tenure (rented, owned)|
|Unit_Built_|	Population in unit built by year (Before 1950, 1950-2000, After 2000)|

**Census Household PULSE Survey:** The Census Bureau has recently deployed a short survey regarding how people’s lives have been impacted by the COVID-19 pandemic. These data are reported on a weekly basis starting April 23, 2020, and include information on a range of issues including housing. Data are reported for the U.S. and are also broken out by state. I have downloaded four housing tables for weeks 1, 6, and 12 of the PULSE survey. You may want to take a look at some of the other tables or weeks available and incorporate them in your analysis as well.

**Other Data Sources:** You may wish to integrate other data sources into your analysis. Please speak with me (proactively) about the use of other sources or about ideas. I can help you to identify other data sources or variables which I have not prepared and downloaded which may be useful for your analysis. 

### Assignment Submission

Please submit your assignment components electronically via your Box Assignment Dropbox.

## Local Housing Market Analysis Memo

In seeking to intervene in local and regional housing environments, housing policy analysts face the challenge of describing past and present housing dynamics while also looking towards the future. This assignment asks you to practice these skills by developing an in-depth understanding of a regional housing market of your choice.

At a most basic level, housing policy analysts have to 

  a) describe the geography and composition of the housing market(s) they are analyzing; 

  b) describe who gets what housing in those markets; and, 

  c) describe the economic environment in which the housing markets operate. 

After distilling salient trends and features, housing policy analysts can then identify the overall health and function of the housing market, likely future influences, and special populations that should receive particular care or intervention.

In this assignment, you will begin defining and exploring a housing market of your choice, focusing on current conditions and housing market trends within the last 10 years. You will use multiple sources of secondary data to describe the local housing market, its demographic and economic conditions, trends for renters and owners, and likely future influences. You will also identify one or more specialized populations and will briefly describe their housing needs (your third assignment asks you to build upon your analysis by performing a detailed housing needs assessment for the specialized population you identify). 

Your housing market analysis should describe the following:

* **Demographic Conditions:**	What are the salient demographic characteristics of the households in your housing market?
	
* **Economic Conditions:**	What local or regional economic conditions shape the housing environment? How do the types of jobs that people have shape the economic environment for housing? How does housing consumption influence the local economic environment?

* **Trends by Tenure:**	How do changes in the housing market differ for renters and owners? 

* **Future Influences:**	Based upon the recent past, what are likely future influences within the local housing market?

* **Specialized Populations:**	Based upon your analysis of demographic conditions, economic conditions, and housing market trends, what specialized populations emerge who are particularly likely to face housing vulnerability in the future or who will be disparately impacted by the future influences you identify? 

### The Deliverable

Prepare your profile as a memorandum of approximately 3,000 words (6 single-spaced pages, excluding tables, illustrations, and references). Your memorandum should include sufficient analysis and properly referenced evidence for another housing market expert to measure the strength and validity of your assertions. The judicious use of maps, imagery, and tables should be included to support your analysis.

In preparing your analysis, you may want to first look for other recent analyses of your local market. Good starting places would be to search for the most recent Analysis of Impediments to Fair Housing, local Analysis of Fair Housing, HUD Comprehensive Housing Market Analysis, or for housing analysis completed as part of a neighborhood, local, or regional plan.

Please also note that I am not specifying or constraining the geography which you are required to conduct your analysis at. In selecting a particular geography, you’ll need to think carefully about what make sense – how does a particular geography constitute a housing market (or series of submarkets)? You will need to describe the definition you select and will need to justify your choice. Once you do, you should also plan to compare the characteristics of your local housing market (however you define it) to its region and the state in which it's located. 

I encourage you to reach out to me as you work to define your market, to get confirmation that you have selected an appropriate geography. Keep in mind that you will be working with this selection over the course of the semester for your remaining assignments in the class.

### Data Resources and Analytical Guidance

Our [class data repository](https://github.com/agreen4/UP-473-S22-Code) includes R scripts as well as data tables for the primary indicators mentioned in this assignment.

The Census Bureau’s American Community Survey (ACS) is the first place to look for data that will help you to describe your housing market. The [data.census.gov](https://data.census.gov) website allows you to query data for different survey years and geographies. To help you get started, I have downloaded data for the 2010 and 2019 5-year American Community Surveys at the census place level which are accessible on the course Box site. To successfully complete the assignment, you may also want to download data for other geographies or time periods on your own.

Below, you will find helpful information including ACS table numbers (e.g. the population table is B01003) as well as some guidance on initial analytical steps that will help you get started with your analysis:

* **Population Demographics:**	Examine the demographic characteristics for your place and describe who lives here. Explore other ACS tables that may prove insightful. In reporting out demographic conditions, produce your own summaries of elements from ACS tables instead of reporting tables verbatim.

| Indicator | ACS Table Number |
|-----------|------------------|
|	Population| B01003 |
|	Race				B02001 |
| Latino Ethnicity | B03002 |
|	Age | B01001 |
|	Household Size | B25010 |
|Foreign Born Population	| B05002 |

* **Economic Conditions:**	Determine the median income for your housing market, as well as the incomes for those earning 120%, 80%, 50%, and 30% of median income

| Indicator | ACS Table Number |
|-----------|------------------|
| Median Household Income | B19013 |
| Vacancy Rate | B25002 |

* **Trends by Tenure:**	Determine housing affordability for renters and owners at median income, 120%, 80%, 50%, and 30% of median income (remember that the federal standard for housing affordability is 30% of median income). Your analysis should compare monthly income to the median rent and owner costs (which are reported as monthly statistics) to determine for which percentages of median income the median priced housing unit is affordable.

Determine what percentage of median income is required to be able to afford the median rent and mortgage payments in your housing market.

| Indicator | ACS Table Number |
|-----------|------------------|
|	Tenure		| B25003 |
| Median Rent | B25064 |
|	Median Owner Costs | B25088 |

* **Future Influences:** To examine future influences, you are going to perform some very crude projections of housing characteristics. You will find more information on performing these projections at the very end of this assignment.

  - Based upon housing costs in 2010 and 2019, project housing costs for owners and renters to the year 2030.

  - Based upon the median income in 2010 and 2019 project median income for 2030. What percentile of median income will be required in 2030 to afford to rent a median priced housing unit? What percentile of median income will be required to pay the mortgage on a median housing unit?

  - Based upon change in housing units from 2010 and 2019, project the number of housing units that will be constructed in your place by 2030.

  - How many new households do you project will live in your place by 2030? To calculate this, project the population to 2030 as well as the average household size and then use the ratio of population to average household size to approximate households.

### Performing Simple Projections

One of the simplest methods of projection is to fit a line between two sets of observed points, and then project future values based upon that line. 

You may remember from your past geometry training that the slope of a line can be calculated as follows:

slope = $\frac{(y_2-y_1)}{(x_2-x_1 )}$
	
Let’s calculate the change in population for a hypothetical location called Busytown. In 2010, the population of Busytown was 8,000 and by 2020 the population was 9,750. Here’s how we would find the annual rate of population change for Busytown between 2010 and 2020:

change = $\frac{(9750-8000)}{(2020-2010)} =  \frac{1750}{10} = 175$

Busytown’s population increased by 1,750 over 10 years – an increase of 175 people per year. If we assume that future population will grow at the same rate per year, we can now calculate the future population for Busytown in any future time period:

$ Population_Future = Population_Base + Change*Time Periods$

Here’s the equation for Busytown assuming a base year of 2020, and projecting the population to 2030, which is 10 years in the future:

$Population_Future = 9750 + 175 * 10$

Therefore, we project that if the population grows at the same rate it did between 2010 and 2020, the total population will be 9,750 + 3,250 = 11,500 in 2030.

### Assignment Submission

Please submit your assignment components electronically via your Box Assignment Dropbox.

## Housing Needs Analysis Memo

In your second assignment, you described elements of housing supply and demand and also identified the specific housing consumers present within your housing market. For this assignment, you will spend more time thinking about the housing needs associated with these consumers. Specifically, you will draw from elements of HUD’s Assessment of Fair Housing methodology to analyze your housing market’s demographics, patterns of spatial integration and segregation, and the intersectionality between housing and other needs. Together with your Housing Market Analysis, your Housing Needs Analysis will constitute the basis for your final assignment – a housing policy platform – which will focus on designing intervention to address the needs you identify within your local housing market.

Drawing from the [HUD AFFH Guidebook](https://www.hud.gov/sites/dfiles/FHEO/documents/AFFH-Rule-Guidebook.pdf) and the [HUD AFFH Data](https://www.hud.gov/program_offices/fair_housing_equal_opp/affh), analyze the needs present within your local housing market. At a minimum, your housing needs analysis should address the following:

* **Demographic Summary:**	Describe demographic patterns in the housing market and describe trends over time. Describe the location of homeowners and renters in the housing market, and describe trends over time. 

For further guidance, see the AFFH Rule Guidebook §5.5.1.
	
* **Segregation and Integration:**	Describe and compare segregation levels in the housing market and region. Identify the racial and ethnic groups that experience the highest levels of segregation. Explain how these segregation levels have changed over time. 

Identify areas with relatively high segregation and integration by race/ethnicity, national origin, or LEP group, and indicate the predominant groups living in each area. 

Consider and describe the location of owner and renter occupied housing in determining whether such housing is located in segregated or integrated areas. Discuss how patterns of segregation have changed over time.

Discuss whether there are any demographic trends, policies, or practices that could lead to higher segregation in the jurisdiction in the future.

For further guidance, see the AFFH Rule Guidebook §5.5.2

* **Concentration of Poverty:**	Identify any R/ECAPs or groupings of R/ECAP tracts within the jurisdiction. Which protected classes disproportionately reside in R/ECAPs compared to the housing market and region?

Describe how R/ECAPs have changed over time. 

For further guidance, see the AFFH Rule Guidebook §5.5.3

* **Access to Opportunity:** 	Describe disparities in access to opportunity, including access to education, employment, transportation, low poverty exposure, and environmentally healthy neighborhoods, as well as any overarching patterns relating to access to opportunity in the region.

Identify and discuss any overarching patterns of access to opportunity and exposure to adverse community factors based on race/ethnicity, national origin, or familial status. Identify areas that experience an aggregate of poor access to opportunity and high exposure to adverse factors. 

For further guidance, see the AFFH Rule Guidebook §5.5.4

* **Disproportionate Needs:**	What groups by race/ethnicity and family status experience higher and severe rates of housing cost burden, overcrowding, or substandard housing when compared to others?

Which areas in the housing market experience the greatest housing burdens, and how do these burdens align with segregated areas, integrated areas, R/ECAPs, and what is the predominant race/ethnicity or national origin group in such areas?

For further guidance, see the AFFH Rule Guidebook §5.5.5

* **Disability and Access:**	How are persons with disabilities geographically dispersed or concentrated in the housing market, including R/ECAPs and other segregated areas identified in previous sections? Describe whether these geographic patterns vary for persons with each type of disability or for persons with disabilities in different age ranges.

To what extent do persons with disabilities in or from the jurisdiction or region reside in segregated or integrated settings?

For further guidance, see the AFFH Rule Guidebook §5.5.7

After analyzing these dimensions of housing needs, provide an overall summary of housing needs present within your housing market, and an assessment of how these needs relate to those within the broader region. As part of your summary, identify one or two priority populations based upon your assessment of needs and housing impacts within your housing market, and describe the needs of these populations. The priority populations which you identify will constitute the focus of your housing policy platform (your final assignment).

### Deliverable

Prepare your assessment as a memorandum of  around 3,000 words. Your memorandum should include sufficient analysis and properly referenced evidence for another housing market expert to measure the strength and validity of your assertions. The judicious use of maps, imagery, and tables should be included to support your analysis.

### Data Notes

You will need to construct your own summaries from the AFFH Raw Data – please note that this process is time-consuming – leave yourself plenty of time to work through this. For more specifics on data and indicators, please also see HUD's data documentation.

### Assignment Submission

Please submit your assignment components electronically via your Box Assignment Dropbox.

## Housing Policy Analysis Memo

Drawing directly from the analysis and arguments you made in your first and second assignments, your final assignment asks you to propose a housing policy intervention intended to impact your local housing market. Your analysis should be directed towards a professional audience consisting of planners and other decision-makers, and should be appropriately targeted towards institutions and decisionmakers that best correspond to the geography(ies) which are dictated by the issues which your policy targets.

Your analysis needs to accomplish several things:

1)	**Define** – your report needs to provide background on the nature and extent of the problem or phenomenon which your proposed policy intervention will target. Drawing from your prior analyses, summarize the nature of the problem, the populations impacted, and the public costs or impacts associated with the problem.

2)	**Review** – your report needs to review… 
  a.	How the problem has been addressed in your place in the past, highlighting policy impacts and unmet needs.
  b.	How the problem has been dealt with in other contexts. What strategies have been applied, and how effective have they been? At what geographic scales have other policies been implemented? How have these policies impacted the population your policy seeks to target? What are the trade-offs associated with these different approaches? 

3)	**Propose** – your report needs to propose a new or different policy intended to address the problem. 

  a.	*Policy Overview* – provide a detailed description of the elements of the policy. Through what mechanisms does it create change? How does it interface with other existing policies? How does it relate to the policies you reviewed in Section 2?
    
  b.	*Local Precedents* – what preexisting goals, policies, or plans support the adoption of your policy?
    
  c.	*Eligibility or Impact Criteria* – how will the policy selectively target populations at need? How does targeting meet policy goals without creating the potential for disparate impact?
    
  d.	*Spatial Impact* – which areas, neighborhoods, and populations will be impacted by your policy? How different is your policy’s prospective impact across space?
    
  e.	*Timeline, Outcomes and Measures* – what are the intended outcomes to be observed if your policy is successfully implemented? Over what period of time will implementation occur? Describe intended outcomes in terms of hard numbers or targets (e.g. 5,000 more affordable housing units serving households at 50%-80% AMI in 10 years). What measures or indicators are the most important ways to identify the success (or failure) of your policy?
    
  f.	*Cost and Impact* – provide a rough estimate of the cost of your proposal. How does this cost compare to continuing in the current fashion (business as usual)? How does this cost (and related benefits) accrue over the next 5, 10, and 20 years?
  
4)	**Strategize and Summarize** – Summarize your policy, its impacts, and its benefits. Provide an assessment of the next steps towards policy debate and implementation.

Please note that there are slightly different outputs from this assignment for undergraduate and graduate students (listed below).

### Outputs

Prepare a polished memorandum of approximately 5,000 words. Your memo should be targeted towards a professional audience and should include sufficient analysis evidence for other experts and decision makers in your housing market to weigh the strengths of your claims. The judicious use of maps, imagery, and tables should be included to support your analysis.

## Housing Policy Platform

Following the guidance in the Housing Policy Memo prompt, Master's students will produce a more fully developed housing policy platform with two outputs:

1.	Prepare a polished report of approximately 5,000 words. Your report should be targeted towards a professional audience and should include sufficient analysis and properly referenced evidence for other experts and decision makers in your housing market to weigh the strengths of your claims. The judicious use of maps, imagery, and tables should be included to support your analysis.

2.	Write an op-ed targeting the news venue of your choice that makes a public argument summarizing your problem, the costs of inaction, and the benefits of your proposed course of action. In general, your op ed should be between 600 and 800 words in length, although you should follow the guidelines posted for the target venue you would hypothetically publish your op ed in. The following resources may be useful in strategizing around your op ed: [The Op Ed Project](https://www.theopedproject.org), [Op Ed Length](https://phairadvantage.com/2014/09/more-than-you-wanted-to-know-about-op-ed-length/), [Centre for Policy Writing](https://cepow.org/tips-tricks-for-op-ed-writing/).

### Assignment Submission

Please submit your assignment components electronically via Illinois your Box Assignment Dropbox.

## Term Paper

Doctoral students in UP 473 will produce a term-length paper on a topic of your choice that draws upon the academic literature to engage with a theme related to housing policy. Based upon your interests and needs, this paper could include original empirical analysis of a phenomenon, could be theory-based, or could be focused on synthesizing literature. We will work together to determine an appropriate paper scope and approach. In addition to preparing your term assignment, you will present your paper to the class at the end of the semester.

Your completed term paper will be due at the end of the semester. In order to ensure that you are making adequate progress to meet this deadline, you will submit several intermediate work products including the following:

* **Term Paper Proposal:** a 1-page term paper proposal
* **Extended Abstract:** an extended abstract and paper outline
* **Literature Review:** a review of relevant literature. 

Your final term paper should be between 8,000 and 10,000 words in length (excluding references).  

### Assignment Submission

* Term Paper Proposal: submit via Box Assignment Dropbox

* Extended Abstract and Outline: submit via Box Assignment Dropbox

* Literature Review: submit via Box Assignment Dropbox

* Complete Term Paper: submit via Box Assignment Dropbox


## Op Ed

Write an op-ed targeting the news venue of your choice that makes a public argument summarizing your problem, the costs of inaction, and the benefits of your proposed course of action. In general, your op ed should be between 600 and 800 words in length, although you should follow the guidelines posted for the target venue you would hypothetically publish your op ed in. The following resources may be useful in strategizing around your op ed: [The Op Ed Project](https://www.theopedproject.org), [Op Ed Length](https://phairadvantage.com/2014/09/more-than-you-wanted-to-know-about-op-ed-length/), [Centre for Policy Writing](https://cepow.org/tips-tricks-for-op-ed-writing/).

## Discussion Facilitation

Our class depends upon all of us taking leadership for our course content, learning, and engagement. One way we will sustain our learning together is to take responsibility for discussion facilitation over the course of the semester. During the first two weeks of class, you will sign up to facilitate discussion for one week of the class (Weeks 3-8, 10-14).

### Discussion Facilitators by Week

<iframe src="https://uofi.app.box.com/embed/s/us48x88pqk99fchnu787ub6gl1fhj3az?sortColumn=date&view=list" width="500" height="400" frameborder="0" allowfullscreen webkitallowfullscreen msallowfullscreen></iframe>

### Facilitation Plans


### Tips for Successful Facilitation

1. **Assume a Prepared Audience:** A baseline assumption is that everyone has read the assigned materials for the week - while you may wish to review key concepts from those readings, strong facilitation will not include summarizing assigned content, since everyone should be prepared to discuss them. Strong facilitation may include providing discussion questions, examples, and scenarios that extend concepts from the readings.

2. **Guest Speakers:** There may be some weeks where the class would benefit from inviting a guest speaker as part of your facilitation. As we develop your facilitation plans, I can help you to invite and make arrangements for guest speakers, if this is desired.

3. **Changing Content:** Your facilitation may involve proposing changes or supplements to reading selections. Please outline these proposed changes as part of your facilitation plans.

## Midterm and Final Exams

To be accountable for your learning over the course of the semester, you will complete written take-home midterm and final exams. Please find example exam questions and prompt below.

### Midterm Exam Prompt

[Midterm Exam Prompt](https://uofi.box.com/s/k4gzcd8pnw8k0fuqg4o07s8nbixoe5qs)

So far in class, we have focused on developing theoretical frameworks for understanding the impact of housing and housing policy in the United States, and have interrogated government intervention regarding owned and rented housing. Your midterm examination asks you to reflect and synthesize several dimensions of what you’ve learned so far this semester.

Please respond to three of the following four questions with a well-composed response. Your response to each question should be approximately 800 words. Your responses should reference source material we have relied upon so far this semester but may also incorporate external sources. Please provide references for cited sources (references do not count towards the length of each of your responses).

1.	The Biden administration’s proposed pandemic recovery plans include a major expansion of the federal Housing Choice Voucher Program. What do you see as the potential trade-offs associated with this expansion? How would these trade-offs impact low-income housing consumers? Identify trade-offs related to voucher expansion, review potential alternate intervention approaches, and provide an overall recommendation regarding a preferred course of action.

2.	The push to deconcentrate low-income populations, particularly those residing in public housing, has resulted in a range of national, state, and local policy efforts, with one major approach being the design of planned mixed-income communities. Briefly describe the theoretical rationale for mixed-income communities, and then provide a brief argument either for or against the application of such policies within the modernization of the nation’s most severely distressed public housing stock.

3.	Briefly describe how tenant-based housing subsidies like the Housing Choice Voucher differ from place-based housing subsidies like public housing. How are tenant-based housing subsidies designed to respond to critiques of place-based housing subsidies related to geographic isolation and segregation? What barriers to fair housing choice are frequently experienced by households with tenant-based housing subsidies?

4.	The Federal Housing Choice Voucher (HCV) Program and Low-Income Housing Tax Credit (LIHTC) program both make use of public-private partnerships to deliver affordable housing. Compare and contrast the types of partnership structures that are characteristic of each program. Thinking about these partnerships, what threats or vulnerabilities exist, with respect to the delivery of affordable housing?

### Final Exam Prompt

To be Posted in April

