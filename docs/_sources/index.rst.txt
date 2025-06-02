==========
CoKLIMAx I
==========

Welcome to the CoKLIMAx I microclimate analysis and visualization toolkit. This project is dedicated to the robust processing and insightful analysis of high-resolution microclimate simulation data. The core simulations underpinning this work were performed using PALM-4U (PALM Model System), and the resulting netCDF4 output files are efficiently handled and explored through the comprehensive scripts and notebooks documented here.

PALM-4U (PALM Model System for Urban Applications) is a cutting-edge, three-dimensional, non-hydrostatic atmospheric model. It is specifically engineered to simulate urban microclimates with exceptional detail, accounting for the intricate interplay of complex surface structures, building geometries, diverse vegetation, and dynamic atmospheric processes. This advanced model is widely utilized in urban climate research and planning to rigorously assess the impacts of urbanization, such as urban heat island effects and altered wind patterns, and to effectively evaluate and inform climate adaptation strategies for creating more resilient and comfortable urban environments. PALM-4U is an open-source solution that continues to be developed by a consortium of institutions, notably within the framework of the "[UC²] - Urban Climate Under Change" program, funded by the German Federal Ministry of Education and Research (BMBF).

.. toctree::
  :maxdepth: 1
  :caption: Data Preparation:

  /notebooks/_01_2D_Var_Agg_and_Extract
  /notebooks/_02_3D_to_2d_Surface_Var_Extract
  /notebooks/_03_2D_Surface_Var_Agg_and_Extract
  
.. toctree::
  :maxdepth: 1
  :caption: Preminimary:

  /notebooks/01_Obs_vs_Sim
  /notebooks/02_Distance_of_AOI_vs_t-test

.. toctree::
  :maxdepth: 1
  :caption: Variable: Temperature:

  /notebooks/03_Air_Temp_Analysis_BS_vs_S1
  /notebooks/04_Air_Temp_Analysis_Heatmaps
  /notebooks/05_Air_Temp_with_Agg

.. toctree::
  :maxdepth: 1
  :caption: Variables: Biometeorology:

  /notebooks/06_Bio_Var_Analysis_BS_vs_S1
  /notebooks/07_Bio_Var_Analysis_BS_vs_S1

.. toctree::
  :maxdepth: 1
  :caption: Variables: Wind:

  /notebooks/08_2D_Wspeed_with_Agg
  