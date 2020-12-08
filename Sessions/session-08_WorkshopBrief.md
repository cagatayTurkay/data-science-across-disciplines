# Session-08: DATA SCIENCE WORKSHOP  

## BRIEF: Analysing Health Indicators

In this practical, your task is to use visualisation effectively to support a "stakeholder" in informing a decision using data. And you will design and conduct a tiny data science approach to support your stakeholders decision making process.

We will be using data made available through the [Health Profiles Programme](https://fingertips.phe.org.uk/profile/health-profiles).  On their web pages, Health Profiles (HP) programme is defined as:

>  Health Profiles is a programme to improve availability and accessibility for health and health-related information in England. The profiles give a snapshot overview of health for each local authority in England. Health Profiles are produced annually.


Designed to **help** local government and health services **make decisions and plans** to improve local people's health and reduce health inequalities, the profiles present a set of health indicators that show how the area compares to the national average. The indicators are carefully selected each year to reflect important public health topics.*

In this exercise, your task is to inform the your *selected stakeholder* on the relations between health indicators and socio-economic and demographic indicators. 

## DATA

**From Health Profiles Programme:**

In this case, we are lucky that the authorities have nicely structured the data and made sure that it is easily possible to join the different data sets. We will be using the [information collected and made available through the Health Profiles Portal](https://fingertips.phe.org.uk/profile/health-profiles).

The data is **for each local authority in England** and presented in the form of indicators that have been carefully processed and made available for analysis (e.g., grouped under categories such as "Our communities", "Disease and poor health", etc.).

[Through this link](https://fingertips.phe.org.uk/profile/health-profiles/data#page/0/gid/1938132696/pat/6/par/E12000004/ati/101/are/E07000032), you can investigate the data visually and download data on a single indicator in either CSV or Excel format. Each file starts with a meta-data section where the indicator is described so these brief information should be sufficient to understand the contents of the file. However, if you want to get a deeper understanding of the indicators and read about how they have been collected, you can [have a look at this detailed page about the indicators](https://fingertips.phe.org.uk/profile/public-health-outcomes-framework/supporting-information/further-info). Note that the actual indicator values are under the column "***Value***" in the joint files.

The indicators are available from the above link but you can also download [a csv with all the indicators in a zipped file here](https://moodle.warwick.ac.uk/mod/resource/view.php?id=1167665).

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
- Consider if you can make use of any design thinking tools, some examples here: https://www.designkit.org/methods, for instance, you can reflect on this brainstorming guidance to help with your discussions as a group: https://www.designkit.org/methods/brainstorm

***Tasks to complete***

**T4:** Develop one or two analytical questions that you want to address

**T5:** Clarify which data variables you will be using in your analysis in order to answer your research question

#### Step-3: Plan an analysis approach/strategy

- Decide on an analysis strategy, which methods will you use and how they can help you respond to your question. 
  - Try to decide on some high level strategies, e.g., "will develop a regression model predicting XXX using variables associated with YYY", or "will apply some clustering algorithms on variables associated with XXX to look for some emerging groups"
- Also identify which data variables could be used with which technique.
- You can already use a Jupyter Notebook document as a template. Set some headers to indicate the different stages of your analysis.

***Tasks to complete***

**T6:** Develop an analysis plan on which techniques you want to use and which data variables you will incorporate. 

#### Step-4: Conduct your analysis 

- Conduct the analysis following your plan. You might find yourself reflecting back on your decisions in the earlier steps and doing things differently to your plan.
- Make good use of exploratory analysis, you might find out that data is different to what you were expecting it to be or new patterns might emerge.
- Think of how you can visualise the data and the results from the tools you use
- Make use of existing Jupyter Notebooks and pieces of code from the labs

***Tasks to complete***

**T7:** Conduct your analysis using Jupyter Notebook by documenting your decisions as you go along.

#### Step-5: Presenting the results (Note: To be presented on Week-10)

- Think about how you will present your results, extract insights, and extract some key visualisations 
- If you need more time to work as a group on your analysis, arrange some time to meet and finalise some bits
- Start a slide-deck and prepare max three slides to:
  - Introduce your persona/context
  - List your analytical questions
  - Present some results from your analysis

***Tasks to complete***

**T8:** Prepare to present your results

**Note:** We'll tell you how to get your slides to us

## Workshop Timeline

We have a total of 2 hours for the session, so roughly 120 minutes.

**15 min:** Introduction and breakout into groups

**20 min:** Step-1, Sketch a hypothetical scenario and a stakeholder

**15 min:** Step 2, Identify analytical questions and data    

**15 min:** Step-3, Plan an analysis approach/strategy

**10 min:** Break / Reflect

**40 min:** Step-4, Conduct your analysis (if you have the time, plan and move to Step-5)

**5 min:** Groups reconvene, debrief

**+ Week-10 reporting back, 2-3 min. from each group**



