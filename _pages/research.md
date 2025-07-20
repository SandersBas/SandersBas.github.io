---
title: ""
layout: single
permalink: /research/
classes: wide
---


# <center> Working Papers  </center>
- - -

**A New Bayesian Bootstrap for Quantitative Trade and Spatial Models** *(Job Market Paper)* <br />
<small>[ <a href="#/" onclick="visib('BB')">Abstract</a> | [Draft][Draft_BB] | [arXiv version][arXiv_BB]] 

<div id="BB" style="display: none; text-align: justify; line-height: 1.2" ><small>
Economists use quantitative trade and spatial models to make counterfactual predictions. Because such predictions often inform policy decisions, it is important to communicate the uncertainty
surrounding them. Three key challenges arise in this setting: the data are dyadic and exhibit complex dependence; the number of interacting units is typically small; and counterfactual
predictions depend on the data in two distinct ways—through the estimation of structural parameters and through their role as inputs into the model’s counterfactual equilibrium. I address
these challenges by proposing a new Bayesian bootstrap procedure tailored to this context. The method is simple to implement and provides both finite-sample Bayesian and asymptotic
frequentist guarantees. Revisiting the results in Waugh (2010), Caliendo and Parro (2015), and Artuç, Chaudhuri, and McLaren (2010) illustrates the practical advantages of the approach.
</small><br><br/></div>

[Draft_BB]:{{ site.baseurl }}{% link files/NBBQTSM_2025_07_20.pdf %}

[arXiv_BB]: https://arxiv.org/abs/2505.11967

**Measurement Error and Counterfactuals in Quantitative Trade and Spatial Models**, *R&R at Review of Economics and Statistics*  <br />
<small>[ <a href="#/" onclick="visib('ME')">Abstract</a> | [Draft][Draft_ME] | [arXiv version][arXiv_ME] | [Toolkit][Toolkit_ME] ] 

<div id="ME" style="display: none; text-align: justify; line-height: 1.2" ><small>
Counterfactuals in quantitative trade and spatial models are functions of the current state of the world and the model parameters. Common practice treats the current state of the world as
perfectly observed, but there is good reason to believe that it is measured with error. This paper provides tools for quantifying uncertainty about counterfactuals when the current state of the
world is measured with error. I recommend an empirical Bayes approach to uncertainty quantification, and show that it is both practical and theoretically justified. I apply the proposed
method to the settings in Adao, Costinot, and Donaldson (2017) and Allen and Arkolakis (2022) and find non-trivial uncertainty about counterfactuals.</small><br><br/></div>

[Draft_ME]:{{ site.baseurl }}{% link files/MECQTSM_2025_06_20.pdf %}

[arXiv_ME]: https://arxiv.org/abs/2311.14032

[Toolkit_ME]: https://github.com/SandersBas/MECQTSM

**Weighing Experimental vs. Observational Evidence: Decision-Relevant Summaries of Treatment Effect Heterogeneity**, joint with Isaiah Andrews and Raj Chetty <br />
<small>[ <a href="#/" onclick="visib('TEH')">Abstract</a> ] 

<div id="TEH" style="display: none; text-align: justify; line-height: 1.2" ><small>
We characterize when and how experimental evidence should be combined with observational information to guide treatment adoption at a new site. We show that the optimal linear predictor for the site-specific treatment effect is a weighted average of the cross-site experimental ATE and the local observational estimate, with weights determined by the covariance matrix of site effects and observational estimands.  We provide unbiased estimators for this covariance in settings with both large and small sites, quantify the effect of mismatch between experimental and target sites, and derive easy-to-interpret breakdown points. Empirical illustrations using the Year Up RCT and Project STAR show substantial gains, with up to 40 percent reductions in out-of-sample MSE over naive ATE extrapolation.
</small><br><br/></div>



[//]: This java script is the button to show abstract
 <script>
  function visib(id) {
   var x = document.getElementById(id);
   if (x.style.display === "block") {
     x.style.display = "none";
   } else {
     x.style.display = "block";
   }
 }
 </script>

 [//]:&emsp;<button onclick="visib('polariz')" class="btn btn--inverse btn--small">Abstract</button>
 
