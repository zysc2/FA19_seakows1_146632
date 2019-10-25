# FA19_seakows1_146632
QIIME
#!/bin/sh
#
#SBATCH --JOB-name=QIIME2_single
#SBATCH --nstaks=5
#SBATCH --cpus-per-task=1
#SBATCH --partition=lrgmem
#SBATCH --mem-per-cpu=20G
mkdir qiime2-moving-pictures-tutorial
cd qiime2-moving-pictures-tutorial
mkdir emp-single-end-sequences
 -O "emp-single-end-sequences/barcodes.fastq.gz" \"https://data.qiime2.org/2018.8/tutorials/moving-pictures/emp-single-end-sequences/barcodes.fastq.gz"
 
