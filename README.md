# Prions Project

## ~~Romantic~~ Purpose of the project
The project was made by two students (Alessia Guadagnin Pattaro and Teresa Dalle Nogare) of University of Trento for the course "Multiscale methods in soft matter physics", held by professor Raffaello Potestio in the Master's degrees in Physics, and Quantitative and Computational Biology - Physical track. We decided to focus on prions because Alessia was intrigued by their bizarre behaviour and because Teresa wanted to do something related to neurobiology. For the first weeks we saw the participation of another student but he eventually decided to do a project on his own.

The aim of our project was to explore the prion protein and its misfolding pathway by means of molecular dynamics simulations. It is necessary to say that neither one of us had taken a course on MD so we did an extensive literature research along with many trial errors that could have been avoided. We immediately recognized that our aim was too ambitious for both our knowledge and for the computational resources that we had at the time. This though didn't stop us and we got very deeply involved in prions biophysics and biochemistry. We did the exam in October 2022, whilst we started another course focused on MD and trajectory analysis and this motivated us to revise the whole project by performing again the simulations and the subsequent analyses. 

This project does not yield any relevant results but it has been highly pedagogical and methodological for us to learn how to do research on unknown topics on our own, without direct or constant supervision. 

## Structure of the repository
This repository, as of February 2023, is comprehensive only of the first version of the project (folder `v.1.0`). The folder reports
* the final report and the presentation
* `structures` folder, with the two chimeras CHI1 and CHI2 and the building blocks (the misfolded base PrPSc, 1FKC PrPc, and the AlphaFold generated PrPc)
* `jupyter-notebooks` folder, with all the analyses notebook
To keep the repository lightweighted, the trajectory files are not reported.

## Project v1.0 abstract
The structural characterization of prions represents a challenging task, both from an experimental and computational point of view. The aim of this project is to investigate the change in secondary structure of two "hand-made" chimeras, called CHI1 and CHI2, exploiting molecular dynamics simulations.

Firstly, an all-atom simulation of 1 ns was performed for both chimeras. Subsequently, two different coarse-grained methods, namely G\=o model and Martini 3 were used to coarse grain the initial structures and perform longer MD simulations. 
An analysis exploiting structural parameters such as the radius of gyration, RMSD and RMSF was performed in order to understand the differences in behaviour between the two structures, but also the effect of temperature on the process of unfolding.

Overall, no particularly significant results were found concerning the folding process itself. However, some considerations were made on the role of coarse graining in the study of the protein folding process.

