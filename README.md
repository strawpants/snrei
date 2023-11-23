# SNREI
Holds various datasets for Spherically symmetric non-rotating Elastic Isotropic Earth models (SNREI).

## Love numbers 
In the directory ``Love`` you'll find ascii files with Love various Love numbers taken from the Literature (see citations in the data files themselves) 

A sqlite file containing all the data is provided as


The SQL file was generated using the [geoslurp client command](https://github.com/strawpants/geoslurp) 
```
geoslurper.py --export geoslurp_dump_llove.sql -d earthmodels.LLove
```


## Licensing
This repository is provides under the CC-BY-SA license, but please do credit/cite the papers where the data originate from

