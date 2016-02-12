# The TIER Documentation Protocol v2.0 for STATA

## NOTE: THESE INSTRUCTIONS NEED TO REVIEWED TO MAKE SURE ALL 
## LANGUAGE IS STATA (NOT R) SPECIFIC

## Overview 

The TIER Documentation Protocol provides instructions for assembling a 
set of electronic files that document all the steps of data processing 
and analysis you conduct for an empirical research paper. 

The documentation specified by the Protocol contains all the data, 
computer programs, and explanatory information an independent researcher 
would need to be able to replicate the data processing and analysis you 
conducted for the project and to reproduce exactly all the results 
reported in your paper.

## ProjectTIER_STATA repository

The instructions presented in this repository are written for users of Stata. 
In a few places, they use Stata-specific terminology. For example, we refer to 
command files as do files, and their names are followed by the .do 
extension. But the Stata-specific terminology that appears in these 
instructions can be easily translated to any of the major statistical 
packages (such as SPSS, SAS, R, Matlab, etc.) or other programming 
languages.

## Getting started

To get started you can fork or clone this repository which will create 
a copy of the folder structure recommended in the Project TIER protocol
Below we describe how to organize your analysis according to the 
Project TIER protocol, i.e. which components of your analysis should go 
into which folder.

## Hierarchy and description of files and folders

Your repository should have the following hierarchy of files and folders:

- An electronic copy of your complete final paper
- The `README.md` file for your repository
- Original Data and Metadata - `original-data-and-metadata`
    + Original Data - `original-data`
    + Metadata - `metadata`
        - Metadata Guide - `metadata_guide.md`
        - Supplements - `supplements`
- Processing and Analysis - `processing-and-analysis`
    + Importable Data - `importable-data`
    + Command Files - `command-files`
    + Analysis Data - `analysis-data`

Contents of these files and folders are described in the `README` files
within these folders.

## README

The `README.md` file in the top hierarchy of your repository (this 
file) gives information about all the other files included in the 
documentation for your paper. In particular, the `README` file should:

1. state what statistical software or other computer programs are 
needed to run the command files.
1. explain the structure of the hierarchy of folders in which the 
documentation is stored, and briefly describe each of the files 
included in the documentation.
1. describe precisely any changes you made to your original data files 
to create the corresponding versions saved in your `importable-data` 
folder.
1. give explicit, step-by-step instructions for using your 
documentation to replicate the statistical results reported in your 
paper.

The README should be a Markdown document so that it can be 
rendered properly on GitHub, and any changes can be tracked. It should 
be named `README.md`. This file should be stored in the top level of 
your repository.