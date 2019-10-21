---
title: "JaSt: Fully Syntactic Detection of Malicious (Obfuscated) JavaScript"
collection: publications
permalink:
excerpt: ''
date: June 2018
year: 2018
authors: <b>Aurore Fass</b>, Robert Krawczyk, Michael Backes, and Ben Stock
venue: 'Proceedings of the International Conference on Detection of Intrusions and Malware, and Vulnerability Assessment (DIMVA)'
acceptance: 32% (18/56 full research papers)
paperurl: 'https://swag.cispa.saarland/papers/fass2018jast.pdf'
code: 'https://github.com/Aurore54F/JaSt'
citation:
---
JavaScript is a browser scripting language initially created to enhance the interactivity of web sites and to improve their user-friendliness. However, as it offloads the work to the user's browser, it can be used to engage in malicious activities such as Crypto Mining, Drive-by Download attacks, or redirections to web sites hosting malicious software. Given the prevalence of such nefarious scripts, the anti-virus industry has increased the focus on their detection. The attackers, in turn, make increasing use of obfuscation techniques, so as to hinder analysis and the creation of corresponding signatures. Yet these malicious samples share syntactic similarities at an abstract level, which enables to bypass obfuscation and detect even unknown malware variants.

In this paper, we present JaSt, a low-overhead solution that combines the extraction of features from the abstract syntax tree with a random forest classifier to detect malicious JavaScript instances. It is based on a frequency analysis of specific patterns, which are either predictive of benign or of malicious samples. Even though the analysis is entirely static, it yields a high detection accuracy of almost 99.5% and has a low false-negative rate of 0.54%.
