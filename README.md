[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/https://github.com/27410/27410-2020-group-project-group5_oxalic-acid_a-niger.git/main)

# 27410 - Group assignment - Group [5] - [Oxalic acid production with *Aspergillus niger*]


## Project summary

Nowadays, a lot of effort is put into replacing the old-fashioned chemical based production of chemicals with a more sustainable biotechnological process. Thus, oxalic acid, a chemical which is mainly applied for cleaning purposes, is chemically produced with extremely high temperatures of 360 °C and harsh chemicals like sulphuric acid, making the process unsustainable.  However, the main challenge of implementing biotechnological processes is to increase yield and productivity to be able to compete with the cheap costs of chemical synthesis.

In this report the fungus A. niger is computationally analyzed with the aim of improving the yield and productivity of oxalic acid synthesis. Thereby, special emphasis is put on assessing the change of media compositions and to perform different knockout strategies to improve oxalic acid synthesis. 
By changing the media composition, a favorable growth of A. niger and an improved flux towards oxalic acid for all identified pathways is observed when switching the carbon source medium from glucose to sucrose or lactose, where growth rate and oxalic production doubles and the flux of the two possible pathway reactions increase by 100% and 21%, respectively. There, sucrose and lactose are identified to show the same growth and flux of the target reaction. Moreover, the elements N and S are shown to be essential for the fungus and P being important but not essential. In contrast, H20, K and Ca are proven to be non essential for the growth of A.niger.

The performed knockouts target a sucrose-degrading enzyme and a glucose oxidase with the attempt to favor the flux towards the product. Surprisingly, neither the growth of the fungus nor the flux of the target reaction are affected by the knockouts, showing that those approaches are not successful. 
This points out that overexpression techniques might be more successful in that regard. Further research should be done to optimize the system.


## Project overview

Our project is structured as follows:

The main project can be read in 00_Report_Final.ipynb notebook. This notebook contains mainly all the written analysis of our project and includes some code in text. Our project model, iJB1325, can be found in Model_iJB1325_ATCC1015.xml file. An evaluation of iJB1325 model can be found in 01_MemoteReportModel iJB1325.pdf file.

Important files containing the designed code are linked to the main report for the Computer-Aided Cell Factory Engineering:

1. Maximum theoretical yields and Medium Characterization (02_Yield calculations CORRECT.ipynb)
2. Flux analysis (03_1_LactoseGrowthFlux.ipynb), (03_1_SucroseGrowthFlux.ipynb) and (03_GlucoseGrowthFlux.ipynb)
3. Knockouts (04_1_Oxaloacetate acetylhydrolase (r51) mutation.ipynb) and (04_Knockouts.ipynb)
4. Phenotypic phas plane (05_Phenotypic phas plane.ipynb)
5. Batch cultivations - dFBA (06_Batch simulation(dFBA).ipynb)




