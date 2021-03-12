# DriverFuse-0.1.0
Analysis of next generation sequencing datasets for driver fusion gene prediction



DriverFuse aims to become instrumental in the study of Driver fusion genes in cancer
genomics, enabling the identification of recurrent complex rearrangements that may pinpoint
disease driver events. Here,we implement the methodological framework into an R package 
incorporating multiple functionalities to integrate orthogonal data types such as SV and CNV and 
characterize fusion gene in breast cancer datasets.This toolset allows the research community to 
easily perform complex analysis of high throughput profiling data and will support extensions to 
further integrate analyses of other types of omics data.




## input_svc 
'input_svc' creates input structural varaint file for a user sample data that is used for mapping 
fusion gene to find out whether it is "Driver" or "Passenger" fusion gene.


## input_cnv
'input_cnv' creates input copy number variation file for a user sample data that is used for mapping 
fusion gene to find out out whether it is "Driver" or "Passenger" fusion gene.


## Driver_result

'Driver_result' function classifies input fusion gene into "Driver" or "Passenger" fusion gene based 
on mapping coordinates in structural variant and copy number variation.


## Driver_object

'Driver_obj' creates object of input fusion gene based on their mapping structural variant and copy number variation.


## Driver_correlation_coefficient

It plots the correlation coefficient between mapping structural variant and copy number variation profile 
for a given input fusion gene.


## Driver_plot

‘Driver_fusion_plot’ function plots mapping structural variants and CNV profile
for input fusion transcripts. It plots the CNV profile and structural variants 
that are mapping to genomic coordinates of input fusion genes.


## Driver_domain
‘Driver-domain’ provides genomic feature annotation tools for driver fusion
gene. Exploring domain level landscape of fusion gene is important to identify 
gene role in cancer progresssion.

