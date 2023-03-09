# Models and Tree Decomposition

### Update as of 9 March 2023

To perform tree decomposition over a .sdf file, run

```
python mol_tree.py -f sdf -o ../data/all.txt
```

To perform tree decomposition over a .txt file of SMILES, run
```
python mol_tree.py -f txt -o ../data/all.txt
```

### Previous method:

To perform tree decomposition over a set of molecules, run
```
python mol_tree.py < ../data/all.txt
```
This gives you the vocabulary of all cluster labels over the entire dataset.
