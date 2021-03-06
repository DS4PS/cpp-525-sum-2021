---
layout: schedule
title: Schedule

canvas: 
  assignment_url: 'https://canvas.asu.edu/courses/41574/assignments'
  
---
 
<!--- 
New sections start with 2 stars:  ** Section Title
New units start with 3 stars:     *** {Unit Metadata}
-----------------------------start example
** Section-I
*** { @unit = "15th Nov", @title = "Course Overview", @reading, @lecture, @assignment, @foldout }
-----------------------------end example
Unit Metadata is comprised of:
@unit - date or number
@title - unit name
@reading - turn on reading icon
@assignment - turn on lecture icon
@lecture - turn on lecture icon
@foldout - activate unit content (allow foldout)
Submit Button - <a class="uk-button uk-button-primary" href="{{page.canvas.assignment_url}}">SUBMIT LAB</a>
-->








** Welcome


*** { @unit = "", @title = "Overview of Causal Analysis with Observational Data", @reading, @foldout }

<br>
<br>

## Evidence-Based Practices 

![](https://physics.aps.org/assets/73b0590c-2226-44f6-852a-fa23e6ef3b76/e86_2.png) 

What does it mean to live in an evidence-based world? How do we become more data-driven? 

It turns out that using data to improve decision-making and organizatoinal performance is not a trivial affair because of a little problem called omitted variable bias (correlation does not equal causation). As a result, we need to combine judicious analytical techniques with feasible approaches to research design in order to understand **causal impact** of social programs. 

Here is a great introduction to a case study that uses evaluation to better understant the impact of a government program by getting past anecdotes to measure program impact.

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/N8rD844McrA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>
<br>


## Understanding Causal Impact Without Randomized Control Trials

In most cases we don't have resources for large-scale Randomized Control Studies. They typically cost millions of dollars, are sometime unethical, and are often times not feasible. For example, does free trade prevent war? How do you randomized free trade across countries?

Statistics and econometricians have spent 75 years developing powerful regression tools that can be used with observational data and clever quasi-experimental research designs to tease out program impact when RCT's are not possible. The courses in the Foundations of Program Evaluation sequence build the tools to deploy these methods.

* Foundations of Eval I covers the mechanics of regression.
* Foundations of Eval II covers counterfactual analysis and quasi-experimental approaches to research design. 
* Foundations of Eval III covers seven regression models used in causal analysis (for example, [interrupted time series](https://ds4ps.org/PROG-EVAL-III/TimeSeries.html)).

Let's start with a simple example. Is caffeine good for you? 

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/2TRcFpytYT8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br> 

What evidence is used to create these assertions? [ [link](https://www.hsph.harvard.edu/news/hsph-in-the-news/coffee-depression-women-ascherio-lucas/) ]

Can you conduct a Randomized Control Trial to study the effects of caffeine on mental health over a long period of time? This would require us to demand that some individuals that enjoy coffee not consume it over long periods of time (several months if studying depression, several years if studying things like heart health, diabetes, or cancer), and you force people that don't like coffee to drink it on a daily basis for years. 

As you might expected, an RCT would be challenging. As a result most of our evidence comes from long-term observational studies where participants self-report daily coffee consumption, and these are physical health is measured through regular physician check-ups and self-reported health measures. For example, one of the most important public health studies began in 1976 with a sample of 121,000 nurses and has followed the cohort over 50 years [see the [Nurses' Health Study](https://en.wikipedia.org/wiki/Nurses%27_Health_Study)]. Does evidence from this study represent correlation or causation?  

How can we be sure we are measuring the causal impact of coffee on health? 

<br>

### Why is evidence-based management hard?

Just listen to this summary of current knowledge on the topic, then try to succinctly translate it to a rule of thumb physicians should use on whether to recommend coffee to patients. 

<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/OvDuBVBoV3Q" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>
<br>



*** { @unit = "", @title = "Estimating Program Impact", @reading, @foldout  }


<br>
<br>

![](https://image.shutterstock.com/image-vector/banner-evaluation-concept-assessment-analysis-260nw-1339409468.jpg)

<br>

## Program Impact 

This course provides foundational skills in quantitative program evaluation:

**Reichardt, C. S., & Bormann, C. A. (1994). Using regression models to estimate program effects. Handbook of practical program evaluation, 417-455.** [__[pdf](https://github.com/DS4PS/cpp-523-spr-2020/raw/master/pubs/Estimating%20Program%20Effects%20Using%20Regression%20Models.pdf)__]

**Gertler, P. J., Martinez, S., Premand, P., Rawlings, L. B., & Vermeersch, C. M. (2016). Impact evaluation in practice. The World Bank.** [[pdf](https://siteresources.worldbank.org/EXTHDOFFICE/Resources/5485726-1295455628620/Impact_Evaluation_in_Practice.pdf)]
* Chapter 3. Causal Inference and Counterfactuals 
* Chapter 4. Randomized Selection Methods  

## The Broader Field of Evaluation 

Program evaluation is a large field that deploys a diversity of methodologies beyond quantitative modeling and impact analysis. We focus heavily on the quantitative skills in the Foundations of Eval I, II, and III in this program because data is hard to use, so you need several courses to build a skill set. Qualitative and case-study approaches build from the same foundations in research design, so you can more fully develop some of those skills drawing from knowledge of formal modeling and inference.

For some useful context on evaluation as a field, this short (6-page overview) is helpful:

**McNamara, C. (2008). Basic guide to program evaluation. Free Management Library. [__[pdf](https://github.com/DS4PS/cpp-523-spr-2020/raw/master/pubs/A-Basic-Guide-to-Program-Evaluation.pdf)__]**

And to get a flavor for debates around approaches to measuring program impact in evaluation:

**White, H. (2010). A contribution to current debates in impact evaluation. Evaluation, 16(2), 153-164. [__[pdf](https://github.com/DS4PS/cpp-523-spr-2020/raw/master/pubs/Reflections-on-Impact-Evaluation-White.pdf)__]**


<br>
<br>




*** { @unit = "", @title = "Varieties of the Counterfactual", @reading, @foldout }

## Description 

This week introduces the notion of counterfactual reasoning using quasi-experimental design. 

## Learning Objectives

* Be able to define and explain what is meant by "counterfactual reasoning" broadly. 
* Explain the three primary counterfactuals in all statistics models. 
* Apply the appropriate tests to determine whether the counterfactual is appropriate and robust. 

## Lecture Materials

* [**Introduction to Counterfactuals**](https://github.com/DS4PS/cpp-524-spr-2020/raw/master/lectures/p-01-intro-to-counterfactuals.pdf)

* [**Testing the Counterfactual Validity**](https://github.com/DS4PS/cpp-524-spr-2020/raw/master/lectures/p-02-tests-for-cf-validity.pdf)

  - Pre-study equivalence 
  - Tests for non-random attrition 


* [**Varieties of the Counterfactual**](https://github.com/DS4PS/cpp-524-spr-2020/raw/master/lectures/p-03-varieties-of-counterfactuals.pdf)

  - Pre-post with comparison group design 
    - difference-in-difference model  
  - Post-test only design 
  - Reflexive design 


## Assigned and Recommended Articles or Chapters

**Required:**

Cook, T. D., Scriven, M., Coryn, C. L., & Evergreen, S. D. (2010). Contemporary thinking about causation in evaluation: A dialogue with Tom Cook and Michael Scriven. American Journal of Evaluation, 31(1), 105-117. [ [LINK](https://github.com/DS4PS/cpp-524-spr-2020/raw/master/pubs/conversation-with-tom-cook-and-michael-scriven.pdf) ]

**Suggested:**

Skim: Gertler, P. J., Martinez, S., Premand, P., Rawlings, L. B., & Vermeersch, C. M. (2016). *Impact evaluation in practice.* The World Bank.  
* CH5 Regression Discontinuity Design   
* CH6 Difference in Difference Models   
* CH7 Matching   



## Key Take-Aways 

We rarely have the resources or opportunity to utilize Randomized Control Trials (RCTs) in policy and management. There is a growing field of quasi-experimental methodologies that allow us to reproduce many of the features of RCTs to make strong causal claims when certain conditions are met. 


<br>
<br>















** Week 1 - Interrupted Time Series 

*** { @unit = "", @title = "Lecture Notes", @reading, @lecture }

*** { @unit = "Due MON Mar 23rd", @title = "Lab 01", @assignment }


** Week 2 - Difference-in-Difference Models 

*** { @unit = "", @title = "Lecture Notes", @reading, @lecture }

*** { @unit = "Due MON Mar 30th", @title = "Lab 02", @assignment }


** Week 3 - Panel Data with Fixed Effects  

*** { @unit = "", @title = "Lecture Notes", @reading, @lecture }

*** { @unit = "Due MON Apr 6th", @title = "Lab 03", @assignment }



** Week 4 - Instrumental Variables 

*** { @unit = "", @title = "Lecture Notes", @reading, @lecture }

*** { @unit = "Due MON Apr 13th", @title = "Lab 04", @assignment }



** Week 5 - Regression Discontinuity Design 

*** { @unit = "", @title = "Lecture Notes", @reading, @lecture }

*** { @unit = "Due MON Apr 20th", @title = "Lab 05", @assignment }



** Week 6 - Logistic Regression  

*** { @unit = "", @title = "Lecture Notes", @reading, @lecture }

*** { @unit = "Due MON Apr 27th", @title = "Lab 06", @assignment }



** Week 7 - Propensity Score Matching 

*** { @unit = "", @title = "Lecture Notes", @reading, @lecture }

*** { @unit = "Due FRI May 1st", @title = "Lab 07", @assignment }


<br>
<br>

-------

<br>
<br>








<style> 
body {
   font-family: "Roboto", sans-serif;
}
 
p.italic {
  font-style: italic;
  color: black !important;
}
td {
  text-align: left;
}
td.i {
  text-align: center;
}
iframe {
  align: middle;
}
em {
  color: black !important;
}
article {
  padding-left:20%;
}
</style>
