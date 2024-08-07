---
title: Test Page
feed: show
notetype: feed
date:  21-03-2023
category: clerk
tags: pocketcard
mermaid: true
---

The following topics are taken from the Anesthesia Clerkship Core Documents. The following collection can serve as memory aids for some key topics, but does not include an exhaustive overview.

### Intra-operative Monitoring
### Fluid Management
### Physiology
### Pharmacology
### Airway Mechanical Skills
### Ventilation Management
### Pain Management
[[Pain Management]]
### Pre-operative Evaluation
[[Airway Assessment Pocket Card]]
### Post-operative Management

jjjj
Testers

```mermaid
flowchart TB
%%{init: {"flowchart": {"htmlLabels": false}} }%%
A["`**Patient** Factors
- Female Sex
- Non-smoker`"];
B[Surgical Factors];
N[Nausea Risk];
AN[Anesthetic Technique];
M[Medications];
RM[Rescue Medications];
subgraph pre-op
A -->N
B-->N
end
subgraph intra-op
N-->AN
N-->M
end
subgraph PACU
AN --> RM
M--> RM
end
```


```mermaid
graph LR
%%{init: {"flowchart": {"htmlLabels": false}} }%%
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
AN[Anesthetic Technique];
M[Medications];
RM[Rescue Medications];




subgraph Pre-operative
A -->N
B-->N
end
subgraph intra-op
N-->AN
N-->M
end
subgraph PACU
AN --> RM
M--> RM
end
```