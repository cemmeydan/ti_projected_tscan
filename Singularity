#######################################################################################
## DO NOT EDIT THIS FILE! This file was automatically generated from the dockerfile. ##
## Run dynwrap:::.container_dockerfile_to_singularityrecipe() to update this file.   ##
#######################################################################################

Bootstrap: shub

From: dynverse/dynwrap:bioc

%labels
    version 0.1.0

%post
    R -e 'devtools::install_cran("TSCAN")'

%files
    . /code

%runscript
    exec Rscript /code/run.R

