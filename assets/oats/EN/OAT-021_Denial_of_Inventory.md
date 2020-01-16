---

layout: col-sidebar
title: OAT-021 Denial of Inventory
site_side: false
tags: oatsEN
project: true

---

**Denial of Inventory** is an automated threat. The OWASP Automated Threat Handbook - Web Applications ([pdf](https://github.com/OWASP/www-project-automated-threats-to-web-applications/tree/master/assets/files/EN), [print](http://www.lulu.com/shop/owasp-foundation/automated-threat-handbook/paperback/product-23540699.html)), an output of the [OWASP Automated Threats to Web Applications Project](../../../), provides a fuller guide to each threat, detection methods and countermeasures. The [threat identification chart](https://www2.owasp.org/www-project-automated-threats-to-web-applications/assets/files/oat-ontology-decision-chart.pdf) helps to correctly identify the automated threat.

## Definition
### OWASP Automated Threat (OAT) Identity Number
OAT-021

### Threat Event Name
Denial of Inventory

### Summary Defining Characteristics
Deplete goods or services stock without ever completing the purchase or committing to the transaction.

### Indicative Diagram
<img alt="Indicative diagram for OAT-021" src="images/500px-OAT-020_Denial_of_Inventory.png" style="background-color:#eeeeee;padding:1em;">

### Description
Selection and holding of items from a limited inventory or stock, but which are never actually bought, or paid for, or confirmed, such that other users are unable to buy/pay/confirm the items themselves. It differs from [OAT-005 Scalping](OAT-005_Scalping.html) in that the goods or services are never actually acquired by the attacker.

Denial of Inventory is most commonly thought of as taking ecommerce items out of circulation by adding many of them to a cart/basket; the attacker never actually proceeds to checkout to buy them but contributes to a possible stock-out condition. A variation of this automated threat event is making reservations (e.g. hotel rooms, restaurant tables, holiday bookings, flight seats), and/or click-and-collect without payment. But this exhaustion of inventory availability also occurs in other types of web application such as in the assignment of non-goods like service allocations, product rations, availability slots, queue positions, and budget apportionments.

If server resources are reduced see [OAT-015 Denial of Service](OAT-015_Denial_of_Service.html) instead. [OAT-005 Scalping](OAT-005_Scalping.html), Denial of Inventory also reduces the availability of goods or services.


### Other Names and Examples
Hoarding; Hold all attack; Inventory depletion; Inventory exhaustion; Stock exhaustion

### See Also
* [OAT-005 Scalping](OAT-005_Scalping.html)
* [OAT-013 Sniping](OAT-013_Sniping.html)
* [OAT-015 Denial of Service](OAT-015_Denial_of_Service.html)

## Cross-References
### CAPEC Category / Attack Pattern IDs
* 210 Abuse of Functionality

### CWE Base / Class / Variant IDs
* 799 Improper Control of Interaction Frequency
* 841 Improper Enforcement of Behavioral Workflow

### WASC Threat IDs
* 21 Insufficient Anti-Automation
* 42 Abuse of Functionality

### OWASP Attack Category / Attack IDs
* Abuse of Functionality

<br/><br/>Return to [OWASP Automated Threats to Web Applications Project](../../../).<br/><br/>
