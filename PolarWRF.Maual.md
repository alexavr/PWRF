# Polar installation WRF manual (not finished!)

Some notes while I was installing PWRF.

Instruction for PWRF 4.5.1. We are planning to release version 4.7.1 soon. It is expected to be the final version of Polar WRF, as we are eventually moving to the MPAS variable resolution model.

* We recommend compiling the initial condition program real.exe with the standard/classic WRF to produce the initial and boundary files. Then run wrf.exe with Polar WRF to produce the standard model output.


## Files

Files in **TBL** subdirectory are designed for usage with the NoahMP land surface model. Those files have Arctic settings.

**dyn_em**,  **phys**,  **Registry**,  **run**,  **share** -- containe file to replase in classic WRF foler.


## Additional variables

1. **Sea ice fraction** -- widely avaiable in common WRF input datasets.
2. **sea ice thickness**, **sea ice albedo**, and **snow depth on sea ice** -- are not easily obtained. 

