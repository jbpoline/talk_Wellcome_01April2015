## Outline
>     
> * Why I came to work on this  
> * Agreeing on the scale of the problem  
> * Understanding why the situation is blocked 
> * What can {researchers,editors,funding agencies} do?
> * Conclusion: culture change

# Part I: Introduction

## Why I came to work on this
>
> * Biostats, applied maths, became moderatly famous for some early works
> * Managed research projects at Neurospin, including large imaging genetics databasing
> * Realized how research done was poorly reproducible and inefficient 
> * Resigned from tenure job and now working at Berkeley (why Berkeley ?)
  - invested on the neuroinformatics side of things

## Examples in brain imaging

## The scale of the problem  

> * Particularly difficult to assess, but few hints
> * 20 years of experience with researchers using neuroimaging as a tool
> * Proof by logic and understanding the mechanisms: 
    - playing the game, 
    - p-hacking + double dipping + 
    - optimizing research assessments (authorship and the "XXXX" example)
> * Percentage of solid and replicable studies in brain mapping : [0-25%]. 

## Why is the current situation difficult to change?

> * Researchers need/want jobs, they will optimize *any* criteria that will gave them a job 
> * Universities need money (i.e. grants) and they will optimize criteria to get more money
> * Publishing companies need money and they will optimize their behaviour
> * All this makes that impact factor and publication is the widely accepted currency in research

## Punish by reward

> ![Punish by reward](./img/punish_by_reward_80.jpg)


## When an "effective" approach means laziness

> * p-values : how do we get them loose their influence 
> * recruiting committees : how can we make papers less important ?
> * reviewers : how do I review the code ? How do I see what has been done before?

# Part II: What can we do? 

## Who can do what?

## Do not change the incentives


## Funding agencies' call

> * code and data should be release and reviewed
> * practical steps: 
      - grant review guidelines have a new section: (significance, feasability, ... *replicability+re-usability*, evaluation of the applicants will include ways previous research can be re-used)
> * the ethical aspects: the rational for sharing is also ethical !

## Universities call: Training on computational methods

## Researcher's call: The Manifesto / Hippocratic oaths

> * the transparency principle
> * the global versus local optimization

## Training on statistical approach

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
* Nidash: David Kennedy, Satra Ghosh, Chris Gorgowleski, Nolan Nichols, Dave Keator, Camille Maumet, Guillaume Flandin, Tom Nichols, Russ Poldrack, etc
* At Pasteur, Neurospin, MNI.



### Neuroscience

> * Button et al., Nature Neuroscience, 2013

### In general: Editorials in high profile journals

> * Nature, "Reducing our irreproducibility", 2013.
    - New mechanism for independently replicating needed 
    - Easy to misinterpret artefacts as biologically important
    - Too many sloppy mistakes
> * NIH plans to enhance reproducibility. Collins and Tabak, Nature, 2014.

---------------

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


# Part II: The issue 

## Causes and Impact

### Statistical 
### Computational 
### Social 

----------------------------

### Statistical causes:(1)

> * Lack of understanding of statistical issues and power computation
> * The usual issues:
>       - low power studies (Button et al, 2013)
>       - P-hacking: Simmons et al. 2011, Simmonshon et al., 2014

### Example  

> * From imaging genetics (BDNF - Hippocampus volume):
> * ![Molendijk, 2012](./img/molendijk_2012_f4.pdf) 

----------------------------

### Statistical causes:(2)

> * P value evil: will we eventually turn to Bayesian evidence? How ?
> * No good understanding of the necessity to report null results -> File drawer problem (Rosenthal, 1979)  
   - Emmergence of complex H0/H1, A. Afraz, 2014. 

### And if we stick to p-values: 

> * Which one to pick: Revised standard for statistical evidence (PNAS Johnson 2013) : 0.05 <=> BF$\in{[3,5]}$
> * ![Johnson 2013, Significance](./img/Johnson_significance.pdf) 


<div class="notes">

    For instance, H1 “neurons in brain area X encode visual memories” can be
    contrasted against H0 “neurons in brain area X does not encode visual
    memories”. Even if H1 is not true, if only positive results get published,
    after a few years there will be plenty of published papers showing that
    neurons in brain area X encode visual memories. Then, some scientists might
    hypothesize a more complex H1: “neurons in area X encode visual memories by
    synchronization of their electrical activity”, now the null hypothesis
    would be “neurons in area X encode visual memories without synchronization
    of their activity”.  In this new null hypothesis, involvement of area X
    neurons in memory encoding is already assumed. This second null hypothesis
    can be falsely rejected again in contrast to an even more complex
    scientific model, creating an even more complex set of default beliefs and
    null hypotheses. 
</div>
----------------------------

### Computational causes:

> * Biologists and MDs are rarely well trained in computation - but most brain imaging findings rely heavily on computations
> * Claerbout's """An article about computational science in a scientific
   publication is not the scholarship itself, it is merely advertising of the
   scholarship. The actual scholarship is the complete software development
   environment and the complete set of instructions which generated the
   figures.""""
> * Meta data capture and curation not implemented (parameters and process of data generation), no standards for meta data
> * Computational environment packaging not used (Neurodebian VM, Docker, ...)

----------------------------

### Social/systemic causes

> * Publication based reward system (career, grants, fame, etc) + hyper competitive environment is in general not working towards good science:
    - favors speed over careful, __re-usable__, reproduced studies
    - favors high risk and rapid publications
    - impeeds data and code sharing even for publicly funded research
> * Positive finding publication bias and the file drawer problem 
    - how this can delay scientific revolution (A. Afraz, 'We could all be astronomers')
    - is science always self-correcting ? 

----------------------------

### Impact

> * Large amount of resource wasted (talent, money, time) 
> * Discredit from the public and governments
> * Slows down scientific and medical progress
> * Impact on the type of work that can be started (counter example: UK biobank, Bavarian cohorts).
> * The system may select the most "productive" scientists - not necessarily the best


# Part III: Conclusion

## Conclusion: What shall we do about it 

> * Adopt more stringent and better statistical and computational standards 
> * Adopt genetic research standards for replication 
> * Adopt clinical trial standards and pre-registration
> * Augment the awareness of these issues, adopt data and code sharing as the standard in our field

----------------------------

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
* Nidash: David Kennedy, Satra Ghosh, Chris Gorgowleski, Nolan Nichols, Dave Keator, Camille Maumet, Guillaume Flandin, Tom Nichols, Russ Poldrack, etc
* At Pasteur, Neurospin, MNI.



