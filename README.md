# STA-303-Final-Project
This repo contains the data and output on the topic of gender parity in hiring, wages and promotion based on hiring and employee data.


# Table of Contents
* [Hiring Phase](#Hiring_Phase)
* [Current Employee](#Current_Employee)

## Hirng Phase

### Phase 1
applicant_id: A unique ID assigned to applicants in Phase 1

team_applied_for: Software or Data

cover_letter: 0 if absent, 1 if present

cv: 0 if absent, 1 if present

gender: ‘Man’, ‘Woman’, ‘Prefer not to say’ only options provided

extracurriculars: The description of extracurricular involement is assessed against a
proprietary key term and phrase bank and given a 0, 1 or 2 for where
2 indicates several high relevenace and/or skills building
extracurriculars, 1 indicates some relevant and/or skills building
extracurriculars and 0 indicates no extracurriculars describes or that
those describe were not rated as high relevance or high skills building

work_experience: Similar to extracurriculars, the description applicants provided is
assessed against a proprietary key term and phrase bank, that also
consideres company names and reputations, to give a 0, 1 or 2 score,
with 2 being the best, 0 the worst

### Phase 2
applicant_id: A unique ID assigned to applicants in Phase 1

technical_skills: Score from 0 to 100 on a timed technical task, AI autograded

writing_skills: Score from 0 to 100 on a timed writing task, AI autograded

speaking_skills: A rating of speaking ability based on pre-recorded video, AI
autograded

leadership_presence: A rating of ‘leadership presence’ based on pre-recorded video, AI
autograded

### Phase 3
applicant_id: A unique ID assigned to applicants in Phase 1
interviewer_rating_1: The overall rating of job fit given by thefirst interviewer on a scale of
0 to 100
interviewer_rating_2: The overall rating of job fit given by the second interviewer on a scale
of 0 to 100

### Final hires
applicant_id: A unique ID assigned to applicants in Phase 1

## Current Employee
* [Promotion](#Promotion)
* [Salary](#Salary)


