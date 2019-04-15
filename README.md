# AU-Mic-starspots

Generate a 2-starspot model for AU Mic to match the TESS light curve. Using the Hebb et al. code "STSP"

## prep_data.ipynb
1. Clean the TESS data of bad data points, obvious flares, etc.
2. Output text file light curve for STSP (tess_lc.dat)
3. Measure precise rotation period from data to use (via ACF) and other things needed for STSP to run

## aumic.in
this is the STSP input file
