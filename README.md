# gtaf
GTAF - Generalized Target Assignment and Path Finding

This contains the code and instances used in the paper "Van Nguyen, Philipp Obermeier, Tran Cao Son, Torsten Schaub, William Yeoh: Generalized Target Assignment and Path Finding Using Answer Set Programming. IJCAI 2017: 1216-1223."

The code is in the root directory. 

The instances are in the subdirectories 22, 33, ... 

Each of these subdirectories contains three instances 0, 1, 2 --- Each instance is described in two files: x.agents and x.map (detailed in the paper)

The script test_asp (you can change it to a better name:) is the glue of all the codes. It is supposed to run in one of the subdirectories (e.g., 22 or 33 or 44 etc.) 

For each instance in the subdirectory, the script will compute one solution. The instance needs to be specified in PROBS; for example, if PROBS="0 1 2" then the script will compute solution for instance 0, 1, 2; 

time_X.txt will record the time taken to compute a solution for the instance X; 

The code only runs with clingo 4.4 or 4.5. 
