# DSML Notes

## Setting Up

### People Involved

| People         | Institution | Role          |
| -------------- | ----------- | ------------- |
| Su Ying Low    | SGH         | Chair for CPI |
| Chan Cilburn   | Duke        |               |
| Chow Wan Cheng |             |               |
| Phua GC        |             |               |
| Ken Goh        |             |               |
| Ryan Tan       |             |               |
| Sheryl Gan     |             |               |
| Kang ML        |             |               |
| Tharma         |             |               |
| Orlanda Goh    |             |               |
| Amanda Lam     |             |               |

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

