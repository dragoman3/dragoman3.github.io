---
title: Post-operative Nausea and Vomiting
notetype: feed
feed: show
category: clerk
tags:
  - clerkship
date: 17-10-2022
mermaid: true
---

# General Principles
- Many patients undergoing anesthesia will experience post-operative nausea and vomiting
- Anti-emetic medications are given routinely during anesthesia. 
- Combining agents of different classes reduces side effects and improves anti-emetic action

# Clinical Pathway

```mermaid
graph TB
A["`**Patient Factors**
-Female
-Hx of PONV
-Non-smoker
-Post-op Opioids`"];
B["`**Surgical Factors**
-Laparoscopy 
-Cholecystectomy
-Gynecologic Surgery
-Strabismus`"];
N[Nausea Risk];
AN["`**Anesthetic Technique**
-TIVA
-Regional`"];
M["`**Medications** 
-5-HT3 Antagonists
-Steroids
-Anti-psychotics
-NK inhibitors
-Dopaminergic Agents`"];
RM["`**Rescue Medications**`"];




subgraph Pre-operative
A -->N
B-->N
end
subgraph Intra-operative
N-->AN
N-->M
end
subgraph Recovery
AN --> RM
M--> RM
end
```

```mermaid
graph LR
A["`**Apfel Score**`"];
B1["`**1-2 Risk Factors**`"];
B2["`**3-4 Risk Factors**`"];
C1["`**2 Antiemetics**`"];
C2["`**3-4 Antiemetics**`"];

A --> B1
A --> B2
B1 --> C1
B2 --> C2

```





# Risk Factors for Nausea
## Patient Risk Factors -- Apfel Score [^1]
- Female
- Non-smoker
- history of PONV/motion sickness
- post-operative opioids

| Apfel Score Points | Risk of PONV |
|--------------------|--------------|
| 0                  | 10%          |
| 1                  | 20%          |
| 2                  | 40%          |
| 3                  | 60%          |
| 4                  | 80%          |

## Surgical Risk Factors
- Cholecystectomy
- laparoscopic
- gynecologic

## Anesthetic Risk Factors
 - Duration of anesthesia
 - use of volatile anesthetics / nitrous oxide

# Medications to Prevent PONV

## 5-HT<sub>3</sub> Antagonists
[[Ondansetron]]

## Antidopaminergics
[[Haloperidol]]
[[Metoclopromide]]

## NK1 Receptor Antagonists
[[Aprepitant]]

## Corticosteroids
[[Dexamethasone]]



[^1]:  [[Tong J. Gan, Kumar G. Belani, Sergio Bergese, Frances Chung, Pierre Diemunsch, Ashraf S. Habib, Zhaosheng Jin, Anthony L. Kovac, Tricia A. Meyer, Richard D. Urman, Christian C. Apfel, Sabry Ayad, Linda Beagley, Keith Candiotti, Marina Englesakis, Traci L. Hedrick, Peter Kranke, Samuel Lee, Daniel Lipman, Harold S. Minkowitz, John Morton, Beverly K. Philip. 2020. Fourth Consensus Guidelines for the Management of Postoperative Nausea and Vomiting . 411-448]]
[^2]:
[^3]:
[^4]: