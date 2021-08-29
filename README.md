# Dock_for_LOX-MODEL_PhD_Work
Microsoft Windows [Version 10.0.19041.985]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Ebhohimen I E>cd C:\Guide to Lipoxygenase\LOX_BHT_Docking

C:\Guide to Lipoxygenase\LOX_BHT_Docking>vina.exe --config conf.txt --log log.txt
#################################################################
# If you used AutoDock Vina in your work, please cite:          #
#                                                               #
# O. Trott, A. J. Olson,                                        #
# AutoDock Vina: improving the speed and accuracy of docking    #
# with a new scoring function, efficient optimization and       #
# multithreading, Journal of Computational Chemistry 31 (2010)  #
# 455-461                                                       #
#                                                               #
# DOI 10.1002/jcc.21334                                         #
#                                                               #
# Please see http://vina.scripps.edu for more information.      #
#################################################################

WARNING: The search space volume > 27000 Angstrom^3 (See FAQ)
Detected 4 CPUs
Reading input ... done.
Setting up the scoring function ... done.
Analyzing the binding site ... done.
Using random seed: -1515861120
Performing search ...
0%   10   20   30   40   50   60   70   80   90   100%
|----|----|----|----|----|----|----|----|----|----|
***************************************************
done.
Refining results ... done.

mode |   affinity | dist from best mode
     | (kcal/mol) | rmsd l.b.| rmsd u.b.
-----+------------+----------+----------
   1         -5.6      0.000      0.000
   2         -5.6      0.030      4.609
   3         -5.5     31.648     34.689
   4         -5.4     31.668     34.925
   5         -5.4     24.667     26.642
   6         -5.3     24.675     26.544
   7         -5.3     31.103     33.503
   8         -5.3     31.393     34.398
   9         -5.3      1.830      2.066
Writing output ... done.

C:\Guide to Lipoxygenase\LOX_BHT_Docking>vina_split.exe --input BHT_out.pdbqt
Prefix for ligands will be BHT_out_ligand_
Prefix for flexible side chains will be BHT_out_flex_

C:\Guide to Lipoxygenase\LOX_BHT_Docking>cd C:\Guide to Lipoxygenase\LOX_Carv_Docking

C:\Guide to Lipoxygenase\LOX_Carv_Docking>vina.exe --config conf.txt --log log.txt
#################################################################
# If you used AutoDock Vina in your work, please cite:          #
#                                                               #
# O. Trott, A. J. Olson,                                        #
# AutoDock Vina: improving the speed and accuracy of docking    #
# with a new scoring function, efficient optimization and       #
# multithreading, Journal of Computational Chemistry 31 (2010)  #
# 455-461                                                       #
#                                                               #
# DOI 10.1002/jcc.21334                                         #
#                                                               #
# Please see http://vina.scripps.edu for more information.      #
#################################################################

WARNING: The search space volume > 27000 Angstrom^3 (See FAQ)
Detected 4 CPUs
Reading input ... done.
Setting up the scoring function ... done.
Analyzing the binding site ... done.
Using random seed: 1522680192
Performing search ...
0%   10   20   30   40   50   60   70   80   90   100%
|----|----|----|----|----|----|----|----|----|----|
***************************************************
done.
Refining results ... done.

mode |   affinity | dist from best mode
     | (kcal/mol) | rmsd l.b.| rmsd u.b.
-----+------------+----------+----------
   1         -6.9      0.000      0.000
   2         -6.5     22.390     22.984
   3         -5.9     22.563     24.448
   4         -5.8     21.810     22.985
   5         -5.7     11.045     12.556
   6         -5.7      1.726      4.159
   7         -5.6     23.550     25.520
   8         -5.6     24.219     25.836
   9         -5.5     24.351     25.886
Writing output ... done.

C:\Guide to Lipoxygenase\LOX_Carv_Docking>vina_split.exe --input Carvacrol_out.pdbqt
Prefix for ligands will be Carvacrol_out_ligand_
Prefix for flexible side chains will be Carvacrol_out_flex_

