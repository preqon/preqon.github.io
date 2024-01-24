---
layout: page
title: "Honours project - information transfer in mouse brains"
---

- Studied the neuroscientific background of mammalian visual processing.
- Explored a dataset containing spike recordings from mice (recordings taken 
using Neuropixel probes. i.e. local-field potential recordings)
- Came up with statistical experiments under an information-theoretic approach 
to investigate whether models of information transfer followed expectations from
the neuroscience.
    - Since neuroscience traditionally builds models of correlation in activity
    rather than models of quantified information.
- Found that information transfers in mice visual cortices either followed 
expectations of hierarchical processing or were surprisingly homogenous.
- Recommended future studies in task-related datasets to ascertain how much
information *relevant to a task* is being processed in a recorded brain area.
- Recommended future work in building information-theoretic estimators tailored
to neuronal population dynamics.

## Skills gained 

- Solid grasp on the fundamentals of information theory.
- Familiarity working with neural data (LFP recordings and spike trains).
- Complex statistical inference in an information theoretic context.
- Building complex statistically-driven models of a fundamental principle
(in this case information transfer).
- Extensive literature research. 

## Longer description

My honours supervisor (A/Prof Joseph Lizier) has been studying how information is processed in natural systems like brains. He takes a unique information-theoretic approach (after Shannon entropy etc.) that allows us to observe brain activity and then estimate the amount of information that has been processed.

My project took a specific look at information *transfer* (one of the stages of information processing) inside the visual cortices of mice. It was the first time an information-theoretic estimator of transfer in continuous-time was used on data from living creatures at this scale.

Broadly speaking the goal of the project was to investigate whether information flowed between regions in directions that one expects from the traditional neuroscientific analysis. The traditional approach is to study structural connections, or better yet to study bivariate or multivariate correlations in activity. However the approach followed by Professor Lizier and the growing numbers aware of information theory, allows a model of the *amount of information present in the system*, rather than just a model of correlated activity (what is usually called "functional" or "effective connectivity").

Quantification of information processing can help address large questions in neuroscience like "how does a particular neuronal population encode information relevant to the task being performed?"

Personally, I find the above question particularly exciting because it points to an engineering opportunity. If nature has provided a beautiful machine that stores, transfers and modifies information, why can't we build something similar? Or why can't we build a system that at least *interfaces* with nature's machines, extracting and interacting with the information stored there?

Briefly, the project found information flows that either matched expectations inside the visual cortex or were unexpectedly homogenous between cortical layers. This points to the versatility of how information can be represented and processed across structural connections that are relatively static. We suggested that future studies in neural dynamics during tasks and behaviours can adopt our information-theoretic approach to assess when, where and how much information relevant to a task is being processed inside a recorded brain area.

