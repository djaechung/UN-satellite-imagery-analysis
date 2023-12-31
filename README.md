# UN-satellite-imagery-analysis
Contains the work of a 2022 research colaboration between MIT and the United Nations Office for Project Services (UNOPS) to develop identification algorithms for Colombian satellite imagery. One team worked on human settlement detection algorithms while another team worked on road and land cover detection algorithms. 

This repository is a public copy of the original private repository. It contains the code for both teams' algorithms but only contains evaluation plots for the road and land cover models. All satellite imagery used in this project is confidential and is excluded from this public version of the repository. All satellite imagery used in report documents has also been redacted.

This work is important because it allows the United Nations to conduct further research into the effects of ordinance removal projects on human developement within Colombia. Human development is measured by the very settlements, roads, and reduction in land cover that our models detect, making our algorithms a critical foundation for future analyses. Notably, our road and land cover models achieve 0.93 AUC and 0.99 accuracy on a per-pixel classification basis. We are pleased to report that this project won 2nd out of 21 teams at the MIT Analytics Lab showcase in 2022!

Contents:
* `Data` - satellite imagery used to train and test our models. We unfortunately cannot disclose these files in this public repository because of confidentiality
* `Models` - code for our algorithms for detecting human settlements, roads, and land cover in satellite imagery
* `Results` - plots comparing performance for the road identification models only
* `Project_Presentation.pdf` - contains the presentation slidedeck for this project, with confidential satellite imagery redacted
* `Project_Report.pdf` - contains the written report for this project, with confidential satellite imagery redacted

Road and Land Cover Detection Team:
> Daniel Chung `Daniel Chung` <br /> Zehao (Andy) Zhou

Human Settlement Detection Team:
> Shurui (Sherry) Cao <br /> Xinyao Han
