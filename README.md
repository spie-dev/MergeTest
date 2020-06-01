# MergeTest
Example of using merge as our merging strategy



SPUD-1234 Change 1 - 10:58am  
SPUD-1234 Change 2 - 11:02am  


SPUD-2345 - Change 1 - 11:00am  
SPUD-2345 - Change 2 - 11:03am

had to resolve conflicts when merging SPUD-2345 into master after SPUD-1234 was merged into master, but that's cause I didn't merge from Master into SPUD-2345 to keep it the latest  


* Created SPUD-1234 branch from master  
* Created SPUD-2345 branch from master  
* Committed SPUD-1234 Change 1 to SPUD-1234 branch  
* Committed SPUD-2345 Change 1 to SPUD-2345 branch  
* Committed SPUD-1234 Change 2 to SPUD-1234 branch  
* Committed SPUD-2345 Change 2 to SPUD-2345 branch  
* Merged SPUD-1234 branch into master  
* Merged master into SPUD-2345  
* Merged SPUD-2345 into master  
* Commited this edit to this doc in master
