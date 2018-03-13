The output of the different ipython files can be seen at 
https://github.com/mschrimpf/9.S52-Emergent-Computations-within-Distributed-Neural-Circuits.

# Run locally
Set up environment
```bash
conda env create -f environment.yml
conda activate 9.S52-pset1
```

Run jupyter notebook
```bash
jupyter notebook --notebook-dir=. > jupyter.log 2>&1 &
```
Retrieve the notebook url/token using e.g. `cat jupyter.log`.
