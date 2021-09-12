---
title: "Statically Detecting JavaScript Obfuscation and Minification Techniques in the Wild"
collection: publications
permalink:
excerpt: ''
when: June 2021
date: June 2021
year: 2021
authors: Marvin Moog, Markus Demmel, Michael Backes, and <b>Aurore Fass</b>
venue: 'Dependable Systems and Networks (DSN)'
acceptance: 16% (48/295 full research papers)
paperurl: 'https://swag.cispa.saarland/papers/moog2021statically.pdf'
code: 'https://github.com/MarM15/js-transformations'
recording: 'https://www.youtube.com/watch?v=ql78Q-JkeNk'
slideurl: 'https://swag.cispa.saarland/papers/moog2021statically.talk.pdf'
citation:
---
JavaScript is both a popular client-side programming language and an attack vector. While malware developers transform their JavaScript code to hide its malicious intent and impede detection, well-intentioned developers also transform their code to, e.g., optimize website performance. In this paper, we conduct an in-depth study of code transformations in the wild. Specifically, we perform a static analysis of JavaScript files to build their Abstract Syntax Tree (AST), which we extend with control and data flows. Subsequently, we define two classifiers, benefitting from AST-based features, to detect transformed samples along with specific transformation techniques.

Besides malicious samples, we find that transforming code is increasingly popular on Node.js libraries and client-side JavaScript, with, e.g., 90% of Alexa Top 10k websites containing a transformed script. This way, code transformations are no indicator of maliciousness. Finally, we showcase that benign code transformation techniques and their frequency both differ from the prevalent malicious ones.