# An N-of-1, reproducible, semantic randomized controlled trial comparing an online, personalized storytelling educational intervention vs control for social skills improvement


Graziela Nogueira  
João Ricardo Vissoci  
Bruno Melo  
Ricardo Pietrobon  

## Abstract
<!-- write at the end -->

## Introduction

Provider social skills in healthcare has been previously associated with increased patient satisfaction as well as improved patient outcomes. <!-- ref --> While an extensive number of both in person and online training methods have been applied to social skills training, results vary widely depending on the match between the content and the individual needs of the learner. To our knowledge, however, no previous studies have evaluated the efficacy of a scalable, personalized approach method in providing online training to healthcare professionals.


* lit review on social skils training efficacy (randomized trials) and effectiveness (observational) in healthcare
* lit review online learning social skills

The objective of this educational, reproducible, online parallel randomized trial is therefore to compare the use of the stakeholder enactment method versus a control training method focused on social skills, among a group of healthcare professionals and students. We measured its effect on knowledge, clinical impact and satisfaction. We hypothesized that, compared to control, the "stakeholder enactment arm" would result in increased knowledge, clinical impact and provider satisfaction with the learning experience.


## Methods

This trial was designed and reported in accordance with the recommendations provided by the [CONSORT statement, version 2010](http://www.consort-statement.org/)

### Ethics
This study was approved by the Ethics Committe at the University of São Paulo ([Universidade de São Paulo](http://www5.usp.br/en/)), informed consent having been waived since this was considered a research with minimal risk within an educational context. All participants were ensured that their involvement with the trial was absolutely unrelated to their performance in their current work or study and that they could exit the study at any point if they so desired.

### Trial Design

This is a parallel, reproducible, controlled randomized trial comparing a control versus a scalable coaching arm. The trial involved 106 participants who completed the trial <!-- replace by the actual number and describe dropout rate -->, randomized on a 1:1 ratio to the intervention and control arms, with the intervention and respective follow-up lasting a total of four weeks. No changes to the initially methods design were implemented while the trial was in course. <!-- need to check at the end whether this is true -->

### Participants
Our study involved 106 participants. Participants were health care providers or students at <!-- add -->, located in the metropolitan area of São Paulo. For each participant we have collected information on gender, age, profession and previous educational background.

### Interventions


#### Scalable coaching
The scalable coaching arm used as its main principle the stakeholder enactment theory <!-- ref arxiv-->, which contains elements from both role play educationaal methods <!-- ref --> as well as Merrienboer's Complex Learning Instructional Design  ([Merrienboer, 2012](http://www.amazon.com/Steps-Complex-Learning-Four-Component-Instructional-ebook/dp/B009WMBP7O/ref=sr_1_1?ie=UTF8&qid=1401304465&sr=8-1&keywords=merrienboer+complex)) . Briefly, in week one participants were exposed to videos first briefly describing all four main process skills advocated by motivational interviewing experts, namely, engaging, focusing, evoking and planning. Then, still during the first week, participants were exposed to a video with a fictitious cases where they had to use these same skills at a very simple level. Subsequent weeks increased the complexity level of the cases, but remained providing participants with cases where all four skills were required, thus mimicking a real clinical situation.

<!-- add details about intervention after we run some initial tests -->


#### Control arm
The control arm was provided with weekly texts for subjects to read regarding four construct regarding motivational interviewing. These texts focused on a set of skills related to social skills, namely <!-- add -->. <!-- list texts -->

#### Educational material reproducibility
All educational material for this course is available within our Reproducible Research repositories, and delivered through the original [Open edX platform](http://code.edx.org/). Videos were provided in Brazilian Portuguese. All remaining material was made available in Portuguese, although both Italian and English versions are provided within our Reproducible Research repositories (see subsequent section on Reproducible Research).


<!-- add CONSORT for Non-Pharmacological Treatment Interventions -->

### Outcome variables

<!-- 

merrienboer whole tasks 

Outcome:
    -   Persuasion of instructor.
Student Satisfaction.
Improve knowledge in Positive Psychology.
Improve clinical use of Positive Psychology Techniques.

Scales: Questions (5-point scale or 7-point scale).

Beginning of the class (use in sessions 2 to 4): How of the knowledge gained in last class did in your clinical practice? 

End of the classe”s
Persuasion http://casaa.unm.edu/download/miti3_1.pdf

Overall how effective was the instructor?
Overall how worthwhile was the course?
Overall how much did you learn?

 -->

Our study had three main categories of outcome variables: Knowledge, User eXperience (UX) and impact on clinical practice, all described under the subsequent sections. Per CONSORT Statement guidelines, any eventual changes to outcome measures deviating from the initial plan and occurring throughout the trial were recorded in our versioning system ([Github](https://github.com/)), thus ensuring full reproducibility. However, changes were avoided unless strictly necessary.

##### Knowledge


Knowledge was measured through a group of questions (items) under four main process domains, namely: <!-- add -->.

Given that there are no standardized scales to measure knowledge within each of these domain areas, we conducted a parallel validation using a combination of Classical Psychometric Theory and Item Response Theory.

An item (question) pool was initially created, covering all <!--  number --> domains, ultimately constituting items sets with 30 items (questions) each, for a total of <!--  number--> items (questions). 

A randomly selected subset of this item pool of {{}} items was exposed to the participants in our trial, using an anchoring approach for linked scales where each set contains a constant group of items that is repeated in every set, thus ensuring that all sets were connected. Subsequently, a sequence of exploratory and confirmatory factor analyses, reliability evaluation within each individual construct, and validity triangulating across different items was used to achieve a psychometrically valid summed construct-specific and overall scores to serve as the variables representing the knowledge outcome of our trial. Details about each of these analyses are presented within the Data Analysis section.

Knowledge evaluation occurred at baseline and then at the end of weeks two and four. These assessments were automatically recorded within the edX Code platform under two databases ([MySQL](http://www.mysql.com/) for participant information and [MongoDB](https://www.mongodb.org/) for exercise information), both with a common unique identification number.

##### User eXperience

In this study we primarily measured User eXperience (UX) as participant satisfaction while participating in one of the two interventions. While the literature on the measurement of satisfaction within online education is vast, (see @banks2007reduction, @dibiase2005scaling and @ summers2005comparison for a few examples)  <!-- see http://www.westga.edu/~distance/ojdla/Fall133/sampson_ballenger133.html (Banks & Faul, 2007; Debourgh, 1998; Dibiase & Rademacher, 2005; Enockson, 1997; Heiman, 2008; McCabe, 1997; Summers, Waigandt, & Whittaker, 2005; Walker & Kelly, 2007). Several other studies focused on student and teacher interactions and perceptions of learning (Heiman, 2008; Rovai & Barnum, 2003); and social presence (Richardson & Swan, 2003) as part of students’ satisfaction. --> we have elected to use the scale developed by [Kuo et cols](http://www.irrodl.org/index.php/irrodl/article/view/1338/2416) since it is not only comprehensive but has also been shown to be psychometrically valid. The Sampson scale covers seven satisfaction sub-constructs, namely satisfaction with learner-learner interaction, learner-instructor interaction, learner-content interaction and overall satisfaction. Cronbach's alpha reliability was found to be above 0.88 for all subscales, the Kuo scale also having been validated against student self-efficacy. 

Satisfaction was assessed at the end of weeks two and four using a set of questionnaires provided within the Open edX platform. These assessments are automatically recorded within the platform.

##### Impact on clinical practice

The last evaluated construct was the impact on clinical practice. Given that, to our knowledge, no previously validated scale has been devised to measure the impact of online learning on clinical practice, we have also devised a concomitant validation strategy. 

Impact on clinical practice was measured through a group of questions (items) under one single domain (unidimensional scale). The item (question) focused on "How much has the knowledge you gained in this course has positively or negatively influenced your clinical practice, where 0 means no influence at all and 10 means an extremely influence." . A five-point Likert alternative pattern then covered the spectrum of positive or negative influence.

This group of items was exposed to the participants in our trial. Similar to the knowledge domain, a sequence of exploratory and confirmatory factor analyses, reliability evaluation within each individual construct, and validity triangulating across different items was used to achieve a psychometrically valid summed score serving as the outcome measuring impact on clinical practice for our trial. Further details on how each of these analyses was conducted are presented within the Data Analysis section.

Knowledge evaluation occurred at the end of weeks two and four. These assessments are also automatically recorded within the platform.



####  Sample size

Given the absence of preliminary efficacy data, we calculated our sample size based on an assumption of a two-sample t-test for an index representing the worst case scenario for each of the three outcome variables, with an effect size of 55%, a significance level and statistical power set at the traditional levels of 0.05 and 80%, respectively. Under these assumptions the estimated required sample size is of 52.9 per group, which we have rounded to 53, ultimately leading to a total sample size of 106 participants in total. Taking into account a worst case scenario dropout rate of approximately 20%, we therefore plan to enroll 140 participants.


####  Interim analyses and stopping guidelines

Given the relatively short duration of our trial, we did not perform an interim analysis. In addition, given the low risk associated with the intervention, our guidelines did recommend that the trial be stopped in case of an unlikely loss of confidentiality that might compromise participants privacy, which has not occurred.

####  Randomization: sequence generation

All randomization schedules were delivered through [Planout](http://facebook.github.io/planout/) within the [edx Code](http://code.edx.org/) platform. Briefly, Planout makes use of a pseudorandom number generator from the [Python language](https://www.python.org/), which has been extensively tested. <!-- need ref --> Randomization was blocked at 10 participants, thus decreasing the likelihood of a possible imbalance.  

All randomization was delivered through the Open edX platform, thus ensuring that participants and investigators are blind to the allocation. Data analysts (RP and JRV) received a dataset from the computer scientist (BM) where the two randomization arms were designated by unspecific letters, thus ensuring that the analysis was also conducted in a blinded fashion.


#### Statistical methods 

All analyses were conducted by members in our team (RP, JRV). The data analysis started with an overall evaluation of individual variables to assess distributions for continuous variables (e.g., participant's age) in terms of their distributions, as well as the frequency/percentage for categorical variables (e.g., gender). 

Missing values were handled differently if they happened to individual variables or full encounters, e.g., an entire evaluation for a week. Individual variables were imputed starting by an exploratory visual analysis to better understand the potential underlying pattern behind missing values for each variable. This analysis was conducted using the [VIM package](http://cran.r-project.org/web/packages/VIMGUI/vignettes/VIM-Imputation.pdf) within the [R language](http://www.r-project.org/). Depending on the pattern of missing data, we might then choose one of several alternatives, ranging from not imputing when the percent missing might be negligible, imputing using predictive models from variables that are hypothesized to be associated with the missing values (e.g., age predicting residency year), or multiple imputation in cases where missing patterns might be happening at random (MAR or missing at random) (@rubin1976inference). <!-- see 3d grant -->

We evaluated for potential confounding of the intervention effect by assessing balance across baseline variables between the scalable coaching and control arms. This evaluation occurred for the overall study. While imbalances were unlikely given that we are using a series of preventive measures (blinding, concealed allocation, blocking and stratification), eventual imbalances were evaluated on an individual basis and required adjusting in our modeling strategy (see below for details).

The psychometric analysis for parallel validation of our scales started with an Exploratory Factor Analysis to evaluate the underlying dimensional structure of our item pool. We then conducted a Confirmatory Factor Analysis using the hypothesized domains (see Outcome Variable section for extensive details). Once domains were established, we used Cronbach's alpha to measure internal reliability within each construct. Validity was measured by triangulation across different domains. 

Given that all of our outcomes have multiple endpoints over time, we used a combination of mixed models and survival analysis to measure the efficacy associated with the "better half toolkit" in comparison with the control arm. To formally test trends in each of our outcome variables over time we developed mixed models that account for multiple measures as random a effect. For each time period we also assessed differences in scores. These bivariate analyses incorporated robust standard errors to account for the clustering effect.


### Reproducible research
In order to follow a reproducible research protocol, we have written our final manuscript using [Rmarkdown](http://www.rstudio.com/ide/docs/authoring/using_markdown), which combines the R language with the [Markdown markup](http://daringfireball.net/projects/markdown/), ultimately allowing us to leave all calculations and data manipulation within the article text. All data sets and respective analytical scripts were provided in CSV (comma separated value) formats in open public repositories including [Figshare](http://figshare.com/) and [Github](https://github.com/). In addition, we have also stored the version of the software used in this analysis and deposited it within our Github and Figshare repositories, ultimately decreasing the probability of reproducibility issues during subsequent attempts to reproduce our analyses. <!-- add paper that recommends this procedure -->

## Results

<!-- add this section in alignment with CENT -->

## Discussion





<!-- 

See: The Effectiveness and Applicability of Motivational Interviewing: A Practice-Friendly Review of Four Meta-Analyses. Brad Lundahl and Brian L. Burke.

See: Client Resistance as Predicted by Therapist Behavior: A Study of Sequential Dependence. Mary M. Bischoff and Terence J. G. Tracey

Intervention:
4-session program using clinical-focused techniques (such as the ,“mind scan” technique, “fly on the wall” technique, clinical cases, practitioner points) and “advanced presentation mode”. 
Each one around (30 minutes?) One-week minimum between each session? 1 or 2 branches?

Personalization, empathy, evocar coisas positivas e daí ancorar pra modificar comportamento (Rogers motivational interviewing) - http://en.wikipedia.org/wiki/Motivational_interviewing 

Session 1: Basic Introduction to Motivational Interviewing.
Session 2: Common errors (during “wrong interviewing” we ask questions – ‘fly on the wall’ - and we present common private thoughts – ‘mind scan’ and reactions of patients).
Session 3:  How to use Motivational Interviewing (during “right interviewing” we ask questions – ‘fly on the wall’ - and we present common private thoughts – ‘mind scan’ and reactions of patients).
Session 4: Evaluation of techniques and closure.

Control: standard presentation (slides and 2D figures).





1) Não focar o curso de Entrevista Motivacional apenas em problemas psiquiátricos mas em problemas significativos de saúde pública e com alta prevalência. Por exemplo, não dar exemplos específicos de psiquiatria  (p.e Gambling, Anorexia, etc) mas focar os exemplos em TABAGISMO, ALCOOLISMO, EXERCÍCIO FÍSICO E QUEM SABE ATÉ ALGUM EXEMPLO CLÍNICO COMO HIPERTENSÃO. 
2) Isso permitiria que nosso publico alvo ampliasse de mental health professionals para health professionals (incluindo general practicioners, nurses, students, etc...). O que tb facilita o recrutamento: primeiro porque aumenta o publico, segundo porque ele tem contato com a parte de saude primária da prefeitura onde ele pode divulgar nosso curso.




 -->