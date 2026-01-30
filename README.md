This study quantitatively analyses elements within OpenStreetMap (OSM) for Amsterdam Centrum that have the 'name' attribute filled and investigates the intrinsic quality parameters that contribute to the reliability of toponyms in OSM.

The workflow is as follows:
<img width="958" height="702" alt="image" src="https://github.com/user-attachments/assets/b162f3ce-2522-4692-ae4e-df1b45f1f8e3" />

### Input Data and Jupyter Notebooks ###

The input datasets are GeoJSON files located in data/input_code1. The Jupyter notebooks generate dropdown widgets that allow the user to select the appropriate file.

The notebooks are:
-  notebooks/replic1_OsmEditHist_OHSOME_Grid.ipynb.
-  notebooks/replic2_OsmToponyms_Analysis.ipynb.

The former extracts historical OSM data using the ohsome API. The latter performs statistical analyses on the output file of the former.

A full explanation of the study, workflow, results, and how the input data files were prepared can be found in the study report.

Report: /OSM_Toponyms_AmsterdamCentrum_Report.pdf
