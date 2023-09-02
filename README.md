# HPML-KAIS
Repository for the Journal Paper "Multi-Label Classification with Label Clusters"

## How to cite this repository

## RESULTS

### Resulting Files

Here you can download the generated partitions, best selected partitions and the results from our experiments. If you want to get these for your experiments since the beginning, then please check the source code section.

**Generated Partitions**

- [10 Folds Cross Validation](https://1drv.ms/f/s!Aq6SGcf6js1m6-B08FI4WPdLPDtdkQ?e=Ijz6dt)
- [All Possible Partitions (Bell Number)](https://1drv.ms/f/s!Aq6SGcf6js1m6-ETm236_Bju4YMjgw?e=wBwzbX)
- [HPML-J](https://1drv.ms/f/s!Aq6SGcf6js1m6-B2rrDsWL8OSwngrQ?e=vGj2tb)
- [HPML-K](https://1drv.ms/f/s!Aq6SGcf6js1m6-B__DDUWcmmChKt_Q?e=GOiLUK)
- [Random 1](https://1drv.ms/f/s!Aq6SGcf6js1m6-FBMGd-u3ndwfgiBA?e=LiZCMP)
- [Random 2](https://1drv.ms/f/s!Aq6SGcf6js1m6-FCBXhuUkS9n8GImw?e=pXOBJe) 
- [Random 3](https://1drv.ms/f/s!Aq6SGcf6js1m7P41pcNLwmHJAUWG2g?e=zstXSw)


**Best Selected Partitions**

- [Oracle](https://1drv.ms/f/s!Aq6SGcf6js1m6-E7-G4u8QbWvOyaYQ?e=lskQ6a)

- *Exhaustive*: [Macro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-EoId5BXS8Mt3HgUw?e=tWrYOt) | [Micro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-EnT2HV6DN1W1NiMw?e=ebLpMO)

- *HPML-J*: [Macro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-EaVAzfj6hOoDvqfA?e=2w9gQp) | [Micro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-Eb19W3q1vMZHs3IQ?e=dmj67U) | [Silhouette](https://1drv.ms/f/s!Aq6SGcf6js1m6-EcOcU1F5h6b4XSDg?e=xGy2Wt)

- *HPML-K*: [Macro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-Ed4L_kp3PxE-kMmA?e=jl59bY) | [Micro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-Ee8pe_XwIKdgD9eA?e=i4hHuS) | [Silhouette](https://1drv.ms/f/s!Aq6SGcf6js1m6-EfBakMcYZeWPGXHw?e=uMgH9p)

- *Random-1*: [Macro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-EgPP48Xo--NrlANw?e=TK9G39) | [Micro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-EhuRev41tVVXRyFA?e=qldux9) | [Silhouette](https://1drv.ms/f/s!Aq6SGcf6js1m6-EicqyByYG2gbONGg?e=ZFtV8x)

- *Random-2*: [Macro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-Ej1VJbGUJx97MClw?e=fRzZ4f) | [Micro-F1](https://1drv.ms/f/s!Aq6SGcf6js1m6-EkdHHPlruE-12Ujg?e=etIs9n) | [Silhouette](https://1drv.ms/f/s!Aq6SGcf6js1m6-ElaRlxjeUuFzH-dw?e=rrKcB5)
  
-  *[Local-Partitions](https://1drv.ms/f/s!Aq6SGcf6js1m7P01XT9LbbGDzax0Ww?e=Xc1U2M)*
  
-   *[Global-Partitions](https://1drv.ms/f/s!Aq6SGcf6js1m7P00Gp5zxVR1xUQi0Q?e=nHw0W4)*


### Analysis

Here you will find all the documents (tables, plots, etc.) with analysis of the results.

- [Performance](https://1drv.ms/b/s!Aq6SGcf6js1m7P5HufzJIoEvmZUrGg?e=DTzFL5)

- [Win-Loss-Tie](https://1drv.ms/f/s!Aq6SGcf6js1m7P5LbvNpbOJC98Diqw?e=6iQT3p)

- [Method-Pair-Comparison](https://1drv.ms/f/s!Aq6SGcf6js1m7P5Oos4NRUHKqz4-JQ?e=iN83dh)

- [Statistical Tests](https://1drv.ms/f/s!Aq6SGcf6js1m7P5MqnImJY2gao69dA?e=6NLbjm)

- [Partitioning](https://1drv.ms/b/s!Aq6SGcf6js1m7P5GKY8MigODG6pE1A?e=Up23Yk)



## INSTRUCTIONS TO REPRODUCE THE EXPERIMENTS

### Enviroments to run experiments

#### Conda
You can run this experiment in a Conda Environment. The name of our conda environment is "AmbienteTeste". To be able to use this env, you must first install conda in your computer or cluster and then install the env using the following command: *conda env create --file AmbienteTeste.yaml*. Click [here](https://drive.google.com/drive/folders/1OGwZi8gPuoUF_DIshz7XsGIUurmQgKXe?usp=sharing) to download the files.


#### Singularity/AppTainer
You can also run this experiment in a singularity container. We do not provide a singularity container for this experiment, but you can build one. [Here](https://rpubs.com/cissagatto/apptainer-slurm-r) you can find a little tutorial about how to do that for our experiments. Using singularity is better than conda environments when you have to execute all the experiment in a tmp (scratch or dev/shm) folder. 

Pay attention to this because sometimes using the conda environment directly from the */home* can destroy hard disks and harm all users. In some situations, copying your singularity container to the server's temp folder and running absolutely everything from there is the best solution for everyone. Talk to the administrator about this before trying to reproduce the experiments.


### SOURCE CODE
Our code is completely modular because of our servers - mainly job queue, time, and memory. In this way, we can run many jobs in parallel in different steps of the methodology. In the future, a package that executes all the flow will be developed and available for the scientific community. 

In each source code, you will find instructions about how to run the code. You also can make adjustments in the main script to save the results in your machine or in your cloud using rclone (there are some examples in the R scripts).

Attention: before using rclone, check with your institution's network administrator if it is possible to upload files and folders from the cluster to the cloud. In case of using google accounts for universities, you need to follow specific steps to configure communication between google cloud and server.

- [Bell Partitions](https://github.com/cissagatto/BellPartitionsMultiLabel)

- [Cross-Validation](https://github.com/cissagatto/CrossValidationMultiLabel)

- [Local Partitions](https://github.com/cissagatto/Local-Partitions)

- [Global Partitions](https://github.com/cissagatto/Global-Partitions)

- [Oracle Partitions](https://github.com/cissagatto/Oracle-Clus)

- Exhaustive Partitions: [Micro-F1](https://github.com/cissagatto/Exhaustive-MiF1-Clus) | [Macro-F1](https://github.com/cissagatto/Exhaustive-MaF1-Clus)

- Hybrid Partitions

-- *Generate Partitions*: [Jaccard](https://github.com/cissagatto/Generate-Partitions-Jaccard) | [Kohonen](https://github.com/cissagatto/Generate-Partitions-Kohonen)

-- *Select Best Partition*: [Macro-F1](https://github.com/cissagatto/Best-Partition-MaF1-Clus) | [Micro-F1](https://github.com/cissagatto/Best-Partition-MiF1-Clus) | [Silhouette](https://github.com/cissagatto/Best-Partition-Silhouete) | [Kohonen Macro-F1](https://github.com/cissagatto/Best-Partition-Kohonen-MaF1-Clus) | [Kohonen Micro-F1](https://github.com/cissagatto/Best-Partition-Kohonen-MiF1-Clus)

-- *Test Best Partition*: [Macro-F1](https://github.com/cissagatto/Test-Best-Partition-MaF1-Clus) | [Micro-F1](https://github.com/cissagatto/Test-Best-Partition-MiF1-Clus) | [Silhouette](https://github.com/cissagatto/Test-Best-Partition-Silhouete)

- Random Partitions

-- *Generate Partitions*: [Random Partitions Version 1](https://github.com/cissagatto/Generate-Partitions-Random1) | [Random Partitions Version 2](https://github.com/cissagatto/Generate-Partitions-Random2) | [Random Partitions Version 3](https://github.com/cissagatto/Generate-Partitions-Random3)

-- *Select Best Partition*: [Macro-F1](https://github.com/cissagatto/Best-Partition-MacroF1) | [Micro-F1](https://github.com/cissagatto/Best-Partition-MicroF1) | [Silhouette](https://github.com/cissagatto/Best-Partition-Silhouete) | [Kohonen Macro-F1](https://github.com/cissagatto/Best-Partition-Kohonen-MaF1-Clus) | [Kohonen Micro-F1](https://github.com/cissagatto/Best-Partition-Kohonen-MiF1-Clus) 

-- *Test Best Partition*: [Macro-F1](https://github.com/cissagatto/Test-Best-Partition-MaF1-Clus) | [Micro-F1](https://github.com/cissagatto/Test-Best-Partition-MiF1-Clus) | [Silhouette](https://github.com/cissagatto/Test-Best-Partition-Silhouete) 

-- [Random 3](https://github.com/cissagatto/Random3-Clus)


## Acknowledgment
This study is financed in part by the Coordenação de Aperfeiçoamento de Pessoal de Nível Superior - Brasil (CAPES) - Finance Code 001


## Links

| [Site](https://sites.google.com/view/professor-cissa-gatto) | [Post-Graduate Program in Computer Science](http://ppgcc.dc.ufscar.br/pt-br) | [Computer Department](https://site.dc.ufscar.br/) |  [Biomal](http://www.biomal.ufscar.br/) | [CNPQ](https://www.gov.br/cnpq/pt-br) | [Ku Leuven](https://kulak.kuleuven.be/) | [Embarcados](https://www.embarcados.com.br/author/cissa/) | [Read Prensa](https://prensa.li/@cissa.gatto/) | [Linkedin Company](https://www.linkedin.com/company/27241216) | [Linkedin Profile](https://www.linkedin.com/in/elainececiliagatto/) | [Instagram](https://www.instagram.com/cissagatto) | [Facebook](https://www.facebook.com/cissagatto) | [Twitter](https://twitter.com/cissagatto) | [Twitch](https://www.twitch.tv/cissagatto) | [Youtube](https://www.youtube.com/CissaGatto) |

## Report Error
Please contact me: elainececiliagatto@gmail.com

# Thanks
