---
title: "DoubleX: Statically Detecting Vulnerable Data Flows in Browser Extensions at Scale"
collection: publications
permalink:
excerpt: ''
when: November 2021
date: November 2021
year: 2021
authors: <b>Aurore Fass</b>, Doliere Francis Some, Michael Backes, and Ben Stock
venue: 'ACM CCS'
acceptance: 23% (131/564 full research papers, May cycle)
paperurl: 'https://swag.cispa.saarland/papers/fass2021doublex.pdf'
code: 'https://github.com/Aurore54F/DoubleX'
citation:
---
Browser extensions are popular to enhance users' browsing experience. By design, they have access to security- and privacy-critical APIs to perform tasks that web applications cannot traditionally do. Even though web pages and extensions are isolated, they can communicate through messages. Specifically, a vulnerable extension can receive messages from another extension or web page, under the control of an attacker. Thus, these communication channels are a way for a malicious actor to elevate their privileges to the capabilities of an extension, which can lead to, e.g., universal cross-site scripting or sensitive user data exfiltration. To automatically detect such security and privacy threats in benign-but-buggy extensions, we propose our static analyzer DoubleX. DoubleX defines an Extension Dependence Graph (EDG), which abstracts extension code with control and data flows, pointer analysis, and models the message interactions within and outside of an extension. This way, we can leverage this graph to track and detect suspicious data flows between external actors and sensitive APIs in browser extensions.

We evaluated DoubleX on 154,484 Chrome extensions, where it flags 278 extensions as having a suspicious data flow. Overall, we could verify that 89% of these flows can be influenced by external actors (i.e., an attacker). Based on our threat model, we subsequently demonstrate exploitability for 184 extensions. Finally, we evaluated DoubleX on a labeled vulnerable extension set, where it accurately detects almost 93% of known flaws.
