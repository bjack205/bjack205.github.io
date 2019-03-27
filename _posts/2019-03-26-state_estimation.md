---
layout: post
title:  "Markov Chain Monte Carlo Sampling Estimation"
date:   2019-02-17
author: Brian Jackson
categories: projects
tags: Stanford robotics
---

For AA273 - State Estimation for Aerospace Systems with Dr. Mac Schwager, I worked with John Lambert to implement an algorithm to track multiple targets given noisy state information, using Markov Chain Monte Carlo sampling, and compared its performance to the more canonical multi-hypothesis Kalman filter. Here's an example of the algorithm in practice:
![MCMC_filter](/assets/MHKF_short.gif)
[MCMC_paper](/assets/MCMC_paper.pdf)

Code is available on [GitHub](https://github.com/bjack205/MultiRobotTracking.git)

