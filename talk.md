## Outline
>     
> * Why I came to work on reproducibility issues
> * Agreeing on the scale of the problem and why the situation is locked 
> * What can {researchers,editors,funding agencies} do?
> * Conclusion: how to we change a culture. 

# Part I: Introduction

## Why I came to work on this

> * Engineering background, applied mathematics to biology
> * Method development for brain imaging, managed research projects, large imaging genetics databasing. Constant interactions with cognitive neuroscience and clinical research.
> * Realized research done was poorly reproducible, inefficient and mistakes were ubiquitous 
> * Many of us were playing the publication game
> * Invested some times in neuroinformatics, resigned from tenure job, took a job at Berkeley where reproducibility was considered an important axis. 

## The scale of the problem in Brain Imaging and what is the current culture

> * NIH is investing about 400M$ each year in neuroimaging studies.
> * Q: "Would the finding for which this paper is published be replicated on another dataset?" 
> * Difficult to assess, only a few relevant papers, tend to show little replication.
> * 20 years of experience with researchers using neuroimaging as a tool:
    - Phds / postdoc / tenured researchers need papers, and grants
    - "data squeezing", p-hacking, double dipping 
    - Percentage of solid and replicable studies in brain mapping : [0-25%]. 
> * Percentage of re-usable data & analyses? Less than a few percents if not funded specifically for sharing. 

## Why is the current culture very difficult to change?

> * Researchers need/want jobs, they optimize their behaviour to get jobs 
> * Universities need money and they will optimize criteria to get grants 
> * Conclusion: optimize publication, the widely accepted currency in research
    - research has become a competitive game : be the quickest, collaborate only if you need
    - keep "your" data for yourself, or trade it for authorship 
    - the situation is fostering secrecy and sloppiness, no time to train yourself properly
> * Administrations loves quantitative criteria: numbers are easier to manage
> * A great deal of cynicism / desabusement in some communities

# Part II: Who can do what? 

## Incentives and Punish by reward

> * Most of us think we need to change the incentives, or "punish" bad behaviour
> * <div style="float:center" markdown="1">
  ![Punish by reward](./img/punish_by_reward_50pc.jpg)
    </div>

## Do not change the incentives

> * Because these new incentives will be optimized and abused.
> * Because working for specific incentives is likely to be detrimental to the work
> * Because evaluation cannot be reduced to a set of numbers: it takes time and competences. 
> * carrots and sticks seem to work very well for some pets, but do they for researchers?

<!-- begin_notes
<div>
something big here
</div>
end_notes -->

## It is mostly the funding agencies' 

> * other "stakeholders" are stuck in local minima, or need to feed their kids
> * they are the ones with the less constraints 
> * consider all ethical aspects in clinical research: strong rational for sharing 
> * consider how much is re-used of what has been funded : make research less costly
> * consider funding infrastructures for sharing data, train 

## practical steps: 
> * grant review guidelines have a new section: significance, feasability, ... *replicability+re-usability*, 
> * evaluation of the applicants will include ways previous research can be re-used
> * code and data are released with appropriate license and reviewed as deliverable (data paper?)

## Universities's call: Training on statistical and computational methods

> * train on open and collaborative science
> * train life science scientists in depth programming skills  ("data science")
> * train life science scientists in depth in statistics ("data science")

## Researcher's call: The research manifesto / Hippocratic oaths

> * I will make my research tools re-usable by others 
> * I will strive to collaborate in the areas where I cannot do the best work
> * I will be as transparent as possible
> * I will take the time to train myself in key areas 
> * I will consider first the actions benefitting the progress of knowledge 

## On the statistical / computational side of things 

> * The damaging effect of p-values (see psychology journal ban on p-values)
> * Effect sizes and power: journals' call
> * Publish models and model comparisons
> * Replication with open data
> * Code review and testing ("un-tested code is broken code") 

# Part III: Conclusion 

## Conclusion: What shall we do about it 

> * Train the new generation of scientist in computation, statistics
> * NIH answers: 
    - Data Discovery Index, checklists 
    - online forum for open discussions, 
    - change in funding and bio, anonymize peer review, etc. 
> * Work with journals and editors to accept well powered null findings
> * OSF, many lab and community based projects, METRICS (Meta-Research) institutes
> * Reward people who produce re-usable science

## Acknowledgement 

* At Berkeley: M. Brett, J. Millman, F. Perez; Simpace interest group:  D. Sheltraw, C. Gallen, A. Tambini, K. K. Hwang; B. Inglis, M. D'Esposito. 
* At INCF: Mathew Abrams, Linda Layon, Roman Valls
* Nidash: David Kennedy, Satra Ghosh, Chris Gorgowleski, Nolan Nichols, Dave Keator, Camille Maumet, Guillaume Flandin, Tom Nichols, Russ Poldrack, and others 
* At Pasteur: Roberto Toro; At Neurospin: B. Thirion; at the MNI: PJT and colleagues

## References

* K. Button et al., Nature Neuroscience, 2013
* Nature, "Reducing our irreproducibility", 2013.
    - New mechanism for independently replicating needed 
    - Easy to misinterpret artefacts as biologically important
    - Too many sloppy mistakes
* NIH plans to enhance reproducibility. Collins and Tabak, Nature, 2014.
* Boekel, W., et al. (Cortex 2013) : replication study of structural brain-behavior correlations.
* J. Carp Cogn Affect Behav Neurosci, 2013
* Poldrack, R.A., and Poline, J.-B. (2014). [...] reproducibility challenges of shared data. TICS.
* Griffiths, T.L. (2015). Manifesto for a new (computational) cognitive revolution. Cognition 135, 21–23.


<!-- begin_comment 

##  "Effective" approaches: research management laziness

> * recruiting committees: how can we make papers less important ?
> * reviewers : how do I review the code ? How do I see what has been done before?

## What about brain imaging ? Some - _but few_ - facts

> * Publication does not allow replication or to find methodological issues (J. Carp Cogn Affect Behav Neurosci, 2013): 

"For example, while Brown and Braver (2005) claimed that activation in the
anterior cingulate cortex (ACC) is sensitive to the likelihood of committing
an error, Nieuwenhuis, Tanja, Mars, Botvinick, and Hajcak (2007) reported no
relationship between ACC activation and error likelihood."

> * When attempted, replication is poor:  
  - Boekel, W., et al. (Cortex 2013) : replication study of structural brain-behavior correlations.
  - 5 studies, 17 findings: Bayesian analysis favored null hypothesis
  - But: only 36 subjects, while most original studies were better powered

> * Autism example: Toro et al., Corpus callosum size example. S. Bookheimer's examples (cereb. size, FFA, FC). 


<div class="notes">
 * Analysis of large databases showing low concordance of small sample group analysis (Thirion et al., 2007)

R Toro: 
    We conducted a meta-analysis of the literature which suggested a
    statistically significant difference. However, the studies included were
    heavily underpowered: on average only 20% power to detect differences of
    0.3 standard deviations, which makes it difficult to establish the reality
    of such a difference. We therefore studied the size of the corpus callosum
    among 694 subjects (328 patients, 366 controls) from the Abide cohort.
    Despite having achieved 99% power to detect statistically significant
    differences of 0.3 standard deviations, we did not observe any.
</div>


end_comment --> 

