---
title: Ontology
displaytext: Ontology
layout: null
tab: true
order: 3
tags: oat
---

## Ontology

### Introduction

The A-Z list of automated threat events and summary descriptions, defined in full in the [OWASP Automated Threat Handbook](https://github.com/OWASP/www-project-automated-threats-to-web-applications/tree/master/assets/files/EN), is:

Identifier | OAT Name | Summary Defining Characteristics
---------|----------|-----------------------------------
[OAT-020](assets/oats/EN/OAT-020_Account_Aggregation.html) | Account Aggregation | Use by an intermediary application that collects together multiple accounts and interacts on their behalf
[OAT-019](assets/oats/EN/OAT-019_Account_Creation.html) | Account Creation | Create multiple accounts for subsequent misuse
[OAT-003](assets/oats/EN/OAT-003_Ad_Fraud.html) | Ad Fraud | False clicks and fraudulent display of web-placed advertisements
[OAT-009](assets/oats/EN/OAT-009_CAPTCHA_Defeat.html) | CAPTCHA Defeat | Solve anti-automation tests
[OAT-010](assets/oats/EN/OAT-010_Card_Cracking.html) | Card Cracking | Identify missing start/expiry dates and security codes for stolen payment card data by trying different values
[OAT-001](assets/oats/EN/OAT-001_Carding.html) | Carding | Multiple payment authorisation attempts used to verify the validity of bulk stolen payment card data
[OAT-012](assets/oats/EN/OAT-012_Cashing_Out.html) | Cashing Out | Buy goods or obtain cash utilising validated stolen payment card or other user account data
[OAT-007](assets/oats/EN/OAT-007_Credential_Cracking.html) | Credential Cracking | Identify valid login credentials by trying different values for usernames and/or passwords
[OAT-008](assets/oats/EN/OAT-008_Credential_Stuffing.html) | Credential Stuffing | Mass log in attempts used to verify the validity of stolen username/password pairs
[OAT-021](assets/oats/EN/OAT-021_Denial_of_Inventory.html) | Denial of Inventory | Deplete goods or services stock without ever completing the purchase or committing to the transaction
[OAT-015](assets/oats/EN/OAT-015_Denial_of_Service.html) | Denial of Service | Target resources of the application and database servers, or individual user accounts, to achieve denial of service (DoS)
[OAT-006](assets/oats/EN/OAT-006_Expediting.html) | Expediting | Perform actions to hasten progress of usually slow, tedious or time-consuming actions
[OAT-004](assets/oats/EN/OAT-004_Fingerprinting.html) | Fingerprinting | Elicit information about the supporting software and framework types and versions
[OAT-018](assets/oats/EN/OAT-018_Footprinting.html) | Footprinting | Probe and explore application to identify its constituents and properties
[OAT-005](assets/oats/EN/OAT-005_Scalping.html) | Scalping | Obtain limited-availability and/or preferred goods/services by unfair methods
[OAT-011](assets/oats/EN/OAT-011_Scraping.html) | Scraping | Collect application content and/or other data for use elsewhere
[OAT-016](assets/oats/EN/OAT-016_Skewing.html) | Skewing | Repeated link clicks, page requests or form submissions intended to alter some metric
[OAT-013](assets/oats/EN/OAT-013_Sniping.html) | Sniping | Last minute bid or offer for goods or services
[OAT-017](assets/oats/EN/OAT-017_Spamming.html) | Spamming | Malicious or questionable information addition that appears in public or private content, databases or user messages
[OAT-002](assets/oats/EN/OAT-002_Token_Cracking.html) | Token Cracking | Mass enumeration of coupon numbers, voucher codes, discount tokens, etc
[OAT-014](assets/oats/EN/OAT-014_Vulnerability_Scanning.html) | Vulnerability Scanning | Crawl and fuzz application to identify weaknesses and possible vulnerabilities
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp; | &nbsp;

### Comparison with other dictionaries, taxonomies and lists

#### [Common Attack Pattern Enumeration and Classification](https://capec.mitre.org/) (CAPEC)

![Venn diagram showing OWASP Autoamted Threats (OATs) fromCAPEC point of view](assets/images/Ontology-chart-capec-wiki.png)

CAPEC is a dictionary and classification taxonomy of known attacks on software. Its primary classification structures are:

* [Domains of attack](https://capec.mitre.org/data/definitions/3000.html) (3000) - Social Engineering (403), [Supply Chain](https://capec.mitre.org/data/definitions/437.html) (437), Communications (512), [Software](https://capec.mitre.org/data/definitions/513.html) (513), Physical Security (514), Hardware (515)
* Mechanism of Attack (1000) - Gather Information (118), Deplete Resources (119), Injection (152), Deceptive Interactions (156), Manipulate Timing and State (172), Abuse of Functionality (210), Probabilistic Techniques (223), Exploitation of Authentication (225), Exploitation of Authorization (232), Manipulate Data Structures (255), Manipulate Resources (262), Analyze Target (281), Gain Physical Access (436), Malicious Code Execution (525), Alter System Components (526), Manipulate System Users (527)

#### [WASC Threat Classification](http://projects.webappsec.org/w/page/13246978/Threat%20Classification)

![Venn diagram showing OWASP Autoamted Threats (OATs) from WASC point of view](assets/images/Ontology-chart-wasc-wiki.png)

The WASC Threat Classification classifies weaknesses and attacks that can lead to the compromise of a website, its data, or its users.

#### [OWASP WASC Web Hacking Incidents Database Project](https://wiki.owasp.org/index.php/OWASP_WASC_Web_Hacking_Incidents_Database_Project) (WHID)

WHID classifies publicly known incidents using:

* attack methods e.g. ARP spoofing, abuse of functionality, account compromise, administration error, automation, backdoor, banking trojan, brute force, clickjacking, code injection, content injection, content spoofing, credential/session prediction, cross site request forgery (CSRF), cross-site scripting (XSS), denial of service, directory traversal, domain hijacking, DNS hijacking, forceful browsing, HTTP response splitting, hidden parameter manipulation, hosting malicious code, information leakage, insufficient authentication, known vulnerability, local file inclusion (LFI), malvertising, malware, malware injection, mass assignment, misconfiguration, OS commanding, parameter manipulation, path traversal, phishing, predictable resource location, process automation, redirection, remote file inclusion (RFI), rogue 3rd party app, scaping, search engine poisoning, shell injection, social engineering, stolen credentials, SQL injection, unintentional information disclosure, weak password recovery validation, worm
* weakness e.g. abuse of functionality, application misconfiguration, directory indexing, improper filesystem permissions, improper input handling, improper output handling, information leakage, insecure indexing, insufficient anti-automation, insufficient authentication, insufficient authorization, insufficient entropy, insufficient password recovery, insufficient process validation, insufficient session expiration, insufficient transport layer protection, misconfiguration, predictable resource location, weak password
* outcome e.g. account hijacking, account takeover, botnet participation, chaos, credit card leakage, data loss, defacement, DDoS attacks, DNS hijacking, DNS redirection, disinformation, disclosure only, downtime, extortion, fraud, information warfare, leakage of information, link spam, loss of sales, malware distribution, monetary loss, phishing, planting of malware, service disruption, session hijacking, spam, spam links, stolen credentials, worm
Plus other/various/unknown.


