# csc263_assignment2
Contains the Code for CSC 263 Assignment 2

# Installation Steps
> - Log on to the cycle machines on the csug network (ssh -L <username> cycle1.csug.rochester.edu)
> - Download the file : `wget https://github.com/DataIntelligenceCrew/csc263_assignment2/blob/main/assignment_2.tar.gz`
> - Unzip the file : `tar -xvf assignment_2.tar.gz`
> - `cd assignment_2`
> - There is a sample file `lastname_assignment2.cpp`, you should use that as the starter code
> - *Rename the above file*
  
# Compiling
To compile your project
> - `cd assignemnt_2`
> - `g++ -o myproj -I./include/ -L./.libs/ -l xapian lastname_assignment2.cpp`
  
  
# Submission
> - You only need to submit the renamed `lastname_assignment2.cpp` file
