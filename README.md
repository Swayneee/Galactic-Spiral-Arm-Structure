# Galactic Spiral Arm Structure: OB Stars and Open Cluster Distribution
Galactic Physics Assignment — Galactic Spiral Arms.
This code analyzes the distribution of Open Clusters (OC) and OB stars. The goal is to map the spiral arm structure of the Milky Way. This analysis has two main targets:
Calculate the three-dimensional coordinates (X, Y, Z) from observation data. Compare the distribution of these objects with a galactic spiral arm model to see their patterns.  

Findigs
- 100% of the analyzed objects are very close to the flat galactic plane. The object height (Z) is less than 0.3 kpc. This proves they are part of the Milky Way's thin disk.
- Young Open Clusters (under 32 million years old) and OB stars are the best spiral structure tracers. Both clearly cluster around the Carina-Sagittarius and Perseus spiral arms
- Old Open Clusters are more widely scattered. They no longer form clear spiral arm patterns.
- The spread of objects on the vertical axis (Z) is very small. The value is only 0.077 kpc for young OCs and 0.070 kpc for OB stars. This small number means these objects stick tightly to the flat galactic disk.

Brief Method
- Clean the initial data from empty values, duplicate data, and incorrect distance data.\
- Convert sky coordinate data into 3D space coordinates (X, Y, Z). The center of these coordinates is at the galactic core.
- Convert sky coordinate data into 3D space coordinates (X, Y, Z). The center of these coordinates is at the galactic core.
- Create point graphs (scatter plots). These graphs show the galaxy from a top-down perspective.
- Add spiral arm model lines to the graphs. This is done to match the star positions with theoretical models.

This notebook requires the ncovocc_final.csv and bintang_ob_final.csv files to run. The program will produce 2 clean CSV data files and 6 visualization graph images.  
