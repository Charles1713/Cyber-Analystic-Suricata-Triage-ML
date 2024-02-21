# Summary
This model in the current state takes transformed ip data from assert which takes alerts from suricata. The model will then compute the attacker and the attack stage of the attack campaign. The data is from sample data created from the ASSERT paper, source code for the paper: https://opensource.ieee.org/rit/assert/assert_plus.

# Creating the environment
create a new environment: conda env create --name project3 --file conda-environment.yaml
activate the environment: conda activate project
deactivate the environment (when you are done): conda deactivate

# API key for WANDB
You may need a wandb API key, this is free. This is an online logger. Create an account and find your key which you will enter on prompt.
