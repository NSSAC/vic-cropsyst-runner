# VIC-CropSyst Runner Framework

This framework aids in running the VIC-CropSyst framework in an high performance computing environment (HPC). It also supports modification of forcing input parameters to perform parameter scanning and sensitivity analyses.

The sim runner framework operates in several steps,
- Change forcing variables
- Setup input files
- Submit and monitor SLURM jobs
- Post-process output data

These components are described below,
