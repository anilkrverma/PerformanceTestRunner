# PerformanceTestingMadeSimple
Maven project for running performance test

To run project via command line, Type below command:


mvn verify -Dthreadcount=5 -Dloop=2 -Dramptime=10


<b>Parameter definitions </b>:
  
threadcount - Number of threads/users for running the performance test

loop - Number of times the execution cycle needs to be repeated

ramptime - The time needed for initialising all threads