
**Here is a set of commands that you might want to have alias for in your .chrc file:**
------

**qalter commands:**
* To change the the priority of all your jobs (can only reduce the priority, cannot increase it):
  qalter -p <priority> -u \<username\>
* To change the priority of a specific job ID:
  qalter -p \<priority\> \<jobID\>
* To change the resource list of your jobs:
	* If your want to set the resource list by negation: qalter -l hostname=!"comp7.itaym.q@compute-7-1.local" -u \<username\>
	* Otherwise: 										 qalter -l hostname="comp7.itaym.q@compute-7-0.local" -u \<username\>


**module load commands:**
* To load R: module load R/R302
* To load python 3.4: module load python/anaconda3-4.0.0
* To allow multi-threaded jobs to run: module load rocks-openmpi
* To allow usage of MPI (multi-threaded that uses GPU rather than CPU): module load openmpi-x86_64
  
**Fun script from Haim that shows you the status of the queues:**
* perl /groups/pupko/haim/pupkoSVN/trunk/scripts/q.pl


<br /><br />


**Here is a a list of out nodes in Jekyl and Lecs2:**
------

**In Jekyl:** 
* compute-7-0 to 7-11
* compute-8-10 to 8-14

**In Lecs2:**
* compute-4-20 to 4-29
