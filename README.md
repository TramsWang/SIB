# SIB
Sorted-integers-based index structure for data efficient logic rule mining

## 1. Compilation

All source code are included in `src/`. The source code for SIB and SInC locate in `src/sib` and `src/sinc` respectively. Please use `cmake` to compile the projects. A `CMakeLists.txt` is provided in each project. The path `src/sib-` is a variation of SIB that the $Match$ and $Join$ queries are trivially implemented instead of the ones with the divide-and-search strategy.

## 2. Datasets

All datasets are included in `datasets.7z`. `datasets/original` contains the original KBs (each in one corresponding directory, in the data format of [SInC](https://github.com/TramsWang/SInC)). `datasets/remapped` contains the KBs where the constants are mapped to integers via different strategies: alphabetical, frequency, and random.

