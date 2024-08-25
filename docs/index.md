# Are we related to James Allan?

A project to trace the Alcrafts back to the infamous Northumbrian piper James Allan, and do a family tree in the process.


``` mermaid
flowchart TD  
JA1[John Alcraft\n1839-1903\nNewcastle UT-Newcastle UT] --> JAJA{Married\n1864};
JA2[Jane Allan\n1841-1883\nEglingham-Newcastle UT] --> JAJA;
ES[Ellen Smith\n1850-1939\nEdinburgh-Newcastle UT] --> JAES{Married\n1885};
JA1 --> JAES
JAJA -->D[Someone else];  

style JA1 fill:#90d5ff
click JA1 "jones" "JA2"

style JA2 fill:#FADADD
click JA2 "jones" "JA1"
style ES fill:#FADADD


```
