# Are we related to James Allan?

A project to trace the Alcrafts back to the infamous Northumbrian piper James Allan, and do a family tree in the process.


``` mermaid
flowchart TD  
  A[Reasearch Software Good Practice] --> B{Processes};
  B -->|Beginner| C[Using version control];
  C --> D[Using virtual environments];
  D --> E[Writing clean, readable code];
  E --> F[Writing tests];
  B ---->|Intermediate| F;
  F --> G[Documenting the software];
  G --> H[Using continuous integration];
  H --> I[Using a package manager];
  I --> J[Using a code review process];
  J --> K[Is it FAIR?];
  B ---->|Advanced| K;
  A --> EB{Languages};
  EB --> |Python| PA[Python overview];
  PA --> PEP8[Python language standards];  
  PEP8 --> PINTRO1[Intro to python in person];
  PINTRO1 --- PINTRO2[Intro to python online];
  PINTRO1 --> STYLE[Better code: Type hints and linting];
  STYLE --> PC[A python package];
  PC --> PD[A python webapp];
  EB --> |R| RA[R language standards];
  RA --> RB[Intro to R];
  RB --> RC[An R package];
  RC --> RD[An R-shiny webapp];
  A --> TA{Tools};
  style A fill:#ff3399,stroke:#333,stroke-width:1px,color:#99ff99
  click A "https://icr-rse-group.github.io/good-practice/about/" "RS Good Practice"
  style PA fill:#ffcce6,stroke:#ff6600,stroke-width:1px,color:#33334d
  click PA "https://icr-rse-group.github.io/good-practice/good/python/" "Python Overview"
  style PEP8 fill:#bbf,stroke:#f66,stroke-width:1px,color:#33334d
  click PEP8 "https://peps.python.org/pep-0008/" "PEP8"
  style PINTRO1 fill:#ffff99,stroke:#ff6600,stroke-width:1px,color:#33334d
  click PINTRO1 "https://training.icr.ac.uk/coursed.php?course=544" "Intro to Python"
  style STYLE fill:#ffff99,stroke:#ff6600,stroke-width:1px,color:#33334d
  style PINTRO2 fill:#ffff99,stroke:#ff6600,stroke-width:1px,color:#33334d
  click PINTRO2 "https://training.icr.ac.uk/coursed.php?course=1189" "Intro to Python"
  style PC fill:#b3ffb3,stroke:#ff6600,stroke-width:1px,color:#33334d
  style PD fill:#b3ffb3,stroke:#ff6600,stroke-width:1px,color:#33334d
  style RA fill:#ffcce6,stroke:#ff6600,stroke-width:1px,color:#33334d
  style RB fill:#ffff99,stroke:#ff6600,stroke-width:1px,color:#33334d
  style RC fill:#b3ffb3,stroke:#ff6600,stroke-width:1px,color:#33334d
  style RD fill:#b3ffb3,stroke:#ff6600,stroke-width:1px,color:#33334d
  click EB "https://cran.r-project.org/web/packages/devtools/readme/README.html" "R packaging good practice"
```
