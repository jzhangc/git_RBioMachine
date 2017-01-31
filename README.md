# git_RBioFS
A simple to use package for implementing machine learning feature selection in biological and biochemical research


Installation

  - Install devtools (if not already done)
  
        install.package("devtools")
        
  - Install the package
        
        devtools::install_github("jzhangc/git_RBioFS/RBioFS", repos = BiocInstaller::biocinstallRepos())
        

Change log
  
  0.2.1 - 0.2.5
    
    - Bug fixes

  
  0.2.0
  
    - All-in-one FS function added
    - Bug fixes
    
  
  0.1.12
    
    - Bug fixes
  
  
  0.1.11
  
    - Output results as txt files functionality added
    
  
  0.1.10
  
    - Random Forest data imputation method added to the data imputation function
    - Round down now used for mtry augment
    
  
  0.1.9
  
    - Text fixes
    
  
  0.1.8
  
    - Name changed to RBioFS
    
  
  0.1.7
  
    - Bug fixes
    
  
  0.1.6
  
    - rbioRF_iterOOB() updated
    
  
  0.1.5
  
    - Iterative OOB error rate computation function added
    
  
  0.1.4
    
    - Initial FS function completed
    
  
  0.1.3
  
    - Parallel computing added for rbioRF_vi()
    
  
  0.1.2
  
    - rbioRF_vi and rbioRF_viplot functions combined to steramline the workflow
    
  
  0.1.1
    
    - Data imputation function added
    - File processing functions added
    
  
  0.1.0
  
    - Initial release
