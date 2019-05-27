# `transpec`: demo data and information for the NIR data transfer tool

Flawil, 27.05.2019

Here you find a short set of tips for using `transpec` along with a demo .nir file that you can use to test the app. 

- Only N-500/NIRMaster to ProxiMate transfer are allowed (for the moment).
- Repeated property names are not allowed.
- No more than 1 product type per .nir file (transfer fucntions are product specific).
- Before using the app, try to remove special characters in the IDs of the samples.
- Recommended for N 500/NIRMaster (no nirvis, no n400, etc)
- Loading huge files might take a while.
- The wavelength range is only the overlap of both spectrometers (e.g. N 500 to ProxiMate: You can only use 1000 to 1700 nm).
- Bad input data will return bad output. 

Download the demo file for `transpec` by cliking [here](https://github.com/l-ramirez-lopez/transpec_info/raw/master/DEMO_file_cannabis.nir). A brief description of the contents of the file is as follows: 

- The spectra correspond to cannabis flowers of 40 samples measured in triplicate (for a total of 120 spectra).  
- The file contains laboratory measured data for two propeties: Cannabidiolic Acid (CBDA) and tetrahydrocannabinolic acid (THCA). CBDA data is available for 21 samples while THCA is available for 27 samples. 
- The measurements were condcuted with three different instruments.