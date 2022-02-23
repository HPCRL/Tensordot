# Tensordot

[![DOI](https://zenodo.org/badge/38998367.svg)](https://zenodo.org/badge/latestdoi/38998367)

Code generator for tensor contraction



## how to use

For full search

```
./tdt.py input_file
```



## Input file format

入力ファイルは1行につき1つのテンソルを，以下の形式で定義します．

The input file defines one tensor per line in the following format.

```
tensor  テンソル名  ボンド名  ボンド名 …
```

```
tensor tensorname bond_name bond_name
```


次のような行を加えることで，ボンド次元が設定可能です．ボンド次元のデフォルト値は10です．

The bond dimension can be set by adding the following line. The default value for the bond dimension is 10.

```
bond_dim  次元数 ( Number of dimensions)  ボンド名 (Bond name)  …
```

その他のオプションについては (For other options) ，`example/input.dat`を参照して下さい (Please refer to) ．


# References

* R. N. C. Pfeifer, et al.: Phys. Rev. E 90, 033315 (2014)
