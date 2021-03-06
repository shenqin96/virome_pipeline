﻿# Virome pipeline

Virome pipeline is a general pipeline constructed for viral metagenomes analysis from NGS read data. The pipeline integrates a series of open source tools, including STAR, MegaHit, BBmap, BLAST, ORFfinder and CAP3, which listed above are required when running the pipeline. In addition, Perl and R language environment are need to install and configure on the machine before running the pipeline.


## Usage

```bash
./Pipeline/virome_pipeline.sh /data/input /data/output sample_name sample_host /data/database /package
```

`./data/input`: path to input directory

`./data/output`: path to output directory

`./sample_name`: Used for directory name of sample

`./sample_host`: host type of sample, value = "Culicoides" or "Mosquito"

`./data/database`: Path to reference files and database files directory

`./package`: Path to bioinformatics tools directory

## Citation

Liu Lin, Shen Qin, Li Nan, He Yuwen, Pan Mei, Jin Yuting, Meng Jinxin, Wang Jinglin, Wu Aiping; Comparative viromes reveals the diversity, consistency and specificity of viral compositions in culicoides and mosquitos 
