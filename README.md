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
```

```

## Further Support
If you have any enquiries, please contact huangwentao@u.nus.edu(Huang Wentao) for the further support.


