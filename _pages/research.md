---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<style>
  /* Typography & spacing */
  body { line-height: 1.4; }
  p, li { font-size: 1em; }
  .coauthors, .subcontent { font-size: 0.9em; }
  h2, h3 { margin-top: 1.5em; }

  /* Subcontent list styling */
  ul.subcontent {
    list-style-type: circle;
    margin-left: 10px;
    padding-left: 10px;
  }

  /* Divider between papers */
  .underline {
    display: block;
    margin: 20px 0;
    border-bottom: 1px solid #ddd;
  }

  /* Abstracts are collapsed by default */
  .abstract {
    display: none;
    text-align: justify;
    margin-top: 5px;
  }

  /* Toggle link with rotating triangle */
  .toggle-link {
    color: #007bff;
    text-decoration: underline;
    cursor: pointer;
    font-size: 0.9em;
    margin-left: 8px;
    display: inline-flex;
    align-items: center;
    gap: 6px;
  }

  /* Triangle icon (right-pointing by default) */
  .toggle-link::before {
    content: "";
    display: inline-block;
    width: 0; height: 0;
    border-style: solid;
    border-width: 6px 0 6px 9px;         /* right-pointing triangle */
    border-color: transparent transparent transparent currentColor;
    transform: rotate(0deg);              /* ▶ */
    transition: transform 0.18s ease;
  }

  /* Rotate triangle down when expanded */
  .toggle-link[aria-expanded="true"]::before {
    transform: rotate(90deg);             /* ▼ */
  }

  /* Keyboard focus visible */
  .toggle-link:focus {
    outline: 2px dotted #007bff;
    outline-offset: 2px;
  }
</style>

<script>
  function toggleAbstract(id, linkEl) {
    var abs = document.getElementById(id);
    var isHidden = abs.style.display === "none" || abs.style.display === "";
    abs.style.display = isHidden ? "block" : "none";
    if (linkEl) {
      linkEl.setAttribute("aria-expanded", isHidden ? "true" : "false");
      linkEl.textContent = isHidden ? "Hide abstract" : "Show abstract";
    }
    abs.setAttribute("aria-hidden", isHidden ? "false" : "true");
  }
</script>

## Working Papers

### [Non-neutral Technological Change in Chinese Manufacturing](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5176447) **[Job Market Paper]**
<a class="toggle-link" href="#" onclick="toggleAbstract('abs-jmp', this); return false;"
   aria-controls="abs-jmp" aria-expanded="false">Show abstract</a>
<div id="abs-jmp" class="abstract" aria-hidden="true">
This paper identifies firm-level factor-augmenting productivity for capital, labor, and materials using Chinese manufacturing data from 1998 to 2008, a period marked by the reform of state-owned enterprises. We develop a novel method to estimate the parameters of a CES production function and recover the three types of factor-augmenting productivity. The results reveal strong biased technological change: labor-augmenting productivity grew fastest (12% annually), followed by capital (5%), with both outperforming material-augmenting productivity (1.4%). Factor-augmenting productivity shows heterogeneity across ownership types. Dynamic Olley–Pakes decomposition indicates that productivity growth was primarily driven by incumbents, while entrants improved capital efficiency and exiters enhanced labor efficiency. Using these estimates, we explain the cost-share shifts in terms of factor-augmenting productivity gaps and relative input prices.
</div>

<span class="underline"></span>

### Privatization and Non-neutral Technological Change in Chinese Manufacturing
<a class="toggle-link" href="#" onclick="toggleAbstract('abs-priv', this); return false;"
   aria-controls="abs-priv" aria-expanded="false">Show abstract</a>
<div id="abs-priv" class="abstract" aria-hidden="true">
  <em>Abstract coming soon.</em>
</div>

<span class="underline"></span>

### Artificial Intelligence (AI) and Endogenous Productivity: Evidence from South Korean Firms <em>(joint with Jae Wook Jung)</em>
<a class="toggle-link" href="#" onclick="toggleAbstract('abs-ai', this); return false;"
   aria-controls="abs-ai" aria-expanded="false">Show abstract</a>
<div id="abs-ai" class="abstract" aria-hidden="true">
This paper examines the impact of artificial intelligence (AI) adoption on firm-level productivity. Using all sectors data between 2017 and 2023 in South Korea, we construct measures of AI adoption and estimate endogenous productivity change to address selection into adoption. We find that AI adopters experience a 4% short-run revenue increase on average. Effects are heterogeneous across years and sectors, with stronger gains in ICT and services, and muted or slightly negative impacts in trade and manufacturing.
</div>

<span class="underline"></span>

## Work In Progress

### Vertical Licensing, Pricing, and Welfare: Evidence from the Instant Coffee Market <em>(joint with Muhammad Shabanpour)</em>
<a class="toggle-link" href="#" onclick="toggleAbstract('abs-lic', this); return false;"
   aria-controls="abs-lic" aria-expanded="false">Show abstract</a>
<div id="abs-lic" class="abstract" aria-hidden="true">
  <em>Abstract coming soon.</em>
</div>
