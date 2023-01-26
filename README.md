# CoastCAMs
This repository gathers all the codes used to process the data collected by nearshore video camera systems.
Video camera systems collect raw images and generate three types of secondary images every 10 or 15 minutes: snapshots, time exposures (timex), and time-stacks.
Timex images are snapshot images averaged every 10 or 15 minutes into a single image [1].
Time-stack images are intensity values saved at each time step at a selected array of pixels from snapshots [2].

Most of the parameters needed to understand the African coastal environments can be derived simultaneously: wave characteristics (CAMS_N2_Parameters and
CAMS_N2_Direction), water level variations (derived form bathymetry, see[3,4]) and beach morphology (CAMS_N2_Shoreline for shoreline, see https://github.com/gregsolo/T-Cor-Toolbox for bathymetry).

References
[1] Holland, K. T., Holman, R. A., Lippmann, T. C., Stanley, J., & Plant, N. Practical use of video imagery in nearshore oceanographic field studies.
IEEE Journal of oceanic engineering, 22(1), 81-92 (1997).
[2] Holland, K. T. & Holman, R. A. The statistical distribution of swash maxima on natural beaches. Journal of Geophysical Research, 98, 10271–10278 (1993).
[3] Abessolo, G.O. et al.. Sea level at the coast from video-sensed waves: comparison to tidal gauges and satellite altimetry. Journal of Atmospheric and Oceanic Technology, 36, 1591-1603 (2019).
[4] Thuan, D. H. Almar, R., Marchesiello, P. & Viet, N. T. Video sensing of nearshore bathymetry evolution with error estimate. J. Mar. Sci. Eng., 7, 233; https://doi.org/10.3390/jmse7070233 (2019).
