# visualization-gallery
Gathering the outputs from different repositories for cool visualizations such as 3D reconstructions, heatmaps and many more.


```mermaid
%%{init: {
  "theme": "default",
  "themeVariables": {
    "primaryColor": "#226e93",
    "edgeLabelBackground":"#eef7fa",
    "fontFamily": "Montserrat",
    "nodeTextColor": "#ffffff"
  }
}}%%

mindmap
  root((QA Mindmap)):::root

    Bugs:::bugs
      Analysis:::sub
        Root Cause Analysis
        High-risk defects
      Behavior:::sub
        Intermittent issues
        Environment-specific issues

    Testing:::testing
      Manual:::branch
        Functional
        Exploratory
      Automation:::branch
        UI
        API
        Performance

    Tools:::tools
      Jira
      Selenium
      Postman
      JMeter

classDef root fill:#226e93,stroke:#0e3d56,color:#ffffff,font-size:20px;
classDef bugs fill:#37a65b,stroke:#1c7c40,color:#fff;
classDef testing fill:#085408,stroke:#063b2f,color:#fff;
classDef tools fill:#5c3fa3,stroke:#3a2a6f,color:#fff;

classDef branch fill:#9ad1e3,stroke:#226e93,color:#000;
classDef sub fill:#c7e7ef,stroke:#226e93,color:#000;
