---
title: "Software"
layout: gridlay
sitemap: false
permalink: /software/
---

<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}
</style>

### Software

<div class="jumbotron">
  <div class="row align-items-end">
  <div class="col-md-12 col-sm-12">
  <h4><b>JAX-CanVeg: A differentiable land surface model</b></h4>
  <a href="https://github.com/pnnl/JAX-CanVeg" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a>

  Land surface process describes the water, energy, and carbon cycles exchanged among the atmosphere, canopy, and soil. Its complex interacting nature makes it challenging to model due to the associated unknown biophysical and ecophysiological parameters and less-mechanistically represented subprocesses. Differentiable modeling provides a new opportunity to explore the parameter space and capture these complex interactions by seamlessly coupling process-based and deep learning models. Here, we developed a differentiable land surface model by reimplementing an existing simulator, CanVeg, in JAX -- a Google-developed Python package for high-performance machine learning research using automatic differentiation. Anchored in differentiable modeling, we expect that JAX-CanVeg provides a new avenue for modeling land-atmospheric interactions by leveraging the benefits of both data-driven learning and process-based modeling.
  </div>
  </div>
</div>

<div class="jumbotron">
  <div class="row align-items-end">

  <div class="col-md-12 col-sm-12">
  <h4><b>DART-PFLOTRAN: An ensemble-based data assimilation system for estimating subsurface flow and transport model parameters</b></h4>
  <a href="https://github.com/PeishiJiang/DART-PFLOTRAN" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a>

  This is a software framework for integrating PFLOTRAN and DART. The objective is to allow users to conduct ensemble data assimilation on PFLOTRAN by using DART assimilation engine.
  </div>

  </div>
</div>

<div class="jumbotron">
  <div class="row align-items-end">
  <div class="col-md-12 col-sm-12">
  <h4><b>An information-theoretic framework for causal history analysis in complex system dynamics</b></h4>
  <a href="https://github.com/PeishiJiang/info" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a>

  This is an open-source program for evaluating the complex system dynamics by using a proposed causal history analysis framework.
  </div>
  </div>
</div>

<div class="jumbotron">
  <div class="row align-items-end">

  <div class="col-md-12 col-sm-12">
  <h4><b>EMELI-WEB: A Web Application for Experimental Modeling Environment Framework for Linking and Interoperability</b></h4>
  <a href="http://ecgs.ncsa.illinois.edu/EMELI.html" target="_blank"><button class="btn btn-info btn-sm">Bitbucket</button></a>

  EMELI-WEB is a web application for EMELI (Experimental Modleing Environment Framework for Linking and Interoperability). The objective of creating EMELI-WEB is to integrate BMI-enabled web service models in a service-oriented architecture, and also make it easy for users to utilize this resource through a web application. The original EMELI is a smart modeling framework, written in Python and able to couple reusable models standardized through CSDMS Basic Model Interface (BMI). In this project, EMELI is revised to integrated BMI-enbled Web Service Model (BMI) and elevated to a web application by using Flask. The basic procedures of using EMELI-WEB includes selecting models, configuring models, coupling models and showing results.
  </div>

  </div>
</div>
