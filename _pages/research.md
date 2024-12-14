---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<style>
  body {
    line-height: 1.4; /* Adjust line spacing */
  }

  p, li {
    font-size: 1em; /* Font size for regular text */
  }

  .coauthors, .subcontent {
    font-size: 0.9em; /* Customize specific classes if needed */
  }

  .abstract {
    display: none; /* Hide the abstract by default */
    text-align: justify; /* Justify text for better readability */
    margin-top: 5px;
  }

  h2, h3 {
    margin-top: 1.5em; /* Increase space above headings */
  }

  /* Indent subcontents and add bullet points for them */
  ul.subcontent {
    list-style-type: circle; /* Set bullet points to circles for subcontent */
    margin-left: 10px; /* Indent subcontents */
    padding-left: 10px; /* Reduce padding for subcontent */
  }

  .toggle-link {
    color: #007bff;
    text-decoration: underline;
    cursor: pointer;
    font-size: 0.9em;
  }

  /* Divider between each paper */
  .underline {
    display: block;
    margin: 20px 0;
    border-bottom: 1px solid #ddd;
  }
</style>

<script>
  function toggleAbstract(id) {
    var abstract = document.getElementById(id);
    if (abstract.style.display === "none" || abstract.style.display === "") {
      abstract.style.display = "block";
    } else {
      abstract.style.display = "none";
    }
  }
</script>

## Working Papers

<ul>
  <!-- Paper 1 -->
  <li>
    <a href="https://qifan-han.github.io/files/JMP_QifanHan.pdf">The Impact of Banning Online Gambling Livestreams: Evidence from Twitch.tv</a> (with Jasmine Yang and Andrey Simonov)
    <ul class="subcontent">
      <li> <em>Job Market Paper</em> </li>
      <li><span class="toggle-link" onclick="toggleAbstract('abstract-1')">Abstract</span></li>
      <li id="abstract-1" class="abstract">
        The necessity of content regulation on digital platforms, particularly concerning misinformation and harmful content, has sparked a growing debate. While many platforms have increasingly relied on self-regulation to address these issues, the effectiveness of such measures remains uncertain, as platforms may prioritize profits over consumer protection, potentially leading to misaligned incentives with regulators. We investigate the effectiveness and market outcomes of content self-regulation by studying Twitch’s ban on online gambling livestreams in October 2022, using a novel high-frequency panel dataset covering the top 6,000 Twitch streamers. To identify banned content and streamers affected by the policy, we leverage video analysis on historical video clips, high-frequency stream titles, and in-stream chat analysis. To tackle key identification challenges, we use three causal estimators: two-way fixed effects DiD, Synthetic DiD, and the doubly-robust estimator of group-time average treatment effects, and propose a network analysis to construct valid treated and control groups. On the supply side, we find that the policy caused a reduction in weekly gambling streams by 63.2% for streamers whose content was banned and 12.2% for streamers whose content was not banned. However, the policy also decreased non-gambling streams as an unintended cost for the platform, resulting in an overall reduction in content production and diversity. Additionally, the more popular streamers experienced a higher content reduction, driven by two underlying mechanisms: lower reliance on gambling content and concerns for reputation. On the demand side, we find that the policy only reduced total viewership and low-tier subscriptions, with revenue from loyal viewers unaffected. We discuss the implications of Twitch’s policy ban and the broader practices of content self-regulation on platforms in general.
      </li>
    </ul>
  </li>

  <div class="underline"></div>

  <!-- Paper 2 -->
  <li>
    <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4538856">Collaboration Among Content Creators</a> (with Jasmine Yang and Kinshuk Jerath)
    <ul class="subcontent">
<!--      <li> <em>with Jasmine Yang and Kinshuk Jerath</em> </li>-->
      <li><span class="toggle-link" onclick="toggleAbstract('abstract-2')">Abstract</span></li>
      <li id="abstract-2" class="abstract">
        We study content collaboration in the creator economy, in which competing creators mutually agree to collaborate on joint content and negotiate on content production and revenue sharing. Using a game theory model with creators competing for consumers on a Hotelling line, we show that collaboration allows creators to use the jointly-produced content to moderate competition, while using their individual content to expand into new audiences. This increases content diversity but also leads to increased monetizability of content. In general, collaboration among creators has an effect of increasing the profits of creators while reducing consumer surplus. When creators create content with heterogeneous entertainment values, the creator producing content of lower entertainment value has an incentive to free ride on the collaborative content. This free riding may increase surplus for consumers (who without collaboration would watch content of low entertainment value), thereby improving creators’ profits as well as consumer surplus. Our results provide guidance to content creators, to platforms designing tools to facilitate collaborations, and to policymakers.
      </li>
    </ul>
  </li>

  <div class="underline"></div>

  <!-- Paper 3 -->
  <li>
    <a href="https://qifan-han.github.io/files/IRF_paper.pdf">Impulse Response Inferences With Existence of Repeated Roots</a>
    <ul class="subcontent">
<!--      <li>Co-authors: Not applicable</li>-->
      <li><span class="toggle-link" onclick="toggleAbstract('abstract-3')">Abstract</span></li>
      <li id="abstract-3" class="abstract">
        Vector Autoregression (VAR) and local projection (LP) are the two main methods of estimating and conducting inferences of the impulse response functions (IRFs) in macroeconomic studies, allowing researchers to choose between them based on the subjects of interest. This paper extends existing works on the comparison between AR inferences and LP inferences, by considering data generating processes with repeated roots. Consequently, the autoregressive estimation of impulse responses will converge to a special type of real-valued random variable, and the bootstrap Efron confidence interval of lag-augmented AR will always be conservative, even if the roots are away from the unit circle. This problem is more severe when the time series is highly persistent and at both intermediate and long horizons. The results are supported by Monte Carlo simulations with different values of roots in AR(2), AR(3) and VAR(1) models.
      </li>
    </ul>
  </li>

</ul>

## Work in Progress

<ul>
  
  <!-- WIP 1 -->
  <li>
    Partial Identification Under Multiple Nest Structures
  </li>
    <ul class="subcontent">
      <li><span class="toggle-link" onclick="toggleAbstract('abstract-wip-1')">Abstract</span></li>
      <li id="abstract-wip-1" class="abstract">
        Nested logit model is one of the most widely applied tools in discrete choice analysis, due to its ability to capture rich substitution patterns in market data. However, the researcher needs to define a nest structure ex ante, as the chosen nest is usually based on prior knowledge of the market and will be applied to all individuals. This paper discusses the identification of individual preferences, while relaxing this unique nest structure assumption and allowing for heterogeneity in individuals' recognition of the nest structures in the same market. I characterize the sharp identification region of parameters in the nested logit model, based on the coexistence of a given set of nest structures. I show in a series of Monte Carlo simulations that misspecification of the nest structure may result in the identification region not covering the true parameter, whereas the identification region solves the misspecification problem and partially identifies the parameters by allowing for multiple nest structures.
      </li>
      <li><a class="toggle-link" href="https://qifan-han.github.io/files/Seminar_Presentation_SP2023.pdf" target="_blank">Presentation at BU Econometrics Seminar, Spring 2023</a></li>
    </ul>

  <div class="underline"></div>
  
  <!-- WIP 2 -->
  <li>
        Optimal Achievement System Design on Video Game Platforms
  </li>

</ul>
