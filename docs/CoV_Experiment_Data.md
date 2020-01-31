We are releasing the following datasets from our big data platform. We are making our best effort to mine all experimental data of previous coronavirus related studies. If you have other specific data need or have datasets to contribute, please contact us @[**here**](https://github.com/GHDDI-AILab/Targeting2019-nCoV/issues). We will update our datasets periodically to provide more information to help your research combat the disease. 

### Annotated Set

* A collection of 1690 in vitro and in vivo records for 245 molecules     
    * [Full dataset](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/SARS_annotated_1690.csv)

### Unannotated Set

* A collection of 816 records for 479 molecules from various sources. We current don't have the capability to annotate the sources or confirm the correctness of all datasets. This dataset may contains missing values and "dirty" data. Please use the data carefully and make your own effort to confirm the data source (journals, patents, websites) and extract useful (signal) information from the set. Some datasets use standardlized value PX=-log[M].   
 
    * [Full dataset](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/AllAssay_coronavirus_all.csv)

* Some subsets extracted:

    * [*PX>6(measurement <1uM) active set*](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/AllAssay_coronavirus_active.csv)

    * [*IC50 values for 562 molecules*](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/coronavirus_IC50_for_562_molecules.csv)

    * [*Ki inhibition constant for 207 molecules*](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/coronavirus_Ki_inhibition_constant_for_207_molecules.csv)

    * [*Inhibition rate for 153 molecules*](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/coronavirus_inhibition_rate_for_153_molecules.csv)

    * [*EC50 values for 30 molecules*](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/coronavirus_EC50_for_30_molecules.csv)

    * [*pKi values for 14 molecules*](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/coronavirus_pKi_for_14_molecules.csv)

* SMILES of 986 molecules tested for coronavirus, but we are not sure if they are active or inactive
    * [SMIELS](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/AllAssay_coronavirus_986_SMILES.csv)

### Literature Mining

* A comprehensive literature mining result kindly provided by [Causaly](https://www.causaly.com), focusing on chemicals/drugs, genes and molecular mechanisms
    * [Full dataset](https://ghddiai.oss-cn-zhangjiakou.aliyuncs.com/file/Causaly-GHDDI_dataset.xlsx)

### Useful links
To check drug and compound related information   

* https://www.drugbank.ca    
* https://www.ebi.ac.uk/chembl/    
* http://zinc15.docking.org/substances/home/    
