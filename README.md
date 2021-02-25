# ErrorRate
# Language: R
# Input: DIRECTORY
# Output: PREFIX
# Tested with: PluMA 1.1, R 4.0.0
# dada2_1.18.0

PluMA plugin to take a set of reads and compute error rates.

The plugin takes as input a directory that contains reads assumed to be in FASTQ format.

Several error measurements will be taken and output as CSV files that start with the user-specified output prefix.
R objects for forward and reverse errors will be output as prefix.forward.rds and prefix.reverse.rds