C:\Guide to Lipoxygenase\LOX_Carv_Docking>cd C:\Guide to Lipoxygenase\Model_BHT_Docking

C:\Guide to Lipoxygenase\Model_BHT_Docking>vina.exe --config conf.txt --log log.txt
#################################################################
# If you used AutoDock Vina in your work, please cite:          #
#                                                               #
# O. Trott, A. J. Olson,                                        #
# AutoDock Vina: improving the speed and accuracy of docking    #
# with a new scoring function, efficient optimization and       #
# multithreading, Journal of Computational Chemistry 31 (2010)  #
# 455-461                                                       #
#                                                               #
# DOI 10.1002/jcc.21334                                         #
#                                                               #
# Please see http://vina.scripps.edu for more information.      #
#################################################################

WARNING: The search space volume > 27000 Angstrom^3 (See FAQ)
Detected 4 CPUs
Reading input ... done.
Setting up the scoring function ... done.
Analyzing the binding site ... done.
Using random seed: -1556447016
Performing search ...
0%   10   20   30   40   50   60   70   80   90   100%
|----|----|----|----|----|----|----|----|----|----|
***************************************************
done.
Refining results ... done.

mode |   affinity | dist from best mode
     | (kcal/mol) | rmsd l.b.| rmsd u.b.
-----+------------+----------+----------
   1         -5.6      0.000      0.000
   2         -5.6      0.012      4.608
   3         -5.4     31.779     34.827
   4         -5.4     31.818     35.062
   5         -5.4     24.706     26.669
   6         -5.4     24.723     26.579
   7         -5.4     31.721     33.987
   8         -5.3     31.757     33.936
   9         -5.3     31.200     34.398
Writing output ... done.

C:\Guide to Lipoxygenase\Model_BHT_Docking>vina_split.exe --input BHT_out.pdbqt
Prefix for ligands will be BHT_out_ligand_
Prefix for flexible side chains will be BHT_out_flex_

C:\Guide to Lipoxygenase\Model_BHT_Docking>cd C:\Guide to Lipoxygenase\Model_Carv_Docking

C:\Guide to Lipoxygenase\Model_Carv_Docking>vina.exe --config conf.txt --log log.txt
#################################################################
# If you used AutoDock Vina in your work, please cite:          #
#                                                               #
# O. Trott, A. J. Olson,                                        #
# AutoDock Vina: improving the speed and accuracy of docking    #
# with a new scoring function, efficient optimization and       #
# multithreading, Journal of Computational Chemistry 31 (2010)  #
# 455-461                                                       #
#                                                               #
# DOI 10.1002/jcc.21334                                         #
#                                                               #
# Please see http://vina.scripps.edu for more information.      #
#################################################################

WARNING: The search space volume > 27000 Angstrom^3 (See FAQ)
Detected 4 CPUs
Reading input ... done.
Setting up the scoring function ... done.
Analyzing the binding site ... done.
Using random seed: -657612188
Performing search ...
0%   10   20   30   40   50   60   70   80   90   100%
|----|----|----|----|----|----|----|----|----|----|
***************************************************
done.
Refining results ... done.

mode |   affinity | dist from best mode
     | (kcal/mol) | rmsd l.b.| rmsd u.b.
-----+------------+----------+----------
   1         -6.7      0.000      0.000
   2         -6.7      1.401      2.017
   3         -5.8     22.685     24.959
   4         -5.8      1.315      4.202
   5         -5.6     11.077     12.571
   6         -5.5     33.453     34.646
   7         -5.5     23.894     25.869
   8         -5.5     24.378     25.840
   9         -5.4     25.221     26.377
Writing output ... done.

C:\Guide to Lipoxygenase\Model_Carv_Docking>vina_split.exe --input Carvacrol_out.pdbqt
Prefix for ligands will be Carvacrol_out_ligand_
Prefix for flexible side chains will be Carvacrol_out_flex_

C:\Guide to Lipoxygenase\Model_Carv_Docking>
