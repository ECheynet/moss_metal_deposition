# Atmospheric deposition of heavy metals in Norway (2015)

[![View Atmospheric deposition of heavy metals in Norway (2015) on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://se.mathworks.com/matlabcentral/fileexchange/127978-atmospheric-deposition-of-heavy-metals-in-norway-2015)
[![Donation](https://camo.githubusercontent.com/a37ab2f2f19af23730565736fb8621eea275aad02f649c8f96959f78388edf45/68747470733a2f2f77617265686f7573652d63616d6f2e636d68312e707366686f737465642e6f72672f316339333962613132323739393662383762623033636630323963313438323165616239616439312f3638373437343730373333613266326636393664363732653733363836393635366336343733326536393666326636323631363436373635326634343666366536313734363532643432373537393235333233303664363532353332333036313235333233303633366636363636363536353264373936353663366336663737363737323635363536653265373337363637)](https://www.buymeacoffee.com/echeynet)

## Summary 

Matlab scripts to extract and visualize data related to deposition of metal on dry moss in Norway. The EBAS database [1] hosted by thredds server by NILU is accessed. For additional information on the data, see [2].

<img src="./moss.png" width="50%" height="50%" />

## Dependencies

    MATLAB R2019b or later
    Mapping Toolbox

## Files

    - getData_from_Thredds.mlx: MATLAB live script for extracting data from the Thredds server 
    - moss_data.mat: data extracted with getData_from_Thredds.mlx
    - plot_results.mlx: MATLAB live script for visualizing the data extracted with getData_from_Thredds.mlx
    - world.mat: MATLAB mat file containing the coastline at a global scale

##  Usage

    Run getData_from_Thredds.mlx to extract the data from the Thredds server. The data will be saved in moss_data.mat.
    Run plot_results.mlx to visualize the extracted data. The script will load moss_data.mat and world.mat and generate scatter plots of the environmental data.
    The output plots will be saved as PDF files in the same directory.

## Acknowledgments

The environmental data was obtained from the EBAS database hosted on the Thredds server maintained by the Norwegian Institute for Air Research.

## Reference

[1] https://thredds.nilu.no/thredds/catalog/ebas/catalog.html

[2] Steinnes, E., Uggerud, H. T., Pfaffhuber, K. A., & Berg, T. (2017). Atmospheric deposition of heavy metals in Norway. National moss survey 2015. NILU rapport.


