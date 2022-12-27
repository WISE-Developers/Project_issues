
# W.I.S.E. (Wildfire Intelligence and Simulation Engine) - Formerly known as PSaaS (Promethues Software as a Service)
![WISE social image](wiserepo.png)
This repository is the primary project management repo and is used to catch all bugs, tasks and Feature requests as well as website feeback.


## Component Status

[### WISE Builder:](https://github.com/WISE-Developers/WISE_Builder_Component) [![Maven Package](https://github.com/WISE-Developers/WISE_Builder_Component/actions/workflows/maven-publish.yml/badge.svg)](https://github.com/WISE-Developers/WISE_Builder_Component/actions/workflows/maven-publish.yml)



## Project Information

- Project Website: [FireGrowthModel.ca](https://firegrowthmodel.ca/pages/wise_overview_e.html)
- Project Licence: [Affero General Public License Version 3+](https://www.gnu.org/licenses/agpl-3.0.en.html)
- API and MQTT Documentation: [Current API Docs](https://firegrowthmodel.ca/pages/wise_documentation_e.html)
- Project Support Info: [GitHub & Discord etc](https://firegrowthmodel.ca/pages/wise_support_e.html)
- Source Code: Source Code is not yet released (Source will be available to all when the Project Releases v1.0)
- Public Release: Targeting a public release of WISE and End-of-life Prometheus by end of the 2022 calendar year.
- Project Timeline: 
  - 1999 Promethues Fire Growth Model was born
  - 2003 Franco Meets Rob & Cordy at a prometheus course - initial discusions about automation
  - 2007 Franco takes the promethues course again Meets Neal & Brett - Further discusions about automation ideas
  - 2010 Franco does a poster display of an Automated Prometheus Concept at kitchener Wildfire Canada Conference
  - 2012 Franco, Kris and Neal present the REDApp Concept at Kananaskis Wildfire Canada Conference
  - 2014 
    - Franco and Rob Talk out the idea of Automated Prometheus into a viable project Idea
    - Franco and Neal Secure the required legal permissions to proceed
    - GNWT (Franco) Contracted HSS to build a Prometheus SaaS Prototype aka Prometheus SaaS V.0
    - Prototype deployed operationally at Government of the Northwest Teritorries (GNWT)
    - Integrated into the SPARCS decision support system.
    - Comprehensive review with GNWT 
    - GNWT goes all in, and commits to build 1.0 
    - GNWT agrees to provides annual funding to the project
    - The Project is born
    - Franco, Neal et al. go on tour drumming up support for the idea of moving all projects to SaaS 
  - 2015 began syncronizing codebases of Prometheus, REDApp, Burn-P3 and Prometheus SaaS
  - 2016 Began preparing REDApp to be open source
  - 2017 
    - Setup redmine, PSaaS and REDApp Websites
    - NZ comes on board, 
    - Franco and Neal try and establish the CIFFC Toolbox , 
    - develop project workplan
    - Franco Creates a national modelling system using DIP and PSaaS
    - PSaaS Models BC Wildfires. PSaaS has modelled > 10,000 fires in 2017 (NWT and BC combined).
    - PRototype Web GUIs Developed using the PHP API
    - First Official Collaborative Development Teleconference
      - NWT (Partner)
      - Alberta (Partner)
      - New Zealand (Partner)
      - Heartland Software Solutions (Contractor)
      - Ember Research Services (Contractor)
    - Franco went to Ontario for Meetings and Discussed PSaaS with teh Director
    - Ontario Aproached the TEam about Partnership and Jordan Evans Came on board
    - PSaaS GOA/NT Contribution Agreement Established
  - 2018
    - MQTT Adopted as communication protocol
    - PSaaS 6 and 7 diverge as we move to cross platform
    - Javascript API is developed
    - Code begins to move to online repositories at bitbucket
    - CIFFC Toolbox initiative stalls out again - no help for the project
    - Redmine is upgraded and new workflows are developed
    - Documentation (JS API Etc) Goes online
    - Government of Canada (CFS/NRCAN) makes verbal commitment to come on board.
    - PSaaS now encompases 
      – Prometheus - EOL
      – REDapp
      – BurnP3
      – Pandora
    - Project forges ahead with PSaaS 7 (Linux)
    - NWT Javascript PSaaS GUI Models its first fire
    - AB (Brett Moore) Ran its first model using the Javascript API
    - PSaaS 6.2.3.7 is released to developers and NWT has it growing fires in SPARCS
    - PSaaS 6 and 7 start to diverge in perimiter comparison due to rounding issues
    - PSaaS 6.2.4.3 is released to developers and NWT has it growing fires in SPARCS
  - 2019
    - REDapp and Prometheus 6.2.4 released
    - DEB and RPM installers for PSaaS version 7.2.4.9 released to developers
    - PSaaS Begins to evolve towards multithreading and distributed computing.
    - Adoption of GDAL as input oputput middleware - ensures standards
    - Further development of the FGMJ File Format.
    - PSaaS 6.2.5.2 Passes Smoke tests - Released to Developers
    - PSaaS 7.2.5.3 Passes Smoke Tests on primary distros (Some distros fail)
    - Franco Succesfully Integrates PSaaS into Node Red - Node Red Runs a PSaaS Model.
    - DND Adopts PSaaS as Fire Modelling Engine for the ER2 Platform
    - Alberta hosts a PSaaS Workshop in Edmonton
    - New Zealand Sucessfully Containerizes PSaaS in Docker
    - Saskatchewan comes on board as a project partner, Rob Kruus joins the team!
    - Proof-of-concept app  "Drop a match" Devloped using leaflet, PSaaS and Node-Red
    - JAVA API Planned
    - NWT Develps the .net API to help Burn-P3 move forward. 
    - PSaaS 6.2.5.5 Passes Smoke tests - Released to Developers
    - New JS API functions:
      - execute job remotely (API-Client)
      - collect results (API-Client)
      - process results (postprocessing-scripts)
    - Developed new workplan
    - PHP API Deprecated
  - 2020
    - NWT Develops new PSaaS Docker Containers
    - Prometheus and PSaaS 6.2.5.6 released to devs
    - Finnish Meteorological Institute (FMI) comes on board and begins testing PSaaS
    - Redapp moves to bitbucket
    - Franco and Brett Develop a dataset cutter using NodeJS and R and GDAL
    - PSaaS 7.2.5.6 for Ubuntu 20.04 released to devs
    - Formal validation work of 6 against 7 begins.
    - PSaaS and REDApp Discord Communities came online.
    - redmine content reorganized into projects
    - Brett Moore moves from GOA to CFS
    - The Canadian Fire Growth Modelling Framework Project was born 
    - Franco and Brett Propose Radical chages to the project Governance and Management
      - All code to github
      - Repo/Branch structure
      - SOPs
      - Github used for Project management
      - Discord Communities
      - Website Update
  - 2021
    - ER2 Project Spawns FireHawk - Web Based Fire Modelling (Using the engine (PSaaS))
    - CFS discussions on using the engine for the New Burn-P3
    - NWT Builds the DIP Modelling Service and Models all wildfires in the DIP all season long
    - LUX/Aerobot - begins discussions of using the engine.
    - Brett and Franco begin visioning on a new Exective to run the project
    - Neal moves from GOA to BC
    - Log4J causes widespread panic in the fire modellign community.
      - Project puts out a white paper on log4j via CIFFC      
    - Heartland Software give birth to FireCast Realime Wilsfire modelling powered by PSaaS
    - Franco and Brett build a new GDAL only cutter service in docker
  - 2022
    - NWT privately contracts HSS to Automate builds of REDAppLib, REDApp, HSS_Java, WTime, HSS_Math.
    - Alberta privately contracts HSS to deliver new log4j safe binaries
    - Project releases Log4j safe versions (2022.03.01) of all our applications.
    - PSaaS Name chosen - Wildfire Intelligence and Simulation Engine (W.I.S.E)
    - Project begins meeting exclusivly in Discord
    - Sub Scenarios added to the Engine
    - Alberta/NWT/Yukon Collaborate on a contract to HSS to run firecast
    - Assets and Critical Paths added to the Engine
    - Add optional compression for MQTT file streaming
    - NWT rewrites its DIP modeller and hosts it for the CFS over the season
    - NWT Models all fires operationally using 2 templates, SGP and 3day
    - NWT Launches Automated pre-Generation of Updated Fire Model Simulation Landscapes for every fire.
    - NWT Integrates FireCast Outputs into its IntelliFire Decision Support System.
    - Forsite - begins discussions of using the engine.
    - CFS deploys its own version of the CFS DIP on Hybrid Solution (Backend at CFS and Front End on AWS)
    - New SOP developed on access to the software before release.
    - AGPLv3 Chosen as the licence
    - Brett begins foundational work on "State of the Project Report"
    - Team declines to present at Wildland Fire Conference 2022 opts for Wildfire Canda Presentation in Nov.
    - Project Adopts ZenHub tools to imporve project management on Github.
    - 

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

[Our code of conduct](https://firegrowthmodel.ca/pages/conduct.html)
