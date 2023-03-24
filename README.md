# veritas
Veritas automation

I intend to fix veritas VCS issues automatically by using this script

Checking veritas products installed. 

checkProductVersion.

if cluster 
Cluster operations 
- Cluster not starting
  - Check Modules(checkVCSModules - Check RPMs)
  - Check VCS variables(checkVCSVariables)
  - Check Services(checkVCSServices)
  - Check VCS files(checkVCSFiles)
  - Check gabconfig and llt status
  
Service group and Resources Operations
- Check faulty SGs(checkSGsStatus)
  Check faulty Resources(checkResourceStatus)- Check faulty Resources and their dependencies.
  Note: if a SG is failing to come online is because one or more dependencies are not coming up.
  
