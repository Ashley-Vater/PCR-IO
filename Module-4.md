---
layout: default
title: Module 4. Expand your power with PyRosetta
nav_order: 5
---


*Welcome to the [PyRosetta](https://drive.google.com/drive/folders/1g7Z3WEAR3zlAfs61uB69RxErcogGr6mG?usp=sharing) module. Here students will be 1. becoming familiar with python and pyrosetta coding and 2. Redesigning miniprotein binders against new spike variants using pyrosetta. Here students are expected to be working out of a shared Google Drive: this is how the modules are built and the notebooks run. Don’t hesitate to reach out if you might like to set a google drive up for your class or group ([Ashley Vater](mailto:awvater@ucdavis.edu)).*

[4.1 PyRosetta 101](https://docs.google.com/presentation/d/16HD8nx2e0Ns7MiO1u7keNHstc2hp2qM1IInxhtLZXB4/edit?usp=sharing)
This slide deck describes: Pyrosetta as an interface, basics of Rosetta, poses, residues, score function, movers, navigating PyRosetta. Author: [Meerit Said](mailto:mys3@uw.edu). An additional resource that student may find complementary and helpful is [Pose Basics Python coding](https://drive.google.com/file/d/1Izcrh4yB40yaSXkRgGWfXEcfZpfmKknm/view?usp=sharing) with Andrew Leaver-Fay.

[4.2 FastDesign reading guide ](https://docs.google.com/document/d/1TbYugq8YZwh1-eU_j3HWfbky1oudhTR6dWKgONgmG7s/edit?usp=sharing)
This reading guide supports students in exploring [Hosseinzadeh 2017 methods](https://science.sciencemag.org/content/sci/suppl/2017/12/14/358.6369.1461.DC1/aap7577-Hosseinzadeh-SM.pdf) paper. The FastDesign protocol/method will be a primary function of the workflow in the PyRosetta Module. Author: [Meerit Said](mailto:mys3@uw.edu).

[4.3 Designing with PyRosetta](https://docs.google.com/presentation/d/1CT21qx7S-Cs2yH5P9DJSvv9AlQqR4rgV9ewLQpTsZxM/edit?usp=sharing)
This slide deck asks students to consider the research problem of redesigning Cao et al 2020 miniprotein binders to better fit SARS-CoV2 variants of concern and merges new content on FastDesign features to design in this system. Author: [Meerit Said](mailto:mys3@uw.edu).

[4.4 Initializing Your Notebook with PyRosetta](https://colab.research.google.com/drive/1Qn5kSLubFtuhAE-4rQ8u-glWxFP5mC4_?usp=sharing)
This Google Colab notebook runs scripts that install PyRosetta just a little bit of PyRosetta on a student’s google drive. The initialization adds a folder “prefix” to the students google drive but beyond a little crosstalk between this folder and the notebooks, most of the compute runs on Johns Hopkins servers. Students do not need to do a complicated and time consuming download of PyRosetta; however, they will need to register for a license through Comotion at UW. The details and links are in the notebook. The second half of the notebook (mover set up) is optional and not necessary for this workflow but can make for a cool add-on. 

[4.5 Guide: using FastDesign to compare and optimize your binder designs](https://docs.google.com/document/d/1gGxb0n19pei4D5D_cJToknriLmmrSYomn1GW6t2SpQc/edit?usp=sharing)
This guide assumes that students have made a redesign in Foldit and want to explore it further in PyRosetta. The guide references the three notebooks below.

[4.6 mutating Foldit hand-designed binder with FastDesign](https://colab.research.google.com/drive/1D93SYtxMj3gDO0ER-LSUfMv63rqneHnG?usp=sharing)
In this notebook, students will (1) import the binder redesigns (in complex with the appropriate viral variant spike receptor binding domain) that they made in Foldit Standalone, (2) adapt the script to mutate around their redesigns, (3) run FastDesign on residues at the binder-RBD interface. These mutations should complement students' earlier work in Foldit. Author: [Meerit Said](mailto:mys3@uw.edu).

[4.7 Use FastDesign to mutate at will: see what happens](https://colab.research.google.com/drive/1YuNlnGFYhZX5fuMYgoeoYgUAnP7cqm11?usp=sharing)
In this notebook, students will run the original binders in complex with viral beta and gamma variant spike receptor binding domains as a comparison, to see if their human intuition in Foldit was supported or conflicts against FastDesign’s predictions. Author: [Meerit Said](mailto:mys3@uw.edu).

[4.8 Just for fun: AlphaFold](https://colab.research.google.com/drive/1cND2sVRac37qBrKtuWJem6ECn1_g_e6m?usp=sharing)
Here students will be prompted to input their designs in amino acid sequence format and run AlphaFold to generate a predicted model. Students are encouraged to align their Foldit and Rosetta predictions with AlphaFolds to look for similarities and differences.
