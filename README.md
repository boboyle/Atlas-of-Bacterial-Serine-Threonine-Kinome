<!-- This github was Made by Brady O'Boyle --> 

# Atlas of the Bacterial Serine/Threonine Kinome

  

## Introduction   

  

   


  

   

  

This repository contains the data and code used in the manuscript "Atlas of the Bacterial Serine/Threonine Kinome". To reproduce the results from the paper, download the data and Jupyter Notebook directories and follow the instructions in the notebooks to run them locally.
</br> 

   

## Quick overview of the dependencies 

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![git-LFS](https://img.shields.io/badge/Git%20LFS-white?style=for-the-badge&logo=Git%20LFS&logoColor=red)
![Biopython](https://img.shields.io/badge/Biopython-6495ED.svg?style=for-the-badge&logo=Biopython&logoColor=black) 

![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) 
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) 
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) 

  

   

</br> 

  

  

## Included in this repository are the following:   

  

   


- `Data`: ipynb file with code used to process sequence data following BPPS analysis

    - `a3m_files`: sequences from each bacterial STK family in a3m format

    - `fasta_files`: sequences from each bacterial STK family in fasta format

    - `bSTK_constraints.con`: file containing the constraint patterns and weights associated with each of the STK families

    - `bSTK_FastTree_InputSeq.fasta`: sequence file used as input for phylogenetic analysis using FastTree

    - `bSTK_domains.csv`: file containing the domains associated with each of the STK families

    - `nr220614_bSTK.cdd`: file containing the domain data from the Conserved Domain Database for each bacterial STK sequence

    - `nr220614_bSTK.tmhmm`: ile containing the transmembrane data from TMHMM for each bacterial STK sequence


- `Juypter Notebooks`: ipynb files with code used to process and analyze data

  

    - `BPPS_github.ipynb`: ipynb file with code used to process sequence data following BPPS analysis 
    
      
    
    - `AnalyzingSeq.ipynb`: ipynb file with code used to analyze sequence data  
    
      
    
    - `Domain_Transmembrane_Analysis.ipynb`: ipynb file with code used for domain and transmembrane analysis  

- `README.md`: 


</br> 

  


  

    

  

## Installing dependencies with version info    

  

  

### From conda:    

  

![python=3.11.5](https://img.shields.io/badge/Python-3.9.16-green)  

  

![jupyterlab=3.6.3](https://img.shields.io/badge/jupyterlab-4.0.0-blue)  

  


  

   

  

### From pip:  

  

   

  

![numpy=1.24.3](https://img.shields.io/badge/numpy-1.24.3-blue)  

  

![pandas=2.0.3](https://img.shields.io/badge/pandas-2.0.3-blue)  

  

![matplotlib=3.7.2](https://img.shields.io/badge/matplotlib-3.7.2-blue)  

  

![scikit-learn=1.3.0](https://img.shields.io/badge/scikitlearn-1.3.0-blue)  

  

![biopython=1.81](https://img.shields.io/badge/biopython-1.81-blue) 
  

### HelperBunny 

  

HelperBunny is used for comparative sequence analysis and has been included in the jupyter_notebooks directory for convenience. More information can be found here https://github.com/waylandy/HelperBunny.


### Git LFS 

  

Due to the large size of the files, Git Large File Storage (Git LFS) is required to clone the repository. Installation steps can be found below. More information can be found here https://git-lfs.com/.
  

</br> 


  

   

  

## Downloading this repository   

  
1. Download Git LFS
```   
sudo apt install git-lfs
```   

2. Install Git LFS
```   
git lfs install
```     

3. Clone the repository to your local computer (this may take a moment)
```   
git clone https://github.com/boboyle/Atlas-of-Bacterial-Serine-Threonine-Kinome
``` 

4. Navigate into the cloned directory
```   
cd Atlas-of-Bacterial-Serine-Threonine-Kinome
``` 
  
5. Unzip data, Jupyter notebook and HelperBunny folders (this also may take a moment)
```   
unzip data.zip
unzip jupyter_notebooks.zip
cd jupyter_notebooks
unzip HelperBunny.zip
```

6. Open Jupyter lab
```   
jupyter lab
``` 

7. Start analyzing data!
