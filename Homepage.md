---
title: Homepage
feed: show
notetype: feed
date: 24-04-2024
tags:
---
# Welcome
This website is part of a University of Calgary Educational Scholarship study to evaluate learning resources for medical students through anesthesia.

# Goal
The goal of this project is to provide condense, useful educational resources that can be used during anesthesia rotations and beyond. 

Several formats of resources exist, including clinical practice flowcharts, topic pocket cards, and a pharmacy section.

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```


```mermaid
graph TB
A[Patient Factors];
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