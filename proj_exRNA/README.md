## HCC and healthy plasma cell-free exRNA-seq generated by lulab
---

**Dateset**: plasma cell-free exRNA-seq generated by lulab

**Location**: /BioII/lulab_b/shared/projects/exRNA/

**Date**: Apr 15, 2018

**Maintainer**: Siqi Wang

 **Description**: 
* Plasma samples were collected from HCC patients (before/after surgery) and normal people.
* 00.rawdata/: R1.fastq and R2.fastq files.
* 01.cutadapt/: Remove adapter and trim low quality base from end of each reads by cutadapt toolkit. The 51-150 nt of R1 reads were forced trimed from 3`end.
* 02.rRNA/: Remove ribosomal RNA reads by bowtie2.
* 03.mapping/: bam files generated from bowtie2. Maping order: miRNA, piRNA, Y RNA, snRNA, srpRNA, tRNA, lncRNA, mRNA, human genome.

|Project|Table Name|Notes|Google Sheet|Local tsv|Person|Update date|
|-|-|-|-|-|-|-|
|exRNA|RNA-seq|human|[metatable](https://docs.google.com/spreadsheets/d/1tEtVWOiUa0dU5kYtyTPkLEGvYUavR7HMhLNZhkXh6q8/edit#gid=1491251054)|/BioII/lulab_b/shared/projects/exRNA/|Siqi Wang|2018.4.15|
|Lulab HCC cell-free|RNA-seq|human|[metatable](https://docs.google.com/spreadsheets/d/1tEtVWOiUa0dU5kYtyTPkLEGvYUavR7HMhLNZhkXh6q8/edit#gid=1491251054)|/BioII/lulab_b/shared/projects/exRNA/ hcc_lulab/metatable|Siqi Wang|2018.4.15|
|Lulab HCC exosome|RNA-seq|human|[metatable](https://docs.google.com/spreadsheets/d/1tEtVWOiUa0dU5kYtyTPkLEGvYUavR7HMhLNZhkXh6q8/edit#gid=1491251054)|/BioII/lulab_b/shared/projects/exRNA/ exosome_lulab/metatable|Siqi Wang|2018.4.15|
---
 **Metatable**:
* Sample_ID: the patient sample were named as xxxxx-B (before surgery) and xxxxx-A (after surgery), respectively
* Sex: M / F
* Age: Age by sampling time
* Tumor_size(cm): size of HCC tumor
* Multiple_tumor: Yes / No
* Vascular_invasion: Yes / No
* Satellite_nonules: Yes / No
* AFP(ng/ml): AFP protein marker examination result
* CEA: CEA protein marker examination result
* ALT(U/L): ALT protein marker examination result
* AST: AST protein marker examination result
* ALB: ALB protein marker examination result
* PT: PT protein marker examination result
* Stage-BCLC: the development stage of HCC, from level A to C
* RNA.mass.ng: the quality of used RNA
* Batch: batch number and sequencign date
* spike-in: number of spike-in sequence(1-cel-mir39, 5-cel-mir39 and 4 lulab sythesis RNA sequences)

> Shared by Siqi Wang

> Email: zzuwsq@163.com