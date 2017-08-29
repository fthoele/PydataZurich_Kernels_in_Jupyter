# Kernel in Jupyter
This repo contains the slides and python code for my talk on kernel in Jupyter for PyData Zurich.

To install a new kernel:
```
jupyter kernelspec install <folder-name>
```

To run a jupyter console with this kernel, make sure that python can load the kernel module (for quick-and-dirty testing, go to the directory with the source files).
```
jupyter console --kernel character_count_kernel
```
