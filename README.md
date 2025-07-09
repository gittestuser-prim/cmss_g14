# CMSS_group_14

This is a little data analysis Project based on a wikipedia communication dataset(https://zenodo.org/records/49561)

## Description
This is a python notebook which provides different visualisations as well as a consent building model based on the mesa libraries with a lot of different hyperparameters for you to play with.
We first spend some time to explore all asspects of the dataset before building a model to run our consent simulation.
Please be aware that we have 41k agents and so a run can take a while (1hour+ on my current hardware) so please be patient.
We also save runs into pkl files for later use. You can rewrite this part in the last section if you need to. (Just add all custom pkl files you generated into the list)

Hpyerparameters:
	model_agents: Number of agents in the network (this is taken from the dataset)
	active_df: Time-sorted edge network, currently not on use for this task
	max_time: length of simulation in time-sorted sims, currently not in use
	trust: This is a multiplier to strengthen opinions of people we corresponded with 
	meeting_size: Size of meetings to build a new consensus for the agent
	meeting_chance: Chance for a meeting to happen, this exists mainly to speed up the simulation
	run_length: How many rounds we try to build consensus
	UDG: undirected graph to gain neighbors we trust



## Installation
Please see the requriements files or import all libraries with the Framework of your choice. The program itself is a python jupyter notebook. Please make sure that all datafiles are in the same directory!

## Usage
Just start the file and enjoy.


