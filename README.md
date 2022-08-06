# pythonSpeedTesting
Testing python code speed

I am using the timeit library because 
- easy formatting 
- averages over many runs to minimise impact of 
  - os scheduling
  - disk flushing
- disables garbage collection to prevent it running during the test
- picks best clock for the system


