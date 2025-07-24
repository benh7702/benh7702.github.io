---
title: "Using Copulas to Model Prepayment and Default in Competing Risks Analysis"

description: "As part of a group project, we produced a report evaluating how effectively copulas model competing risks in loan data."
dateString: May 2025
draft: false
showToc: false
weight: 203
cover:
    image: "/projects/projects/copulas.png"
--- 
### Abstract

This paper explores the use of copula models for analysing competing financial risks, with a particular focus on modelling the dependence between loan prepayment and default events. Beginning with a theoretical overview of copula functions and their application within a competing risks framework, we evaluate the performance of different copula families through simulation studies. These simulations demonstrate that copula-based models can effectively recover both marginal and dependence parameters. The methodology is then applied to a real-world dataset of over two million loans from the Lending Club. Marginal distributions are selected using AIC criteria, with a Weibull distribution fitted for prepayment times and a three-component Weibull mixture for defaults, due to evident multimodality. The results highlight the value of flexible marginal modelling and copula-based approaches in capturing complex interdependencies between financial risks.

{{< pdfbutton src="/projects/projects/Copulas.pdf" text="View the pdf in another tab here" >}}

####  PDF 

<div style="position: relative; padding-top: 75%; height: 0; overflow: hidden;">
  <iframe src="/projects/projects/Copulas.pdf"
          style="position:absolute; top:0; left:0; width:100%; height:300%; border:none;"
          allowfullscreen>
  </iframe>
</div>
