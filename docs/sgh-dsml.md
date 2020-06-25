# DSML Notes

## Meetings

### 22 Jun 2020

- Introduction of everyone
- Data analytics
- Digital platform - standing database for research
- Raymond from hospital level, using statistics, for what is happening within the hospital: business data
- QI not strictly in research
- Incubator - some hardware and some software for data analytics
- ![Screenshot 2020-06-22 at 18.24.38](figures/Screenshot%202020-06-22%20at%2018.24.38.png)

- Solve meaningful tractable research, clinical practice, and business challenges

![Screenshot 2020-06-22 at 18.27.40](figures/Screenshot%202020-06-22%20at%2018.27.40.png)

- ![Screenshot 2020-06-22 at 18.28.26](figures/Screenshot%202020-06-22%20at%2018.28.26.png)
- Aggregate for the best return if we want to share resources



Dear Prof Chow, 

Thank you so much for having me at the dsml meeting yesterday. I took some time to reflect on the meeting and have some questions that I would like your thoughts on:

1. What is the expertise that DSML would like to develop to differentiate it from all the other entities that does data science and machine learning in a way that also leverages on the strength of Singhealth to make the work of DSML difficult to surpass?

   

2. DSML hub members working with domain experts; or DSML members who are domain experts.

   - In most of the projects, under the slides on domain experts commitment. 

   `

3. There was the mentioning of the cost of maintenance as an important factor to consider during project selection. 

   - A comment was made when discussing project 3, that due to COVID19 situation, recent data may not translate to prediction that is as reliable for baseline situations. This led to the mentioning of the cost of maintenance, whereby active maintenance is required for projects with dynamically changing backdrop, as opposed to more 'low cost' projects in which we can build a learning algorithm that continues to work. 

   - I would like to point out that the cost of software development and maintenance should not be underestimated, even for algorithms that we do not plan to continue to adjust; software is subjected to influence not only from the developers but also the whole software engineering community. For instance while I was consulting for a medical device company, the company had to actively keep track of Java updates and update their code frequently (for the same functions). In the MIT community there is also and often discussions about how to prevent biases in learning algorithms, which would require frequent checking and re-checking. So given the non-deterministic nature of most of the proposed projects, I think would be risky to dismiss ideas or select ideas based on the static nature of the problem in order to satisfy 'certain cost of maintenance'. Unless perhaps the products of the projects are meant to be short lived and the development phase or deployment phase would not be under the care of DSML. 

     

4. DSML hub members working with domain experts; or DSML members who are domain experts.

   - In most of the projects, under the slides on domain experts commitment. 



I am going to be very bold here and ask for your generosity for me to share some of my reflections from the meeting. Apologises in advance if this is stepping over the line because you obviously have a solid plan in place and being new to the system I do not have the full background to comment on. Yet I do want to highlight a few things that felt important to me arising from the meeting, which were not adequately discussed. If anything is not appropriate, or if there is anything that you feel like commenting on (for a lack of better expression for 指正), please feel free to let me know. As you have shared, this is a learning process for all involved.

In general, I felt very encouraged by all the ground up enthusiasm, and there is great potential in harnessing these energies and interests to do great work that advance medical practice in useful and powerful ways. However I get the sense that there is insufficient in-depth technological understanding, and therefore insufficient details when it comes to defining the technical aspects of the projects. As such the scale and complexity of the projects may not have been adequately assessed. This could translate to missed opportunities.

Here are some more specific thoughts:

1. There was the mentioning of one project characteristics under examination being the cost of maintenance, which may not be a reliable measure from get-go.

   - A comment was made when discussing project 3, that due to COVID19 situation, recent data may not translate to prediction that is as reliable for baseline situations. This led to the mentioning of the cost of maintenance, whereby active maintenance is required for projects with dynamically changing backdrop, as opposed to more 'low cost' projects in which we can build a learning algorithm that continues to work. 

   - I would like to point out that the cost of software development and maintenance should not be underestimated, even for algorithms that we do not plan to continue to adjust; software is subjected to influence not only from the developers but also the whole software engineering community. For instance while I was consulting for a medical device company, the company had to actively keep track of Java updates and update their code frequently (for the same functions). In the MIT community there is also and often discussions about how to prevent biases in learning algorithms, which would require frequent checking and re-checking. So given the non-deterministic nature of most of the proposed projects, I think would be risky to dismiss ideas or select ideas based on the static nature of the problem in order to satisfy 'certain cost of maintenance'. Unless perhaps the products of the projects are meant to be short lived and the development phase or deployment phase would not be under the care of DSML. 

     

2. DSML hub members working with domain experts; or DSML members who are domain experts.

   - In most of the projects, under the slides on domain experts commitment. 





#### Project 1: Dr Phua Ghee Chee and Ken Goh

- Early prediction of critical illness in hospitalised patients
  - Early predictions and recognition of critical illness remains poor
  - Current state: clinical acumen, concerned staff, monitoring of vital signs (early warning scores), protocols, critical lab tests
  - Current response: rapid response teams and code blue teams
  - Potential for machine learning to integrate data from electronic

Impact on Patient Care

![Screenshot 2020-06-22 at 18.33.40](figures/Screenshot%202020-06-22%20at%2018.33.40.png)

**Outcome: Predictive model for critical illness in hospitalised patients**

![Screenshot 2020-06-22 at 18.34.45](figures/Screenshot%202020-06-22%20at%2018.34.45.png)

![Screenshot 2020-06-22 at 18.35.47](figures/Screenshot%202020-06-22%20at%2018.35.47.png)

![Screenshot 2020-06-22 at 18.36.19](figures/Screenshot%202020-06-22%20at%2018.36.19.png)

![Screenshot 2020-06-22 at 18.38.41](figures/Screenshot%202020-06-22%20at%2018.38.41.png)



![Screenshot 2020-06-22 at 18.39.12](figures/Screenshot%202020-06-22%20at%2018.39.12.png)

**New development in critical care:** 

Their data is intermittent, but we are starting to use wearables. Deploy container isolation wards. All patients will be fitted with continuous monitoring? IOT prevalent. COVID is driving wearable will become the normal worldwide. In isolation ward.

**Question**

- How would you define critical illness? Which particular critical illness?
  - Triage patient for ICU space?
  - Improve patient care we can reduce ICU enter
  - Code blue success rate data for past several years and rapid response - baseline data
    - ED to General Ward
  - Roll out the program in one ward
  - Admission issue that is coded for all patients. But it depends on the clerking doctor whether or not they fill up all the info. 
- What data is available? Why are we uniquely position to solve this illness?
  - Discrete data right now will eventually transit to continuous data
  - If the operation capability already here for 12 - 24 hours
  - From data ingestion process need to work with backend team; 
  - Desmond Chew Singhealth cannot do real-time right now but is working towards it.
    - So how does the wearable data communicate with the system?
  - No NPL required
  - Andrew is involved in data prediction and he is in the team.
    - Andrew is knowledgeable in data science

**Infrastructure**

- We need a way to easily pull data and activate predictor and then push the results to the interface

**Where we can maybe do better**

- Fluid plug in and extraction from the EHR / EMR
- Next 24 and 48 hours etc.

Very ambitious result. Mei Ling's department has early warning score system hospital one for traditional new score. This would help us capture baseline data. 

####  Project 2: Predicting Haemodialysis Centre Workload

Sheryl 



![Screenshot 2020-06-22 at 18.56.53](figures/Screenshot%202020-06-22%20at%2018.56.53.png)

![Screenshot 2020-06-22 at 18.58.51](figures/Screenshot%202020-06-22%20at%2018.58.51.png)



![Screenshot 2020-06-22 at 19.00.06](figures/Screenshot%202020-06-22%20at%2019.00.06.png)

![Screenshot 2020-06-22 at 19.02.15](figures/Screenshot%202020-06-22%20at%2019.02.15.png)

![Screenshot 2020-06-22 at 19.03.13](figures/Screenshot%202020-06-22%20at%2019.03.13.png)



These are all great visions.

- Each project can be thought of as a research program.
  - Project 1: 
    - Dimension to play with like different critical illness
    - Do we want to predict for different phases: pre ICU to within ICU deterioration etc. 
    - A good chance to do MDI
  - Project 2:
    - Scheduling system talking - a piping project
      - Automatic scheduling
    - Analysis of may data
    - Help with surge - the stochastic changes matters more
    - Help with surgical planning - long time line; seasonality matters

- Supply is relatively fixed

This is an operations research area - operations analytics team. 

**Question**

- How much in advance do you need to activate the surge plan?
  - There seems to be multiple time lines
    - Surgery - months in advance
    - Activate surge - short
  - Different level of precision is required and different types of data;
- Sounds like a multi-data source planning question?
  - Surgeons admitting for pre-op dialysis optimization
  - How much inpatient scheduled and how much not scheduled
- Not a static project
- Synergy between the two projects, if we can predict dialysis requirement, we might also consider renal failure is a critical illness
- Difference between these QI project, renal modelling and simulation



#### Project 3: Prediction of DIM patients with shorter length of stay for right-siting to AMW

Dr Kang Mei Ling

![Screenshot 2020-06-22 at 19.22.45](figures/Screenshot%202020-06-22%20at%2019.22.45.png)



- Pilot AMW in ward 73
- Improved length of stay for pneumonia without increasing re-admission rate
- Based on diagnosis alone, we cannot predict who is going to stay
  - The patient factor matters a lot too
  - Observe up to 50% of the patients admitted cannot go home. 

H9A - 168 new beds to admit the patients. 

- Prediction model of medical patients who will achieve LOS at the point of ED admission
- So they can be right sited into ADW
- Current is only general, ICU, observation
- Age, admission diagnostic code, 

Clinical score for LOS

- Dependent on clinical team / practice
- Will change with different practice

![Screenshot 2020-06-22 at 19.29.28](figures/Screenshot%202020-06-22%20at%2019.29.28.png)

![Screenshot 2020-06-22 at 19.31.16](figures/Screenshot%202020-06-22%20at%2019.31.16.png)

![Screenshot 2020-06-22 at 19.31.59](figures/Screenshot%202020-06-22%20at%2019.31.59.png)

23K to DIM, 80% of the DIM cases in the coming years in AMW.

**Idea: Admitting diagnosis vs. actual diagnosis**

- Machine assisted likelihood calculation in real time? Bayesian modelling? Go really evidence based?

**Question**

- Heterogenous is always a question - think about how to reduce heterogenous by reducing the scope
- If we trust the DSML approach, we should not need to start by reasoning what is reasonable.... If the collaborators love the reasoning, can they let go of control?
- If machine learning is going to help you understand where the patient is coming from: Interpretable AI.

**How to be different**

- Be a midline between mechanistic and the DSML to help generate hypothesis

- MDI is valuable and an important relationship to nurture - become the trusted FDA of Asia? Because FDA is too hard to get to.

- Synthesis of data from more than the hospital

  

Regional difference, patient data, CPF data etc might be available. But cross government agency may be challenging; But need API.

- Live data

Family medicine colleagues have done a study...

#### Project 4: ML for predicting patient glycemic control

Dr Amanda Lam

![Screenshot 2020-06-22 at 19.50.31](figures/Screenshot%202020-06-22%20at%2019.50.31.png)

- 10 - 20 patients a day for the worst of the worst
- Non-critically ill patients treated with insulin
- Classification and prediction **for 24 hours** - why 24 hours?

![Screenshot 2020-06-22 at 19.53.11](figures/Screenshot%202020-06-22%20at%2019.53.11.png)

![Screenshot 2020-06-22 at 19.53.56](figures/Screenshot%202020-06-22%20at%2019.53.56.png)



![Screenshot 2020-06-22 at 19.54.13](figures/Screenshot%202020-06-22%20at%2019.54.13.png)

![Screenshot 2020-06-22 at 19.54.48](figures/Screenshot%202020-06-22%20at%2019.54.48.png)

![Screenshot 2020-06-22 at 19.55.40](figures/Screenshot%202020-06-22%20at%2019.55.40.png)

![Screenshot 2020-06-22 at 19.56.19](figures/Screenshot%202020-06-22%20at%2019.56.19.png)



- Decision support for preemptive management of glucose



**Potential problems**

- Decision support is probably is going to be useful only from day 2 onwards
- Diagnosis codes are coded at the end of admission; and as free text
- Another project algorithm to predict the hypoglycemia



**Question**

- Prediction of blood sugar - average glucose



#### Project 5: Measuring the health impact of circuit breaker

Daniel Lim - good project

![Screenshot 2020-06-22 at 20.09.30](figures/Screenshot%202020-06-22%20at%2020.09.30.png)

![Screenshot 2020-06-22 at 20.11.56](figures/Screenshot%202020-06-22%20at%2020.11.56.png)

![Screenshot 2020-06-22 at 20.14.27](figures/Screenshot%202020-06-22%20at%2020.14.27.png)

- Would patient come late during COVID19?
- Could be interesting for respiratory conditions as well.
- Only Singapore has a closed population

![Screenshot 2020-06-22 at 20.17.42](figures/Screenshot%202020-06-22%20at%2020.17.42.png)

- If we know certain conditions are more vulnerable to circuit breaker we should go ahead and warn these patient
- Source data availability
  - ![Screenshot 2020-06-22 at 20.19.27](figures/Screenshot%202020-06-22%20at%2020.19.27.png)

- Domain

![Screenshot 2020-06-22 at 20.20.10](figures/Screenshot%202020-06-22%20at%2020.20.10.png)



**Learning**

- Use bayesian probability as an analogy

- Granular data will not be available at MOH level

- Think with the presenters, encourage before discourage

  

**Medical Device Integration (?)** 



## Setting Up

### People Involved

| People         | Institution | Role          |
| -------------- | ----------- | ------------- |
| Su Ying Low    | SGH         | Chair for CPI |
| Chan Cilburn   | Duke        |               |
| Chow Wan Cheng | SGH         |               |
| Phua GC        | SGH         |               |
| Ken Goh        | SGH         |               |
| Ryan Tan       | SGH         |               |
| Sheryl Gan     | SGH         |               |
| Kang ML        | SGH         |               |
| Tharma         | SGH         |               |
| Orlanda Goh    | SGH         |               |
| Amanda Lam     | SGH         |               |
| Hawa           | SGH         |               |
| Mei Kang       | SGH         |               |

- Ken Goh - duke student, currently IM doctor
- Daniel - IM resident, stopped to do a masters in data science, tech area queuing optimisation, masters in data analytics, continuing IM residency afterwards
- Amanda Lam - endocrinology, health informatics, AI project for diabetic complications, health informatics course
- Ratna Div Med - supportive staff
- Ryan Tan - associative consultants, breast and gynec cancer
- Sheryl - for director of inpatient dialysis patient center
- Tharmma Balakrishnan - 
- Ghee Chee Phua - critical care medicine; predictive analytics before during and after care; lung transplant
- Lynn - get stuff
- Xiaohui - small groups of colleagues for descriptive analytics work
- Jet Singhealth digital strategy office for insight and analytics
- Julian Thumboo from research office
- Affect the next central grant
- Hawa supporting coordinator, Executive under DIM from DIM under Lim
- Mei Lin Kang, SGH clinical department, finding a bed is a problem for him
- Cliburn - talk to chicken and talk to the duck
- Demond Chew - OIA data science team
- Orlanda Goh - SR, interest in HSR and what medics can do for it
- Raymond from organisation planing and performance
- Julian T - work with Xiao hui in health services research; 



#### Tan Mei Ling

- She is very looking forward to meeting me
- Coming zoom, we want to make people submit project and present and 10 minutes each
- After presented, we have a lady employed in the hospital to start the efforts
- The counter part of cliburn chan, technical expertise
- Technical administrative ability
- What are the people we want to employ and software and hardware we want to buy
- Who are more ready; projects with commonality can leverage on the same kind of technology and expertise; people we want employ the support the projects
  - 100% technical person
  - Regular meetings once a week
    - There is also the issue of the culture for such meetings
  - Many are pure clinicians
  - MSC data science
- Once a month the group can come together

Two ways

- Involve in the regular meetings to present to the projects
- In the process give inputs and share and contribute
- Or if there is one particular project we are particular 

Group digital officer

- Either involve in a project or participate in a regular meeting

#### Zhu Lin

- 

#### Chan Cilburn

- Parents here
- Immunology model; 
- Being a journey man, get my hands dirty, wouldn't commit that much time, maybe 10 hours a week. Then after speciality 3 - 4 years director; running the projects. 
- Operations team, deep knowledge of AI algorithms, statistical learning, control theory; 
- DSML expertise, own area looking after more translational and clinical applications; health services - research in the hospital; operations team reports to CEO that looks at operations; Kenneth Quek surgical robotics; separate units. 
  - Knowledge is fairly superficial.
  - Day to day stuff but no one with deep knowledge of the maths
  - Infrastructure for data - sing health level
  - Benedict tan and parts we don't want to deal with like governance and security; data mine SQL access; 
  - Priyanka, she runs team, not technical, building predictive model for out patient wait time; and incorporated. 
  - EHR; prescription information; financial data is collecting custom data; research data;
- KPI of DSML
  - Wan Cheng cares about **improving patient outcomes**
  - Whether or not can get new funding
  - Publications not a focus right now; eventually will want publications
  - Don't run a service shop; 
  - Bring value in, able to frame problems in ways that they can solve; Where problems are and link different fields together. 
  - Apply innovative things that is recently published; 50 research - 50 service; a team is very good, standard pipeline should be very good. 
- Value sleep too much
- Engineering - plumbers; 
- Liking not to do work if possible; 
- Immunology center: academic center
  - Postdoc molecular immunology lab
  - Modling immune system in PhD
- Greencard
- One things that has a lot going is a lot of **leadership buy-in**; Ben rans the digital operations at Singhealth level and Wan Cheng has to stay involved; Kenneth is also very involved; 
  - One of the office person, Jack
  - Singhealth as data science team; 
- Paid internship; I can be a quantitative mentors; 
- Just a **consultant** it is just DSML; something that needs to happen can make it happen
- Clinicians interested in data science but no deep background in maths; might be doing masters in data science and informatics; good for practical things but ultimately is limiting without knowing what's going on at the deep level;
- How to mesh people with different levels of training together in a team so they can solve **Wan Cheng's vision of AI for outcome**
- Ground up; proposals; deep knowledge and deep expertise will reside. 

SGH being the largest hospital has tons of data; CEO wants SGH to become an academic center; 



### How do we select and prioritize DSML projects?

**High level**

1. **Fit** - Will this lead to growth in an area that DSML values? 
   - What clinical domains will DSML build long-term collaborations in? 
   - What technical domains will DSML build expertise in?
   - These can evolve over time but need to be developed strategically

2. **Impact** – Will this add value to patients and the hospital?
   - Think of positive outcomes
   - Think of hurdles and challenges
   - Think of worst-case scenarios

3. **Feasibility** – Is there a reasonable likelihood of success at this point in time?
   - What data resources will the DSML build over time?
   - What software resources will the DSML build over time?
   - What computing resources will the DSML build over time?

#### **Is it a good fit for DSML?**

- What will DSML learn from doing this project whether it fails or succeeds?
  - Does the project offer learning opportunities that will result in DSML growth? 
- Is SGH a particularly good place for this project?
  - Are there data or samples that would be hard to get elsewhere?
  - Is there expertise that would be hard to find elsewhere?
- Is this project likely to lead to a long-term collaboration?
  - Is there scope for project extension?
  - Are there similar projects that we can apply learning from this project to?
  - Can we build local expertise for DSML in a specific clinical domain?

#### What is the potential impact?

- What would be the value if the project was a success?
  - What is the **data service or product** that would be generated?
  - What changes would there be to **patient outcomes**? 
    - days to readmission
    - ICU admission (yes/no)
    - time to death/discharge
  - What changes would there be to **baseline practices**?
  - What impact would it have for **hospital operations**?
  - What impact would it have for **hospital finances**?
- What would be the downside if the project had failures?
  - What would be the harm to the patients?
  - Are there measures that can be taken to limit damage?
  - What would be the harm to the hospital?
- Are there alternative ways to achieve this outcome?
  - Are there other hospitals that are doing this better?
  - Are there existing solutions (commercial or academic) that can be used or built on?

#### Is it feasible?

- Is data available?

  If data is unavailable, a corollary project is required to do data collection.

  - What data is needed?
  - How much work must be done to make the data useful?
    - Source data is available for predictor variables (source data can come from many sources - EHR, sensors and regular monitoring, lab results, imaging studies, genomics - each of which may need specialized expertise to process)
    - Labeled data for training is available (e.g. if asked to classify X-rays, we need a training set where a radiologist has provided diagnostic class)

- Is technical expertise available?

  - What skills are required beyond generic data science and machine learning?
  - Is effort available for a person with such skills

- Is domain expertise available?

  - What clinical expertise is needed for guidance and interpretation?
  - What level of time commitment is required from domain expert?
  - Does the domain expert have effort to spare for this project?

- Are computing resources adequate?

  - What software resources are needed?
  - What hardware resources are needed?

- How long will it take to complete the project?

  - Are there clear success and failure criteria?
  - How much uncertainty is involved?
  - Can the project be achieved incrementally by iterative prototype refinements?

### Initial Project Proposals

| Submitter                             | Input                                                        |
| ------------------------------------- | ------------------------------------------------------------ |
| Dr Phua GC, Dr Ken Goh                | Prediction of critical illness with machine learning using electronic health record data<br />**Prediction outcome:**<br />Either In-hospital death or ICU/ICA/HD admission (yes/no); Either In-hospital death or ICU/ICA/HD admission or requiring MICU/SICU triage note (yes/no) |
| Dr Ryan Tan                           | 1) Can we predict the **risk of progression to diabetes** in Singapore adults with normoglycaemia?<br />2) Can we better **predict the risk of developing breast cancer** with screening mammogram images compared to traditional clinical risk assessment models? |
| Dr Sheryl Gan                         | Predicting Inpatient Haemodialysis Demand<br /><br />Other potential topics:<br />Medical device integration (MDI) to predict the following:<br />**Hypotension on dialysis.** To then allow the nurses to call for assistance for alter the dialysis treatment to avoid the hypotension.<br />**Reduced circuit lifespan due to clotting.** Based on dialysis circuit parameters, we can predict when a HD circuit may clot. This would allow for the HD session to be terminated and before the entire circuit clots (avoid blood loss from this means)<br />MDI allows us to predict when a **HD machine requires earlier replacement** or review by the vendor. Currently this is manually collated and decided by the person collating.<br />Peritoneal dialysis workload prescription<br />Predictors of mortality and hospital admissions for the various renal sub-groups: peritoneal dialysis, harm-dialysis, acute kidney injury<br />Risk of ESRD in following populations: CKD, AKI |
| Dr Kang ML; Dr Tharma; Dr Orlanda Goh | Identification of patients presenting acutely at Emergency Department for admission into an acute medical ward |
| Dr Amanda Lam                         | Machine learning algorithms to predict inpatient glycemic control and guide insulin dosing decisions |

