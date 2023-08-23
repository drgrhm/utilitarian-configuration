# utilitarian-configuration

Code to reproduce experiments from the paper *Utilitarian Algorithm Configuration* (see paper [here](https://www.cs.ubc.ca/~drgraham/datasets.html)).

Download the data from [here](https://www.cs.ubc.ca/~drgraham/datasets.html).

Unpack it into a folder called icar/.

Set up directories: 
```
mkdir dat img
```

## Run Experiments: 

Runtime of Naive algorithm for different captimes (Figure 1)
```
python naive_captime_experiement.py cplex_rcw
```


Compare total time of Naive algorithm and UP... (Figures 2, 3)
```
python naive_captime_experiement.py cplex_rcw
```
