---
layout: page
title: "Spiking neural network for detecting speech emotion"
---

## Summary

0. Became interested in spiking neural networks (SNN) for the opportunities they
offer in the real-time processing of continuous-time signals[^1].
1. Read a few papers on spiking neural networks for speech classification as 
well as audio-to-spike encoding schemes.
2. Implemented a completely biologically-plausible audio-to-spike encoding. 
For me, the advantage to using a biologically plausible method is that 
processing can now be done in real-time as the signal appears. Which happens to
be how our ears work, but not how common digital audio processing methods work.
3. Implemented a spiking neural network with a basic plasticity rule "from 
scratch" (using numpy). This was because available SNN libraries (e.g. NEST, 
snnTorch) seemed either too complex (intended for modelling physiology) or used 
deep learning methods that defeat my goal of real-time processing of a 
continuous signal.
4. Trained a Support Vector Machine to map readouts of the SNN to emotion labels.
5. So far, accuracy is only slightly better than random chance ;_;.
6. Currently looking for possible bugs + ways to improve the network's 
architecture.

[^1]: By "continuous-time signals" I mean a signal that can be sampled at any point in continuous time.


## Skills gained


## Longer description

The deeper reason I became interested in training an SNN is that I suspect 
neuromorphics will be used in future brain-computer-interfaces.

**Hold on, what is a spiking neural network, and what are neuromorphics?**



## References


---