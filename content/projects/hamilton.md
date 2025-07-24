---
title: "Sampling Plackett-Luce Distributions to Study Condorcet Paradoxes in Ranked-Choice Voting"

description: "The report from my research internship that I completed Summer 2024"
dateString: July 2024
draft: false
showToc: false
weight: 205
cover:
    image: "/projects/projects/hamilton.png"
--- 
### Abstract

This report models the incidence of Condorcet paradoxes in elections that use ranked-choice voting. It is known that the occurrence of such paradoxes becomes more likely as the number of voters increases, assuming each candidate is equally preferred by the voters. However, such a scenario is not plausible in the real-world, as some candidates will inevitably be preferred more or less by the electorate than others. In the absence of real data, ballots were generated using a function that samples the Plackett-Luce distribution, which in this context considers the voters propensity to vote for a candidate using weights. Then, an algorithm was run that tests the frequency of Condorcet paradoxes for various amounts of voters and candidates, inferring the probability of its occurrence for various sets of these parameters. The programming language used to generate the ballots and implement the algorithm was R. Interestingly, the probability of a Condorcet paradox tends to zero very quickly for a set of candidates with randomised weights.

{{< pdfbutton src="/projects/projects/Hamilton.pdf" text="View the pdf in another tab here" >}}

####  PDF 

<div style="position: relative; padding-top: 75%; height: 0; overflow: hidden;">
  <iframe src="/projects/projects/Hamilton.pdf"
          style="position:absolute; top:0; left:0; width:100%; height:300%; border:none;"
          allowfullscreen>
  </iframe>
</div>
