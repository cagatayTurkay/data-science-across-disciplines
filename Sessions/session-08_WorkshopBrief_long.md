# Session-08: DATA SCIENCE WORKSHOP  

## Analysing Health Indicators

In this practical, your task is to use visualisation effectively to support a "stakeholder" in informing a decision using data. And you will design and conduct a tiny data science approach to support your stakeholders decision making process.

We will be using data made available through two different organisations. One is the [Health Profiles Programme](https://fingertips.phe.org.uk/profile/health-profiles) and the other is the main gateway to London related data, [London DataStore](http://data.london.gov.uk/). On their web pages, Health Profiles (HP) programme is defined as:

>  Health Profiles is a programme to improve availability and accessibility for health and health-related information in England. The profiles give a snapshot overview of health for each local authority in England. Health Profiles are produced annually.


Designed to **help** local government and health services **make decisions and plans** to improve local people's health and reduce health inequalities, the profiles present a set of health indicators that show how the area compares to the national average. The indicators are carefully selected each year to reflect important public health topics.*

and London DataStore describes itself as:

*The London DataStore is a free and open data-sharing portal where anyone can access data relating to the capital. Whether you're a citizen, business owner, researcher or developer, the site provides over 500 datasets to help you understand the city and develop solutions to London's problems.*

In this exercise, your task is to inform the your *selected stakeholder* on the relations between health indicators and socio-economic and demographic indicators. 

**As an optional task,** although the Health Profiles Programme have gathered data on socio-economic indicators, you can also enrich their understanding by **merging data from London Data Store with data from the Health Profiles Programme**.

## DATA

**From Health Profiles Programme:**

In this case, we are lucky that the authorities have nicely structured the data and made sure that it is easily possible to join the different data sets. For the sake of simplicity in this coursework, we will be using the [information collected in 2018](https://fingertips.phe.org.uk/profile/health-profiles).

The data is **for each local authority in England** and presented in the form of indicators that have been carefully processed and made available for analysis (e.g., grouped under categories such as "Our communities", "Disease and poor health", etc.).

[Through this link](https://fingertips.phe.org.uk/profile/health-profiles/data#page/0/gid/1938132696/pat/6/par/E12000004/ati/101/are/E07000032), you can investigate the data visually and download data on a single indicator in either CSV or Excel format. Each file starts with a meta-data section where the indicator is described so these brief information should be sufficient to understand the contents of the file. However, if you want to get a deeper understanding of the indicators and read about how they have been collected, you can [have a look at this detailed page about the indicators](https://fingertips.phe.org.uk/profile/public-health-outcomes-framework/supporting-information/further-info). Note that the actual indicator values are under the column "***Value***" in the joint files.

The indicators are available from the above link but you can also download [a csv with all the indicators in a zipped file here](http://staff.city.ac.uk/cagatay.turkay.1/Teaching/Resources/INM430/Week10/LocalAuthorityHealthProfiles-DistrictUA.data.csv.zip).

**From London DataStore:**

London DataStore has a large selection of datasets at different data resolutions (e.g., borough, ward, etc.) on various aspects of London. You are free to pick any data you like. For instance, the Household Income Estimates as described [here](http://data.london.gov.uk/dataset/household-income-estimates-small-areas) could be a good one. We've curated a file here based on the data on these links. You can[ download the file here](http://staff.city.ac.uk/~sbbk529/Teaching/Resources/INM430/2015/CW01/gla-household-income-estimates-WardLevel.xlsx) which includes data only at the "Ward" level. As suggested, feel free to include any data set, you can choose more than one.

## TASKS

As also described above, the expectation to utilise the relation between the health indicators and socio-demographics information.

#### Step-1: Sketch a hypothetical scenario and a stakeholder

- Identify a stakeholder and define the setting. Think about the **personas** and think about the **context**. Think about questions such as:
  - What are the needs of the people? What do they know and what data is available?
  - What do they need to know?
  - What are some sensitivities?

##### Potential stakeholder involved could be: 

Public Health Officer, Local Authority Officer, Patient-facing Clinician (GP), Clinical researcher,  Patient...

##### Potential situations could be:

Consider yourself/your team to be a data scientists aiming to support:

- A local authority 
- Clinical researcher talking to a public health officer -- how can research outcome inform policy?
- Patient looking for self help -- how to visualise information to inform them?
- GP giving advice to a patient -- how to visualise information to support their conversation?

***Tasks to complete***

**T1:** Explore the datasets through the webpages above to get yourself familiar.

**T2:** Identify a stakeholder and agree on a situation

**T3:** Use this persona template from servicedesigntools.org [[link to template page](https://servicedesigntools.org/tools/personas)] to help outline a stakeholder persona. Consider how you can help your stakeholder through data when responding to these challenges.

#### Step-2: Identify analytical questions and data    

- Identify a number of analytical questions that you can address using the data available and using the analytical tools that we have available.
- Identify the data fields that fit with your scenario
- Choose features that are relevant and speculate what you can achieve with them

***Tasks to complete***

**T4:** Develop one or two analytical questions that you want to address

**T5:** Clarify which data variables you will be using in your analysis in order to answer your research question

#### Step-3: Plan an analysis approach/plan

- Decide on an analysis strategy, which methods will you use and how they can help you respond to your question.
- Identify which data features could be used with which technique.
- 

#### Step-4: Conduct the analysis method

- Conduct the analysis
- You can print out and put in within the context of a narrative/larger design (i.e., an interface / poster)

#### Step-5: Presenting / acting on the results

- Think about how you will present the results 

