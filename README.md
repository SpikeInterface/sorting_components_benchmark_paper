# Opening the black box: a modular approach to spike sorting

Here python scripts and jupyter notebooks to reproduces figures from the paper :

**Opening the black box: a modular approach to spike sorting**

https://elifesciences.org/reviewed-preprints/110588v1


Theses scripts and notebooks are good examples for using the internal benchmarks from
spikeinterface.


Figure 2 can be reproduce using:

  * `figure_dataset.ipynb`


Figure 3 can be reproduce using:

  * `detection_method.py` : run the script to create and compute the study
  * `detection_method.ipynb` : plot the results

Figure 4 can be reproduce using:

  * `clustering_drifting.py` : run the script to create and compute the study
  * `clustering_drifting.ipynb` : plot the results


Figure 5 can be reproduce using:

  * `matching_drift.py` : run the script to create and compute the study
  * `matching_drift.ipynb` : plot the results


Figure 6 can be reproduce using:

  * `matching_drift_aware.py` : run the script to create and compute the study
  * `matching_drift_aware.ipynb` : plot the results


Figure 7 can be reproduce using:

  * `sorters_simulation.py` : run the script to create and compute the study
  * `sorters_simulation.ipynb` : plot the results

Figure 8 can be reproduce using:

  * `cd notebooks/real_data_figure` : move to the folder where the environment is defined
  * `uv run sort_all_real_data.py` : Sort three datasets using four sorters
  * `uv run generate_curation_data.py` : Use UnitRefine, Bombcell and SLAy to curate the sorting output
  * `uv run make_drift_plots.py` : Make the drift and probe plots
  * `figure.tpy` : Generate the plot


Supplementary figure can be reproduce using::

  * `sorters_simulation_other_probes.py` : run the script to create and compute the study
  * `sorters_simulation_other_probes.ipynb` : plot the results


Additional scripts:

  * `slurm_tools.py` : custum machinery to run study in slurm
  * `dataset.py` : parameters to generate the datasets
  * `configuration.py` : local configuration (path, ...)


