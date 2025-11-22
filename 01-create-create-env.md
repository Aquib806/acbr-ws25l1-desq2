# Create Conda Enviroment with Miniconda


I am Creating a Conda enviroment for DESeq2 Data analysis  with R and Bioconductor in my windows System using Windows Subsystem Linux (WSL)

## Code in WSL terminal 
- Start the WSL in Windows 
- Type the following to create a conda enviroment for R4.5 names as R4.5WS


```{CMD}
conda create --name R4.5WS
```{CMD}
- Activate the R4.5WS conda enviroment as follows 
```
conda activate R4.5WS
```{CMD}
 - Install R4.5 in the R4.W5S conda enviroment
 ```
 conda install conda-forge::r-base
 ```
`conda-forge` is the channel from anaconda.org.[conda-forge/r-base 4.5.2](https://anaconda.org/conda-forge/r-base)





