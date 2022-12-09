# GLE-NMDB
**GLE_tutorial** produces **3 GLE related plots**.

It makes use of the script by **C.T. Steigies** (*nest.py*) to call **NMDB** and download data from the neutron monitor (NM) stations selected by the user.

In particular it provides:

**First plot**

A percentage increase plot of the selected stations. In order to make the percentage a baseline (taken simply as the 1 hour, i.e. the first 60 minutes from the selected interval).

**Second plot** This script provides the **North-South latitudinal anisotropy**

Similar as before, in order to make the percentage a baseline (taken simply as the 1 hour, i.e. the first 60 minutes from the selected interval).

Makes a plot of two stations including their difference (the idea here is to directly evaluate the North-South latitudinal anisotropy. 
For this THULE and JBGO (or MCMU for earlier GLEs) should be selected, see also https://www.aanda.org/articles/aa/full_html/2022/04/aa42855-21/F10.html for an example) | however data seem not to be available.

**Third plot** This script provides the **Longitudinal anisotropy**

Similar as before, in order to make the percentage a baseline (taken simply as the 1 hour, i.e. the first 60 minutes from the selected interval).

The script makes a sum of all selected stations except the first one and then provides the difference between the first one and the rest of the NMs. 
The idea is to have all NM stations with a nominal cut-off R< 1.4 GV in order to evaluate the longitudinal anisotropy see also https://www.aanda.org/articles/aa/full_html/2022/04/aa42855-21/F11.html for an example).

**Contact**
Athanasios Papaioannou atpapaio@noa.gr, George Vasalos gvasalos@noa.gr
