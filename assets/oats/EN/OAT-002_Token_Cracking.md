---

layout: col-sidebar
title: OAT-002 Token Cracking
site_side: false
tags: oatsEN
project: true

---

**Token Cracking** is an automated threat. The OWASP Automated Threat Handbook - Web Applications ([pdf](https://github.com/OWASP/www-project-automated-threats-to-web-applications/tree/master/assets/files/EN), [print](http://www.lulu.com/shop/owasp-foundation/automated-threat-handbook/paperback/product-23540699.html)), an output of the [OWASP Automated Threats to Web Applications Project](../../../), provides a fuller guide to each threat, detection methods and countermeasures. The [threat identification chart](https://www.owasp.org/www-project-automated-threats-to-web-applications/assets/files/oat-ontology-decision-chart.pdf) helps to correctly identify the automated threat.

## Definition
### OWASP Automated Threat (OAT) Identity Number
OAT-002

### Threat Event Name
Token Cracking

### Summary Defining Characteristics
Mass enumeration of coupon numbers, voucher codes, discount tokens, etc.

### Indicative Diagram
<img alt="Indicative diagram for OAT-002" src="images/500px-OAT-002_Token_Cracking.png" style="background-color:#eeeeee;padding:1em;">

### Description
Identification of valid token codes providing some form of user benefit within the application. The benefit may be a cash alternative, a non-cash credit, a discount, or an opportunity such as access to a limited offer.

For cracking of usernames, see [OAT-007 Credential Cracking](OAT-007_Credential_Cracking.html) instead.

### Other Names and Examples
Coupon guessing; Voucher, gift card and discount enumeration

### See Also
* [OAT-007 Credential Cracking](OAT-007_Credential_Cracking.html)
* [OAT-011 Scraping](OAT-011_Scraping.html)
* [OAT-012 Cashing Out](OAT-012_Cashing_Out.html)

## Cross-References
### CAPEC Category / Attack Pattern IDs
* 112 Brute Force
* 210 Abuse Existing Functionality

### CWE Base / Class / Variant IDs
* 799 Improper Control of Interaction Frequency
* 837 Improper Enforcement of a Single, Unique Action

### WASC Threat IDs
* 11 Brute Force
* 21 Insufficient Anti-Automation
* 42 Abuse of Functionality

### OWASP Attack Category / Attack IDs
* Abuse of Functionality
* Brute Force Attack

<br/><br/>Return to [OWASP Automated Threats to Web Applications Project](../../../).<br/><br/>
