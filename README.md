# SLURM Cloud Bursting
## Example Scripts

The files in this repository will give you examples of what is need to get SLURM's Cloud Bursting feature working. They are heavily dependent on the (slurm_power_saving scripts)[https://github.com/jrwellshpc/slurm_power_saving].

This is a work in process.

Three links of interest:
1. [AWS](https://github.com/aws-samples/aws-plugin-for-slurm/tree/plugin-v2)
2. [Azure](https://github.com/Azure/cyclecloud-slurm)
3. [GCP](https://github.com/SchedMD/slurm-gcp)
4. [Jetstream](https://iujetstream.atlassian.net/wiki/spaces/JWT/pages/39682057/Using+the+Jetstream+API) Much more in the menu.

It may be useful to remember the sinfo codes:  
\*  The node is presently not responding and will not be allocated any new work. If the node remains non-responsive, it will be placed in the DOWN state (except in the case of COMPLETING, DRAINED, DRAINING, FAIL, FAILING nodes).  
\~  The node is presently in powered off.  
\#  The node is presently being powered up or configured.  
\!  The node is pending power down.  
\%  The node is presently being powered down.  
\$  The node is currently in a reservation with a flag value of "maintenance".  
\@  The node is pending reboot.  
\^  The node reboot was issued.  
\-  The node is planned by the backfill scheduler for a higher priority job.  

To Do:
1. Everything
