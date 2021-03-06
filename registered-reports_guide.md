**NB: Please [contact the MSR RR track chairs](mailto:nernst@uvic.ca) with any questions, feedback, or requests for clarification. Specific analysis approaches mentioned below are intended as examples, not mandatory components.**

# Title (required)
Provide the working title of your study. It may be the same title that you submit for publication of your final manuscript, but it is not a requirement.

* **Example**: Should your family travel with you on the enterprise?
* Subtitle (optional): Effect of accompanying families on the work habits of crew members

# Authors (required)
At this stage, we believe that an unblinded/single blind review is most productive

# Structured Abstract (required)
The abstract should describe in 200 words or so:

## Background/Context
What is your research about? Why are you doing this research, why is it interesting?

**Example**: The enterprise is the flag ship of the federation, and it allows families to travel onboard. However, there are no studies that evaluate how this affects the crew members.”

## Objective/Aim
What exactly are you studying/investigating/evaluating? What are the objects of the study?

We welcome both confirmatory and exploratory types of studies.

**Example**: We evaluate whether the frequency of sick days, the work effectiveness and efficiency differ between science officers who bring their family with them, compared to science officers who are serving without their family.
**Example**: We investigate the problem of frequent Holodeck use on interpersonal relationships with an ethnographic study using participant observation, in order to derive specific hypotheses about Holodeck usage.

## Method
How are you addressing your objective? What data sources are you using.

**Example**: We conduct an observational study and use a between subject design. To analyze the data, we use a t test or Wilcoxon test, depending on the underlying distribution. Our data come computer monitoring of Enterprise crew members.

## Limitations

# Hypotheses / research questions (required)
Clearly state the research hypotheses that you want to test with your study, and a rationalization for the hypotheses. 

* **Example**: Science officers with their family on board have more sick days than science officers without their family

Rationale: Since toddlers are often sick, we can expect that crew members with their family onboard need to take sick days more often. 

# Introduction
Give more details on the bigger picture of your study and how it contributes to this bigger picture. An important component pf phase 1 review is assessing the importance and relevance of the study questions, so be sure to explain this. 

# Variables (required)
* Independent Variable(s) and their operationalization
* Dependent Variable(s) and their operationalization (e.g., time to solve a specified task)
* Confounding Variable(s) and how their effect will be controlled (e.g., species type (Vulcan, Human, Tribble) might be a confounding factor; we control for it by separating our sample additionally into Human/Non-Human and using an ANOVA (normal distribution) or Friedman (non-normal distribution) to distill its effect).

For each variable, you should give:
- name (e.g., presence of family)
- abbreviation (if you intend to use one)
- description (whether the family of the crew members travels on board)
- scale type (nominal: either the family is present or not)
- operationalization (crew members without family on board vs. crew members with family onboard)

# Material/objects (required)
Describe any material that you plan to use, be specific on whether you developed it (and how) or whether it is already defined (e.g., a standard myers-briggs-type indicator)

**Example**: For sick days, we recruit the medical records from sick bay (ethics approval pending). For efficiency, we conduct standard interviews with the superior officer and crew members. The questions are the following: / can be found on the Web site / Appendix. Furthermore, we observe their performance during a simulated task.

# Tasks (optional)
If you use tasks, describe them, how they were designed or from where they are taken and why they are suitable to evaluate the hypotheses / research question

**Example**: For effectiveness of the crew members, we ask them to sweep a class 2 nebula. We simulate an error in the primary sensory array. Crew members should then run a level 3 diagnostic to spot the error, fix the error, and complete the sweep of the nebular. We measure the time to (i) spot that there is an error, (ii) decide on the correct diagnostic protocol, (iii) fix the error, and (iv) complete the sweep.

# Participants/Subjects/sample (required)
Describe how and why you select the sample. When you conduct a meta analysis, describe the primary studies / work on which you base your meta analysis.

**Example**: We recruit crew members from the science department on a voluntary basis. They are our targeted population. 

# Execution Plan (required)
Describe the experimental protocol.

**Example**: Each crew member needs to sign the informed consent and agreement to process their data according to GDPR. Then, we conduct the interviews. Afterwards, participants need to complete the simulated task. 

# Analysis Plan (required)
## Descriptive statistics
How do you describe the data? How do you handle outliers?

Example: To represent the number of sickdays, we use histograms. Dependending on the distribution, we remove values that are 2 standard deviations above the mean as outliers (normal distribution). If the data are non-normal, we use the median and values below the 10th/above the 90th percentile.

## How do you evaluate the practical significance of the hypotheses?
How are you testing the significance of your results? Be specific about the epistemological paradigm and statistical paradigm you are using. This will help us assign reviewers familiar with the relevant research strategies. See [Neto et al.](https://arxiv.org/pdf/1706.00933.pdf) for more information.

* **Example**: (Frequentist) To test for normality, we use a Shapiro-Wilk test. For efficiency, we use a t test / Wilcoxon test depending on the distribution. To evaluate the effect of species type, we use a two-way ANOVA / Friedman test, depending on the distribution.
* **Example**: (Bayesian) We derive a posterior predictive distribution by choosing a weakly informative prior with sickdays modeled using a Poisson distribution, and likelihood of species influence modeled using a normal distribution with mean 0 and s.d. \sigma. We then calculate the 95% and 99% uncertainty intervals and median m and mean μ of the posterior.

# Examples
* Final studies (phase 1 and 2) are available at [this Zotero page](https://www.zotero.org/groups/479248/osf/items/collectionKey/KEJP68G9?) 
* Example phase 1 registrations can be found at [OSF Registry](https://osf.io/registries/discover?provider=OSF&type=OSF%20Preregistration)
* A sample phase 1 registration is [a study of tax in economics](https://osf.io/5g7hv/)
