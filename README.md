# soa
The purpose of this repository is to outline the work done to parralelize SOA. 

### SOA
SOA is a SPICE-based analysis and visualization tool for planning spacecraft-based observations used by NASA. This tool relies on another library called SPICE to perform geometric calculations. SPICE relies on global variables, and is therefore, not thread-safe. 


### The project
The purpose of this project was to find bottlenecks in SOA that called on SPICE, and parralelize them using using Java workers. 
