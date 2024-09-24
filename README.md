# Summary
Cyber attacks happen very often and attackers can obfuscate their actions and stages of attacks. It is the job of cyber analysts to shift through IP data to figure out what the attackers did and what stage of their attack the data corresponds to, (using the MITRE Attack Stage Scale). This project seeks to automate the process by showing the attack stages in real-time. This model in its current state takes transformed IP data from Assert which takes alerts from suricata. The model will then compute the attacker and the attack stage of the attack campaign. The data is from sample data created from the ASSERT paper, source code for the paper: https://opensource.ieee.org/rit/assert/assert_plus. This model achieved a 93% accuracy rate.

# Further Improvements
If action is taken to improve the project, the model architecture should be changed to a GNN and the initial data collection should not rely on the Assert paper.

# Running
To run this for the first time, create a new environment then run each cell of the Triage_Notebook.ipynb

# Creating the environment
create a new environment: conda env create --name triage --file conda-environment.yaml
activate the environment: conda activate triage
deactivate the environment (when you are done): conda deactivate

# API key for WANDB
You may need a wandb API key, this is for a free online logger. Create an account and find your key which you will enter on prompt.
