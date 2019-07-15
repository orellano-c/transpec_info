# `transpec`: demo data and information for the NIR data transfer app

Flawil, 27.05.2019

Here you can [download the demo file](https://github.com/buchi-labortechnik/transpec_info/raw/master/DEMO-file_cannabis.nir). A brief description of the contents of the file is as follows: 

- The spectra correspond to cannabis flowers of 40 samples measured in triplicate (for a total of 120 spectra).  
- The file contains laboratory measured data for two propeties: Cannabidiolic Acid (CBDA) and tetrahydrocannabinolic acid (THCA). CBDA data is available for 21 samples while THCA is available for 27 samples. 
- The measurements were condcuted with three different instruments.

Here you find a short set of tips for using `transpec` along with a demo .nir file that you can use to try the app. 

- Only N-500/NIRMaster to ProxiMate transfer are allowed (for the moment).
- Repeated property names are not allowed.
- No more than 1 product type per .nir file (transfer fucntions are product specific).
- Before uploading a file into the app, verify that the sample ID's are Ok. Sometimes software programs do not handle adequately non-ASCII characters and they are replaced by a `?` symbol. Despite `transpec` handles almost any character, if you input a file with corrupted ID's the app will not correct them and you will get an output with corrputed ID's too. 
- Recommended for transferring data originally collected with N-500/NIRMaster devices (no nirvis, no n400, etc)
- Loading huge files (>3000 spectra) might take a while.
- When transferring spectra from instrument A to instrument B, the transferable spectral range is limited to the wavelength range in which instruments A and B overlap (e.g. N 500 to ProxiMate: The resulting transferable range is from 1000 to 1700 nm).
- Bad input data will return bad output. 
- For this app we have developed our own proprietary algorithms, the interanl research experiments conducted by the NIR team have demonstrated that the mehods used by the app usually outperform the standard methods commonly found in the literature (direct standardization, piece-wise direct standardization, etc).

You can directly access `transpec`by clicking [here](https://transpec.buchi.com/)


