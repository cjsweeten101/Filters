# Filters
The goal of this project was to characterize and investigate the difference between digital and analog filters.

Inside of the project folder there is 3 main VIs meas01, meas02a, meas02b.  Along with scopeinit and scope amp.  There utility is as follows:

meas01:  Reads the output of a integrated analog filter, and stores the data in a csv file

meas02a: Uses LabVIEWs built in digital filter to filter an inputed waveform, also outputs data the same as meas01.

meas02b: Uses a custom built digital filter, which is called 10tapvi.  With calculated coefficients.

scopeinit and scopeamp are both for initializing and reading from an oscilliscope.



Also included are screenshots off the frequency gain profile for the input waveform, low pass filter (lp) and notch pass filter (np).
