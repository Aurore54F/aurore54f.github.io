---
title: "Studying JavaScript Security Through Static Analysis"
collection: publications
permalink:
excerpt: ''
when: October 2020
date: October 2020
year: 2020
authors: <b>Aurore Fass</b>
venue: 'PhD Thesis, Saarland University'
paperurl: 'https://publications.cispa.saarland/3471/7/fass2020thesis.pdf'
papersummary: 'https://aurore54f.github.io/papers/fass2020thesissummary.pdf'
code: 'https://github.com/Aurore54F/'
citation:
---
As the Internet keeps on growing, so does the interest of malicious actors. While the Internet has become widespread and popular to interconnect billions of people, this interconnectivity also simplifies the spread of malicious software. Specifically, JavaScript has become a popular attack vector, as it enables to stealthily exploit bugs and further vulnerabilities to compromise the security and privacy of Internet users. In this thesis, we approach these issues by proposing several systems to statically analyze real-world JavaScript code at scale.

First, we focus on the detection of malicious JavaScript samples. To this end, we propose two learning-based pipelines, which leverage syntactic, control and data-flow based features to distinguish benign from malicious inputs. Subsequently, we evaluate the robustness of such static malicious JavaScript detectors in an adversarial setting. For this purpose, we introduce a generic camouflage attack, which consists in rewriting malicious samples to reproduce existing benign syntactic structures. Finally, we consider vulnerable browser extensions. In particular, we abstract an extension source code at a semantic level, including control, data, and message flows, and pointer analysis, to detect suspicious data flows from and toward an extension privileged context. Overall, we report on 184 Chrome extensions that attackers could exploit to, e.g., execute arbitrary code in a victim's browser.