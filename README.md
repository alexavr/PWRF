# PWRF
This is my modification of the [WRF](https://www2.mmm.ucar.edu/wrf/users/) (version 4.5.1) model to create [PolarWRF](https://polarmet.osu.edu/PWRF/) (version 4.5.1). I took the latest (at the moment) version of PWRF (4.5.1) and integrated it with the proper version of WRF src. 

## Fixed:
* The bug in ./Registry/Registry.EM_COMMON.PWRF4.5.0 of PWRF
* Speedup calculation of `GREENFRAC` var in `geogrid.exe` by removing `search` from `./geogrid/GEOGRID.TBL` in WRF
* 


## Installation

1. Clone this repo
2. Compile WRF and WPS (follow the instruction on [WRF Users](https://www2.mmm.ucar.edu/wrf/users/))

>[!WARNING]
> Polar Meteorology Group recommend compiling the initial condition program real.exe with the standard/classic WRF to produce the initial and boundary files. Then run wrf.exe with Polar WRF to produce the standard model output.


Enjoy! 
