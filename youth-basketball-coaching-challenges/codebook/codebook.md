# Youth Basketball Challenges — Variable Codebook

**Appendix B — Codebook**

This codebook documents all variables used in the Youth Basketball Challenges survey, including variable names, measurement levels, question type (demographic vs. research), and value labels.

---

## Identification

| Variable | Description |
|---|---|
| `ID` | Unique respondent identifier |

---

## Demographic Variables

### GENDER
- **Type:** Nominal, demographic
- **Question:** What is your Gender?
- `1` = Female
- `2` = Male
- `3` = Other

---

### AGE
- **Type:** Interval, demographic
- **Question:** What is your age?
- *(Open-ended numeric response)*
- *Note: Recoded into two groups — under 40 years old (0) and 41 years and older (1)*

---

### RACE
- **Type:** Nominal, demographic
- **Question:** What racial or ethnic group do you identify with? (Circle all that apply)
- `1` = Asian or Pacific Islander
- `2` = Black
- `3` = White, non-Hispanic
- `4` = Hispanic
- `5` = Native American
- `6` = Other

---

### CHILDREN
- **Type:** Interval, research
- **Question:** How many children do you have?
- *(Open-ended numeric response)*

---

### COACH_CHILDREN
- **Type:** Nominal, demographic
- **Question:** Do you coach your own child(ren)?
- `1` = Yes
- `2` = No
- `3` = Have no children

---

### RESIDENCY
- **Type:** Nominal, demographic
- **Question:** What area of Santa Clarita do you live in?
- `1` = Canyon Country
- `2` = Newhall
- `3` = Saugus
- `4` = Valencia
- `5` = Stevenson Ranch
- `6` = Other (specify)

---

### EDUCATION
- **Type:** Nominal, demographic
- **Question:** What is the highest degree or level of education you have completed?
- `1` = Less than high school
- `2` = High school graduate (includes equivalency)
- `3` = Some college, no degree
- `4` = Associate's degree
- `5` = Bachelor's degree
- `6` = Ph.D.
- `7` = Graduate or professional degree

---

### INCOME
- **Type:** Ordinal, demographic
- **Question:** What is your income?
- `1` = Under $30,000
- `2` = $30,001–$55,000
- `3` = $55,001–$75,000
- `4` = $75,001–$100,000
- `5` = $100,001 and over
- *Note: Recoded into two groups — under $75,000 (0) and over $75,001 (1)*

---

### MARITAL_STATUS
- **Type:** Nominal, demographic
- **Question:** What is your marital status?
- `1` = Single
- `2` = Married
- `3` = Divorced
- `4` = Widowed
- `5` = Other

---

### EMPLOYMENT
- **Type:** Nominal, demographic
- **Question:** What is your work status?
- `1` = One or more full-time jobs (at least 32 hours a week each)
- `2` = Two part-time jobs
- `3` = One part-time job
- `4` = Self-employed
- `5` = Retired
- `6` = Student
- `7` = Unable to work due to medical condition
- `8` = Not currently looking to work
- `9` = Currently looking for work
- `10` = Other

---

### OCCUPATION
- **Type:** Nominal, open-ended
- **Question:** What is your occupation?

---

### NEGATIVE_EXPERIENCE
- **Type:** Nominal, dichotomous, demographic
- **Question:** Have you ever had a negative experience coaching basketball?
- `0` = Yes
- `1` = No

---

## Research Variables

### HOURS_COACH
- **Type:** Interval, research
- **Question:** How many hours do you invest in coaching every week?
- *(Open-ended numeric response)*

---

### COACH_CHALLENGES
- **Type:** Nominal, research
- **Question:** What is the biggest challenge for you as a youth basketball coach?
- `1` = Time Commitment
- `2` = Referees
- `3` = Sports organization
- `4` = Parents
- `5` = Players
- `6` = Own child(ren)
- `7` = Home/Life
- `8` = Spouse
- `9` = Job/Coach balance
- `10` = Family commitment
- `11` = Other

---

## Outside Influence Susceptibility Scale

*Six Likert-scale items measuring susceptibility to pressure from parents, players, and the crowd.*
**Scoring:** 5 = Strongly Disagree, 4 = Disagree, 3 = Neutral, 2 = Agree, 1 = Strongly Agree
*(Higher scores indicate lower susceptibility to outside influence)*
**Scale Range:** 6–30 | **Cronbach's α = .767** | **Mean = 24.26**

| Variable Name | Description | Type |
|---|---|---|
| `UNSEEN_PLAYER` | Unseen player reaction — coach yells at referee on player's behalf without seeing the play | Ordinal (Likert, treated as interval) |
| `PARENT_PLAYTIME` | Overbearing parent — coach adjusts playing time to avoid parent confrontation | Ordinal (Likert, treated as interval) |
| `SELFISH_PLAYER` | Selfish player — coach adjusts play design to accommodate player preference | Ordinal (Likert, treated as interval) |
| `CENTER_PG` | Center/PG conflict — coach changes player position to please parents | Ordinal (Likert, treated as interval) |
| `BENCH_SUB` | Bench sub — coach responds to crowd chanting by inserting a player | Ordinal (Likert, treated as interval) |
| `FREE_THROW_SUB` | Free throw sub — coach responds to player's substitution request | Ordinal (Likert, treated as interval) |

---

## Challenges Scale

*Ten interval-level items measuring the perceived difficulty of each challenge factor.*
**Scoring:** 0 (no issue) to 10 (highest issue) per item; combined score range 0–100
**Cronbach's α = .846** | **Mean = 38.76** | **SD = 20.54**
*Recoded: 0 = score ≤ 38 (at or below mean); 1 = score ≥ 39 (above mean)*

| Variable Name | Description | Type |
|---|---|---|
| `TIMECOMMIT` | Time Commitment | Interval, research |
| `REFS` | Referees | Interval, research |
| `ORGANIZATION` | Sports organization | Interval, research |
| `PARENTS` | Parents | Interval, research |
| `PLAYERS` | Players | Interval, research |
| `CHILD` | Own child(ren) | Interval, research |
| `HOMELIFE` | Home/Life | Interval, research |
| `SPOUSE` | Spouse | Interval, research |
| `JOBBALANCE` | Job/Coach balance | Interval, research |
| `FAMCOMMIT` | Family commitment | Interval, research |

---

*Thank you for taking the time to fill out this survey. Your answers will help improve the quality of youth sports programs.*
