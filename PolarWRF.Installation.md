# Polar installation WRF manual (not finished!)

1. Get PWRF from [Polar Meteorology Group](https://polarmet.osu.edu/PWRF/).

2. Rename folders `PWRF{XXX}` into PWRFV{X}.{Y}.{Z}, where X,Y,Z -- PWRF version

3. Rename folders `wps` into PWPSV{X}.{Y}.{Z}, where X,Y,Z -- PWRF version

4. Download proper version of WRF src from [WRF Users](https://www2.mmm.ucar.edu/wrf/users/). Keep exactly the same version as PWRF.

5. Check proper paths in `install_Gavrikov.sh`
	* Set `$PWRFSRC` and `$PWPSSRC` for folders from Sections 2 and 3
	* Set `$WRFSRC` and `$WRFSRC` variables for the src path to WRF and WPS folders from 4 section

5. Run `install_Gavrikov.sh`

6. Finally go through WRF installation process (follow the instruction on [WRF Users](https://www2.mmm.ucar.edu/wrf/users/)).

Enjoy