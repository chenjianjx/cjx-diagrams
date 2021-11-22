# 3 dimensions

* A and B:  bundled or distributed
* A calls B, or A and B are in parallel
  * Services's computation requirements are fully elastic - don't have minimum Capacity Unit,  or not?
* Requests to A vs B is  m:n  



# How do go about it? 

## People say that if ... then ....  Is that real?  Will the overrall ... ?  Now let's use some examples. 

### Assumptions: Compute Units of A, B


### A and B not calling each other 
#### Say B has a minimum CU

Scenario 1: A and B not calling each other, Requests 1:1 
If bundled ...
If independent ...

Scenario 2: A and B not calling each other, Requests 2 : 1
If bundled ...
If independent ...

Scenario 3: A and B not calling each other, Requests 1 : 2
If bundled ...
If independent ...


#### A summary of "A and B non dependency"

### A calls B
Scenario 1: B has a minimum CU 
If bundled ...
If independent ...

Scenario 2: B doesn't have a minimum CU

A summary of A calls B

### B calls A
Scenario 1: B calls A
If bundled ...
If independent ...

Scenario 2: B doesn't have a minimum CU
...

A summary of B calls A

## Conclusion
xxx

## TL&DR;