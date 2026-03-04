# dtc COP

*description of the COP*

**COP timeframe** 2026-02-18 - 2026-05-27

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/dtc](https://cra-proto.github.io/dtc)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-03-04

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Tax credits and benefits for individuals)
    node4(Disability tax credit #40;DTC#41;)
    node5(Disability tax credit #40;DTC#41;<br>CRA's review and decision)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes/child-and-family-benefits.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/segments/tax-credits-deductions-persons-disabilities/disability-tax-credit.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/tax/individuals/segments/tax-credits-deductions-persons-disabilities/disability-tax-credit/review-decision-dtc.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5 inscope
```
