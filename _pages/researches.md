---
layout: archive
title: "Research Experiences"
permalink: /research/
redirect_from: 
  - /rs/
  - /researches.html
  
author_profile: true
---

{% include base_path %}

Communicating Classification Results over Noisy Channels 
==========================================================
* Objective: Design framework for characterizing the tradeoff between latency and distortion for transmitting the results of a classifier (assumedly a probability vector).
* Solution: Assuming uniform quantization, used results from finite blocklength theory to create link between source distortion and decoding error probability to enable analyisis of latency/distortion tradeoff.
   * Changed different parameters (i.e. length of probability vector, bandwidth) to observe effect on framework.
* Results: Observe that for a fixed total distortion requirement, there is an optimal source distortion that can provide a minimum latency.

Cell-Free MIMO
=========================================================

High Frequency (HF) Communications 
===========================================================
* Objective: Researched how adaptive equalization and machine learning algorithms can be used to improve transmissions made over the high frequency (HF) Band.
* Solution: Use reinforcement learning (multi-armed bandit algorithms) to learn optimal equalizer configurations (i.e. tap length, step size, adaptive algorithm) for simulated HF channels.
     * Examed for SISO and 2x2 MIMO simulated channels. 
* Results: Showed that bandit based methods can learn equalizer configurations from a given set that can provide better performance than pre-decided adaptive equalizers.


Verification of HF antenna 
============================================================================
* Objective: Worked on Verification of HF antenna
* Solution: Connected the antenna to a URSP N200, operated using GNU Radio. Used flowgraph from Ettus Research to process waveforms transmitted over the HF band.
    * Recorded ranges observed through this system . 

