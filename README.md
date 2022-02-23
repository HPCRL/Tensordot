# Tensordot

[![DOI](https://zenodo.org/badge/38998367.svg)](https://zenodo.org/badge/latestdoi/38998367)

Code generator for tensor contraction



## how to use

For full search

```
./tdt.py input_file
```



## Input file format



The input file defines one tensor per line in the following format.



```
tensor tensorname bond_name bond_name
```


The bond dimension can be set by adding the following line. The default value for the bond dimension is 10.

```
bond_dim ( Number of dimensions) (Bond name)  …
```

 For other options ，`example/input.dat` ．


# References

* R. N. C. Pfeifer, et al.: Phys. Rev. E 90, 033315 (2014)
