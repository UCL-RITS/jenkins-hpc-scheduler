jenkins-hpc-scheduler
=====================

Jenkins plugin for HPC job schedulers

The plan:

* Jobs currently queued in the batch system would show as pending jobs in the Jenkins UI.
* Jobs would be qsubbed when they are requested to be built
* Job would transition to currently running when it runs on the scheduler

Configuration for the scheduler-based slave would:

* Specify the commands to be used for job submission, termination and status monitoring
* with standard options for common queue systems
* SSH connection details to the login node of an HPC system.
