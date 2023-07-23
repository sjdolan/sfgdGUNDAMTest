# sfgdGUNDAMTest
A test set of inputs to run GUNDAM (definitely not intended for a real analysis!)

# How to use
First we need to go and get the MC we need. To do this, go to the repos root directory (the one with this file in) make a directory: 
```
mkdir MC
```
Then we need to put an MC file into this directory which you can find here: 
https://cernbox.cern.ch/s/PjCJ9Kdb3esbzfa

# Running GUNDAM
Once we have the MC we need, go into configtest and run:
```
gundamFitter -c configFitter_SFGDONLY_2022.yaml -t 8 -a -o /path/to/your/output.root
```
