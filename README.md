#AGTAR is a python package to identify and quantify transcripts from RNA-seq data.

#####Requirement#####

AGTAR is suitable for Linux systems, and requires python>=2.7 (we tested AGTAR based on the Redhat6.8 system environment, python2.7.13).If the result file mapping reads to genome is in bam format, you need to install SAMtools to convert bam files to sam files.

#####Installation#####

#Unzip the downloaded installation package

unzip AGTAR-main.zip

#If the AGTAR folder is located at /opt/biosoft/AGTAR-main, then execute the following command:

echo 'PATH=$PATH:/opt/biosoft/AGTAR-mainr/bin/' >> ~/.bashrc

source ~/.bashrc

#####Documentation#####

#Executing the software with the parameter -h can list all the options and the corresponding meanings:

AGTAR -h

#For more details about installation and use, please refer to User_Guide_AGTAR.html


