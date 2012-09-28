This repository contains code and other material for the development of a script module for the GRASS GIS (http://grass.osgeo.org).
The v.topsites module automatically detects hill-top sites candidates from a DTM. This is accomplished in two steps:
1. the DTM is segmented using GRASS' r.seg module (http://www.ing.unitn.it/~vittia/sw/)
2. the resulting areas are filtered according to compactness and mean curvature

A brief description of this approach and an introductory discussion of the results can be found in "Elisa Rosciano, Fabio Cavulli, Marco Ciolli, Alfonso Vitti, Paolo Zatelli, DTM segmentation and analysis for archaeological hill-top sites recognition in GRASS, 2011, Geomatics Workbooks", available here http://geomatica.como.polimi.it/workbooks/n10/GW10-FOSS4Git_2011.pdf. Further papers are in preparation.
