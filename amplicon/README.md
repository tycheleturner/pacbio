Scripts for analyzing amplicon data post-ROI. This is in particular useful for CCS1 data where you have required a number of passes.

In order to run this analysis you'll need to fill out the config.json with the necessary information.

These are the components of the config.json

```
reference: This is should be the path to the reference genome for which you want to align your data.
data_dir: This is the path of the directory where your barcoded fastq files are located (they will take the form of something like this: lbc1--lbc1.fastq) 
minreadsize: This should be the size of your smallest amplicon minus a small amount (let's say 100 bp)
mazreadsize: This should be the size of your largest amplicon plus a small amount (let's say 100 bp)
picard: Put the path to your version of picard
bwamem: Put the path to your version of bwamem
```
