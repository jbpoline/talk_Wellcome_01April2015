## Outline
     
> * Why I came to work on reproducibility issues
> * Agreeing on the scale of the problem and why the situation is blocked 
> * __What can we: {researchers, editors, funding agencies, universities} do?__
> * Conclusion: how to we change our research culture. 

# Part I: Introduction

## Why I came to work on reproducibility 

> * Engineering applied mathematics to biology background.
> * Method development for brain imaging, managed research projects, large imaging genetics databasing. _Constant interactions with cognitive neuroscience and clinical research._
> * Realized brain imaging research done was poorly reproducible, inefficient, and mistakes were ubiquitous.
> * Many of us were playing the "publication and grant" game.
> * Invested some times in neuroinformatics and took a job at Berkeley where reproducibility was considered an important axis

## The scale of the problem in Brain Imaging and what is the current culture

> * NIH is investing ~400M$ each year in neuroimaging studies.
> * "Would the finding for which this paper is published be replicated on another dataset?" 
> * Difficult to assess, only a few relevant papers, tend to show little replication.
> * 20 years of experience with researchers using neuroimaging as a tool:
    - PhDs / Postdoc / tenured researchers need papers and grants
    - "Data squeezing", p-hacking, double dipping 
    - Percentage of solid and replicable studies in brain mapping : [5%-25%]. 
> * Percentage of re-usable data & analyses? Less than a few percents if not funded specifically for sharing. 

## Why is the publication-centered culture very difficult to change?

> * Researchers need/want jobs, they optimize their behaviour to get jobs 
> * Universities need money and they will optimize criteria to get grants 
> * Administrations loves quantitative criteria: numbers are easier to manage
> * Conclusion: publication-centered culture, the only widely accepted "currency" in research
    - research has become a competitive game : be the quickest, collaborate only if you need
    - keep "your" data for yourself, or trade it for authorship 
    - a culture of secrecy and sloppiness, no time to check things or train yourself properly
> * A great deal of cynicism / disillusion in some communities

# Part II: Who can do what? 

## Incentives and Punish by reward

> * Most of us think we need to change the incentives: the "rewards", or "punish" bad behaviour
> * <div style="float:center" markdown="1">
  ![Punish by reward](./img/punish_by_reward_50pc.jpg)
    </div>

<!-- 
The pb with this way of thinking is that rewarding people for certain type of works will make the work less interesting and people less committed to it. Currently, we reward the work with the paper currency, and this tends to change our work to get more currency. We optimize numbers. 
-->

## Do not change the incentives

> * Because these new incentives will be optimized and abused.
> * Because working for specific incentives is likely to be detrimental to the work
> * Because evaluation cannot be reduced to a set of numbers: it takes time and competences. 
> * Carrots and sticks seem to work very well for some pets, but do they for researchers?
> * Remove incentives as far as possible

## Mostly the funding agencies' call 

> * Other "stakeholders" are stuck in local minima, or need to feed their kids
> * Funding agencies have the less constraints 
> * Consider all ethical aspects in clinical research: strong rational for sharing 
> * Consider how much is re-used of what has been funded: make research less costly / more efficient
> * Consider funding infrastructures for sharing data, or for training
> * Consider continuous funding of current infrastructures (how ?)

## Practical steps: 
> * Grant review guidelines have a new section: significance, feasibility, ... *replicability+re-usability*, 
> * Evaluation of the applicants will include ways previous research can be re-used
> * Code and data are released with appropriate license and reviewed as deliverable (data paper?)
> * Increase funding in development of tools for open-science (data-sharing, collaborative tools)

## Universities' call: Train on statistical and computational methods

> * Train on open and collaborative science (eg git/github)
> * Train life science researchers in depth programming skills  ("data science")
> * Train life science researchers in depth in statistics ("data science")

## Researcher's call: The research manifesto / "Hippocratic oath"

> * I will make my research open and let tools and data be re-usable by others 
> * I will foster collaboration in the areas where this would improve the work
> * I will take the time to train myself in key areas 
> * I will consider how my actions are first benefiting the progress of knowledge 

## On the statistical / computational side of things 

> * The damaging effect of p-values (cf psychology journal ban on p-values)
> * Effect sizes and power: journals' call
> * Publish models and model comparisons
> * Replication with open data
> * Code review and testing ("un-tested code is broken code") 

# Part III: Conclusion 

## Conclusion: What shall we do about it 

> * Train the new generation of scientist in computation, statistics, open science
> * multiply initiatives like OSF, many lab and community based projects, METRICS (Meta-Research) institutes
> * Work with journals and editors to accept well powered null findings, replication studies
> * Foster a culture of re-usable science through new grants/publications calls and guidelines
> * Foster the "replicate and advance" culture. 


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

<!-- begin_notes
<div>
something big here
</div>
end_notes -->
