# WRF-WVTs
Weather Research and Forecasting (WRF) model with moisture tracers

----

The implementation of moisture tracers, or water vapor tracers (WVT), in a regional model, allows users to track moisture from any possible source within the simulation domain. Therefore, this tagging tool is especially appropriate for researchers interested in moisture source studies. 

Users should follow the next steps to run WRF with tracers.

### Compilation

- Download WRF version 3.8.1 at http://www2.mmm.ucar.edu/wrf/users/download/get_sources.html
- Download here the model modules modified to allow moisture tracking, which are compressed within the modules_tracers_3.8.1.tar file
- Move the modules_tracers_3.8.1.tar file to the root directory of the WRF code and decompress it (tar -cvf modules_tracers_3.8.1.tar)
- Compile the WRF model as usual

### Preprocessing