# Separate Bombs from Firecrackers: Intention-guided Vulnerability Assessment via LLM


# Framework and workflow of VulStamp.
<img width="721" height="376" alt="image" src="https://github.com/user-attachments/assets/19f5bf59-cdb2-4ce5-85a8-83690ecda2bc" />


# COMPARISON OF DATASET PARTITIONING SCHEMES BETWEEN SVACL AND VULSTAMP
<img width="643" height="186" alt="image" src="https://github.com/user-attachments/assets/bf0a3101-d414-4966-b56d-739535f3bb65" />

# Please note that due to size limitations, our dataset can be downloaded from the following link: 
(https://drive.google.com/drive/folders/1h2VA4k08qaJ57MEXrztMGrQfM75aw7PI?usp=drive_link)


# Data Processing
Running dataprocessing/slice/process.py, we can obtain the CFG of the code snippet.

Running dataprocessing/slice/pdg.py, we can obtain the PDG of the code snippet.

Running dataprocessing/slice/PDG_slice.py, we can obtain the sliced_PDG of the code snippet.

# Exact Intention
Running dataprocessing/exact_intention/add_intention_gpt3.py, we can obtain the intention of the code snippet.

# Exact Suggestion
Running dataprocessing/exact_sug/oracle_extraction_gpt.py, we can obtain the repair suggestion of the code snippet.

# RQ1
The RQ1 folder contains the implementation of VulStamp and baselines.

# RQ2
The RQ2 folder contains the implementation details of the ablation experiment. When part of the content needs to be ablated, the corresponding part can be annotated.

# RQ3
