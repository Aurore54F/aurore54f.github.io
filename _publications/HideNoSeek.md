---
title: "HideNoSeek: Camouflaging Malicious JavaScript in Benign ASTs"
collection: publications
permalink:
excerpt: ''
date: November 2019
year: 2019
authors: <b>Aurore Fass</b>, Michael Backes, and Ben Stock
venue: 'ACM CCS'
paperurl: 'https://swag.cispa.saarland/papers/fass2019hidenoseek.pdf'
citation:
---
In the malware field, learning-based systems have become popular to detect new malicious variants. Nevertheless, it has been shown that attackers with specific and internal knowledge of a target system may be able to produce input samples which are misclassified. In practice, the assumption of strong attackers is not realistic as it implies access to insider information. We instead propose HideNoSeek, a novel and generic camouflage attack, which evades the entire class of detectors based on syntactic features, without needing any information about the system it is trying to evade. Our attack consists of changing the constructs of a malicious JavaScript sample to imitate a benign syntax. In particular, HideNoSeek uses malicious seeds and searches for similarities at the Abstract Syntax Tree (AST) level between the seeds and traditional benign scripts. Specifically, it replaces benign sub-ASTs by identical malicious ones and adjusts the benign data dependencies--without changing the AST--, so that the malicious semantics is kept after execution.

In practice, we are able to generate 91,020 malicious scripts from 22 malicious seeds and 8,279 benign web pages. In addition, we can hide on average 14 malicious samples in a benign AST of the Alexa top 10, and 13 in each of the five most popular JavaScript libraries. In particular, a standard trained classifier has over 99.7% false-negatives with HideNoSeek inputs, while a classifier trained on such samples has over 96% false-positives, rendering the targeted static detectors unreliable.