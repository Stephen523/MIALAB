# Introduction

This is a program to calculate PSAIA of proteins and then predict the batch of possible binding sites of proteins.

# Data

This program needs pdb-format files of proteins, you can download them from [RCSB PDB: Homepage](https://www.rcsb.org/).

# Necessary Program

This program needs Naccess, you can download it if from http://www.bioinf.manchester.ac.uk/naccess/ and then put the directory named naccess2.1.1 in Program/.

To use Qcontacts in Program/, you need to install the corresponding dependencies : 

```
sudo apt-get install ia32-libs
```

or 

```
sudo apt-get install lib32ncurses5
```

After this, run the following order:

```
cd Program/Qcontacts
ldd Qcontacts
```

If you can see its dependencies, you can go on . If not, you need to check if the versions of the relevant libraries are correct.

# Run

Put pdb files of proteins in the folder named /data/pdb/.

Then run the following order to run:

```
bash main.sh
```

You can change the number of top patches in  sort_patch.sh

Then, you will get the results in the folder: /result/


# Contact

If you have any questions, please contact with: 13168zsl@ruc.edu.cn



