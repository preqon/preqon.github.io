---
layout: page
title: "Honours project - information transfer in mouse brains"
---

## Summary

1. Surveyed the literature in mammalian visual processing.
2. Explored a dataset containing spike recordings from mice (recordings taken 
using Neuropixel probes. i.e. local-field potential recordings).
3. Came up with statistical experiments under an information-theoretic approach
to investigate whether models of information transfer followed expectations from
the neuroscience. We suspected there might be discrepancies, since neuroscience
traditionally builds models of functional connectivity/effective connectivity using
correlation in activity rather than models of quantified information.
4. Found that information transfers in mice visual cortices either followed the 
expectations of hierarchical processing or were surprisingly homogenous.
5. Recommended future studies in task-related datasets to ascertain how much
information *relevant to a task* is being processed in a recorded brain area.
6. Recommended future work in building information-theoretic estimators tailored
to neuronal population dynamics.

## Skills gained 

- Fundamentals of information theory.
- Familiarity working with neural data (LFP recordings and spike trains).
- Statistical inference in an information theoretic context.
- Building complex statistically-driven models of a fundamental principle
(in this case information transfer).
- Extensive literature research. 
- Inter-disciplinary communication (worked with neuroscientists, physicists and
computer scientists).

## Longer description

My honours supervisor (A/Prof Joseph Lizier) has been studying how information is processed in natural systems like brains. He takes a unique information-theoretic approach (after Shannon entropy etc.) that allows us to observe brain activity and then estimate the amount of information that has been processed.

My project took a specific look at information *transfer* (one of the stages of information processing) inside the visual cortices of mice. It was the first time an information-theoretic estimator of transfer in continuous-time was used on data from living creatures at this scale.

Broadly speaking the goal of the project was to investigate whether information flowed between regions in directions that one expects from the traditional neuroscientific analysis. The traditional approach is to study structural connections, or better yet to study bivariate or multivariate correlations in activity. However the approach followed by Professor Lizier and the growing numbers aware of information theory, allows a model of the *amount of information present in the system*, rather than just a model of correlated activity (what is usually called "functional" or "effective connectivity").

Quantification of information processing can help address large questions in neuroscience like "how does a particular neuronal population encode information relevant to the task being performed?"

Briefly, the project found information flows that either matched expectations inside the visual cortex or were unexpectedly homogenous between cortical layers. This points to the versatility of how information can be represented and processed across structural connections that are relatively static. We suggested that future studies in neural dynamics during tasks and behaviours can adopt our information-theoretic approach to assess when, where and how much information relevant to a task is being processed inside a recorded brain area.

We also suggested that future studies can look at building information-theoretic
estimators that rely on more emergent structures in dynamical systems; like
bursts and oscillations. This would quantify information processing at various
analytical levels of the dynamical system, not only of spike times of neuronal 
processes. Work with this flavour is being done at the University of Sydney,
as a collaboration between three groups (including Joe's).
- [Ben Fulcher](https://dynamicsandneuralsystems.github.io/)
- [Mac Shine](https://shine-lab.org/research/)
- [Joe Lizier](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/joseph-lizier.html)

I strongly recommend checking them out.

# Submitted thesis

<object data="{site.github.url}" type="application/pdf" width="700px" height="700px">
    <embed src="{site.github.url}">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="http://yoursite.com/the.pdf">Download PDF</a>.</p>
    </embed>
</object>


# Code

You can find the code for this project on my GitHub at 
[spikes-information-transfer](https://github.com/preqon/spikes-information-transfer).
