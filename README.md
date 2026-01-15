#Amplicon Sequencing
Scripts and workflows for 16S and variable length (18S, ITS) amplicon sequencing.

This repository contains scripts and workflows for processing amplicon sequencing data with DADA2 (16S, 18S, ITS) or QIIME2 (16S).

Important: There are different scripts and workflows for handling data from a single sequencing run vs doing combined analysis of data from multiple sequencing runs. Each sequencing run has distinct error patterns, so combining results runs results in error correction profiles that introduce more errors than you started with. 

The phylomicro script has tools for downstream visualization and biostatistical analysis. DADA2 output can be directly imported, but QIIME2 output will require a bit of reformatting. 

The R scripts contain several places where I say something has to be formatted a certain way. If you're comfortable changing the relevant R code, feel free to play around.
