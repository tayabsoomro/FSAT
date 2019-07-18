
===============================================================================
- FSAT -- FASTA & SAM Analysis Tool                                           -
-                                                                             -
- Author: Tayab Soomro
- Agriculture & Agri-Food Canada, SRDC                                                       -
- 09/06/2019                                                                  -
===============================================================================

CHANGELOG
=========

June, 2019
    - Initial release with following tools: fastaparse, samtocsv

INTRODUCTION
============

FSAT is a utility to for interogating SAM and FASTA files and extract important
information from those files. This program was generated to aid the genome 
assembly and annotation of Plasmodiophora Brasscae, which was sequenced using
Oxford Nanopore's MinION DNA Sequencer.

Although most of the modules created are specific to my project, there are tools
in this sofware suite that can be used for any type of analysis involving SAM
and FASTA files.

USAGE
===== 

The FSAT program currently supports 2 modules, each of which are described below.

Modules:
    samtocsv -- Outputs various analysis in CSV format for comparison of 
                Newbler assembly with Flye assembly.
    fastaparse -- Contains various tools for interogating multi-FASTA file.

Main program usage
$ fsat {module}

ACKNOWLEDGMENT
==============

The genome assembly and annotation project was performed at Agriculture &
Agri-Food Canada under the supervision of Dr. Hossein Borhan. I was hired as a
FSWEP (Federal Student Work Experience Program) student.

(c) Tayab Soomro, 2019



