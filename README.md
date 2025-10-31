# straggler-free
This repository accompanies our ICDE'26 submission:  **“The End of Stragglers: Forging Load Balance in Sparse General Matrix-Matrix Multiplication through Contention-Aware Design”**.

## Dependencies
### install development packages
```
sudo apt install libnuma-dev libconfig-dev libpmem-dev
```

### install papi
install [papi](https://icl.utk.edu/papi/)

### install other tools
```
sudo apt intall parallel unzip gzip libreoffice python-is-python3 python3-pip graphviz
pip install --upgrade xlrd numpy pandas scipy scikit-learn matplotlib graphviz pydotplus  
```
note: scipy >= 1.13.1




## Quick Start
### Compile & Build
```
bash revitalize.sh
```

### Data Generation
```
cd scripts/20251005-scripts
bash gen_er.sh
bash gen_g500.sh
bash gen_ssca.sh
bash download_tamu.sh
bash parallel_tamu_refactor.sh
```

### Running SpGEMM
```
./bin/hashspgemm er_19_16
```

## Reproducing Experiments 
### General Instruction
Please visit the following folders, and run the scripts for reproducing the respective experiment. The plotting scripts are also included in these folders.


Experiments | Scritps
---|---
"Figure 1" | [20251021-scripts](scripts/20251021-scripts)
"Figure 3" | [20251020-scripts](scripts/20251020-scripts)
"Figure 4" | [20251019-scripts](scripts/20251019-scripts)
"Figure 5" | [20251017-scripts](scripts/20251017-scripts)
"Figure 7" | [20251018-scripts](scripts/20251018-scripts)
"Figure 8" | [20251014-scripts](scripts/20251014-scripts)
"Figure 9" | [20251011-scripts](scripts/20251011-scripts)
"Figure 10" | [20251015-scripts](scripts/20251015-scripts)
"Figure 11" | [20251012-scripts](scripts/20251012-scripts)
"Figure 12" | [20251016-scripts](scripts/20251016-scripts)
"Figure 13" | [20251013-scripts](scripts/20251013-scripts)


## Further Support
If you have any enquiries, please contact huangwentao@u.nus.edu(Huang Wentao) for the further support.


