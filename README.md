This repository shows the implementation of the IGS coseismic slip prediction workflow, applied to Nevada Geodetic Laboratory's affiliated stations in Greece. IGS uses the Okada 1985 surface deformation model, along with scaling laws by Mai & Beroza (2000), Yen & Ma (2011), and Yen & Ma (2011). This workflow is applied to the 10 largest earthquakes in Greece from years 2000-2020, according to the Global Centroid Moment Tensor catalog.

Point-Source_Okada.ipynb uses the point source model of Okada. The resulting deformations are saved in the Point folder.

Finite-Source_Okada.ipynb uses the finite source model of Okada. The resulting deformations are saved in the Finite folder.

Finite-Source_IGSverification.ipynb uses the finite source code to replicate IGS-calculated coseismic deformations for Turkey M7.8 2023 earthquake and Philippines M7.8 2026 earthquake. Results are saved in the IGSverify folder.

Thesis_Mapping.ipynb maps the Nevada Geodetic Laboratory stations and Global Centroid Moment Tensor catalog in Greece. There are some analyses of seismicity.

Point-Source_CumulativeDisp.ipynb uses the point source model to compute and visualize the cumulative coseismic displacement in Greece due to the events in the CMT catalog from the years 2000-2020.

Finite-Source_CoseismicDisp.ipynb uses the finite source model to visualize the coseismic slip of the largest 10 earthquakes in Greece from 2000-2020 using contour and quiver plots. Results are in the Coseismic folder.
