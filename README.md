# CARMEN-RVP analysis tool
CARMEN-RVP is a CRISPR/Cas13 based assay detecting 9 respiratory viruses. The readout is raw fluorescence data extracted from the Fluidigm RT-PCR software. The exported data can then be further analyzed with this tool. \

src folder:\
The main script for the analysis is called 'carmen_rvp_analysis.py'. The other scripts contain functions that will be imported during the analysis run.

img folder:\
Icons for graphical user interface.

archive-expertversion folder:\
For R&D use only. This contains an older version of the tool that provides the user with more flexibility on the input.

## Requirements
Python dependencies:
- pandas==1.0.5
- seaborn==0.10.1
- matplotlib==3.2.2
- Gooey==1.0.7
- numpy==1.18.5
- xlrd==1.1.0

Other things you should have:
- Fluidigm Biomark raw data file (.csv)
- Sample assignment sheet (.xlsx)

## Installation

Clone this github repository to always have the most up-to-date version. An executable version for Windows and Mac will be coming soon.

## Workflow

1. If you are using the command line, run the the main script with the following command:\
$ pythonw ./src/carmen_rvp_analysis.py
2. Choose an output prefix and an output directory
3. Upload the assignment sheet and the raw data file
4. Click start run.
