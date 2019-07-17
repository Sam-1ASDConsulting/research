# research
Contains jupyter python notebook projects for learning NLP concepts and prototyping HL7 data scrubbing and analysis ideas

DESCRIPTION:
------------
This is the README file describing protyping and research on reading HL7 ORU radiology report message files
to aggregate and create the original radiology report for a particular patient and analyzing the radiology
report using NLP techniques to discover any insights that can be leveraged for various healthcare use cases.

A few in mind are:
. Automated data scrubbing and verification for analhysis
. rad report analysis for claims coding assistance
. rad report analysis for diagnosis assitance

NOTE: this is still a work in progress


COMPONENTS:
-----------
NLP_Play_CPT_MRI.ipynb:
Jupyter Lab Notebook that contains logic for analyzing  the patient output report files from "RADORUSample.hl7" and
"RADAnalysisPrototype.ipynb" logic.

RADAnalysisPrototype.ipynb:
Jupyter Lab Notebook that contains logic for reading and loading the "RADORUSample.hl7" files into a pandas dataframe
for data format munging and aggregating to create 3 patient radiology reports to be used for NLP analysis by the
"NLP_Play_CPT_MRI.ipynb" notebook.

RADORUSample.hl7:
Contains 3 HL7 ORU messages. One for each patient and their radiology report.

README.md: 
This file.

sam_2018_cpt_radf.py:
Python dictionaires of 2018 CPT codes as keys and short descriptions as values. There is a dictionary for each
radiology modality. ie. CT, FLUORO, MAMMO, MRI,  NUCLEAR, PET, US, XRAY  

