Tasks
=====

Tasks accepts matching jobs and performs actual heavy operations with the given payload from the job.

Tasks can return a result object or a new envelope containing a job. This envelope is then pushed on the queue and it's result will be returned to the tasks original return address.
