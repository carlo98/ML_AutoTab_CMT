# Learning When to Use Automatic Tabulation in Constraint Model Reformulation
This repository contains the problem classes, instances, dataset and machine learning (ML) models used for the paper: "Learning When to Use Automatic Tabulation in Constraint Model Reformulation".

# Table of contents
1. [Organization](#organization)

## Organization <a name="organization"></a>
The repository is organized as follows: 
- The instances of each problem class are grouped in a folder, along with problem's model.
- 'Generators' contains a few python and bash scripts used to generate the instances of some of the problem classes.
- 'Dataset' contains the results obtained by solving the instances with different solvers, i.e. minion, kissat, kissat-mdd and chuffed, as csv files. In the same folder are also available the instances' features (folder 'on-off-feature-instances') and the results obtained for the second task.
- 'ML_logs' should contain the results obtained when training a few ML models on the dataset (use the python script provided in the "Code" folder).
- 'Code' contains the code used by us to train the models and to study the results.

## Citation
@inproceedings{cena2023learning,
  title={Learning When to Use Automatic Tabulation in Constraint Model Reformulation},
  author={Cena, Carlo and Akg{\"u}n, {\"O}zg{\"u}r and Kiziltan, Zeynep and Miguel, Ian James and Nightingale, Peter and Ulrich-Oltean, Felix},
  booktitle={Proceedings of the 32nd International Joint Conference on Artificial Intelligence},
  year={2023},
  organization={IJCAI/AAAI}
}
