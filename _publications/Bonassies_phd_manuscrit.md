---
title: "Data assimilation of remote sensing flood extent for flood forecasting: Benefits of data provided by the SWOT satellite"
title_fr: "Assimilation de données des étendues des inondations obtenues par télédétection pour la prévision des inondations : apports des données issues du satellite SWOT"
collection: phd
category: manuscripts
permalink: /publication/Bonassies_phd_manuscrit
date: 2026-04-21
venue: 'University of Toulouse, France'
bibtexurl: 'https://quentinbns.github.io/files/bib/Bonassies_phd_2026.bib'
citation: 'Q. Bonassies, "Data assimilation of remote sensing flood extent for flood forecasting: Benefits of data provided by the SWOT satellite", PhD Thesis, University of Toulouse, France, 2026.'
---

French Title
---
"Assimilation de données des étendues des inondations obtenues par télédétection pour la prévision des inondations : apports des données issues du satellite SWOT"

Plain Language Summary
----
Floods are difficult to predict due to the dynamics of such events and the limited number of observations, especially during floods. Satellite images are now widely used for flood monitoring, but combining such data with ground measurements and numerical models is still challenging. This thesis aims to improve flood modeling by better integrating in-situ observations and satellite data, with a focus on the SWOT satellite. The study examines floods at several scales, from large river basins to detailed 2D hydrodynamic flood simulations. Different SWOT products are evaluated, showing good results for river water levels and strong potential for flood extent mapping. A new method, inspired by computer vision techniques, has been developed to incorporate satellite-derived flood maps into models. Overall, the results show that combining ground data and multiple satellite sources lead to the most accurate flood simulations and highlights the strong potential of SWOT for flood monitoring.


Abstract
---
Flood modeling and forecasting are essential for effective risk management and disaster mitigation. Accurately representing flood dynamics remains challenging due to the strong nonlinearity of hydrological and hydraulic processes, their multi-scale nature, and the limited spatial and temporal coverage of observations, particularly during extreme events.  In recent years, satellite imagery has become an essential source of information for flood monitoring, offering unprecedented spatial coverage. These observations raise important challenges regarding the integration of heterogeneous and uncertain observations into numerical models.

This thesis addresses these challenges by developing and evaluating data assimilation methods combining in situ measurements and satellite observations, with a particular focus on the SWOT (Surface Water and Ocean Topography) satellite. It adopts a multi-scale approach, ranging from large-scale hydrological routing to local two-dimensional hydrodynamic modeling, and explores the contribution of different SWOT products for improving flood simulation and monitoring.

At the basin scale, the RAPID routing model is used to simulate the discharge over the Garonne watershed. The assimilation of the observed discharge by the in-situ VigiCrue gauging network significantly improves the representation of flood events, but also highlights the limitations of the definition and propagation of observation error covariances in the current assimilation framework. The discharge estimated by SWOT is analyzed but not assimilated, due to significant discrepancies with in situ observations and RAPID results.

At finer spatial scales, the thesis focuses on 2D hydraulic modeling of flood events and the assimilation of SWOT Level 2 products. Water surface elevation from SWOT Node products along the river centerline is analyzed and assimilated. These assimilation experiments show good consistency between SWOT data and associated hydrodynamic simulations under low water conditions. However, these products do not allow observation of floodplain dynamics. A study on the extraction of flood extents from SWOT Pixel Cloud products is carried out for various flood events worldwide. It demonstrates the strong potential of SWOT for flood mapping, while highlighting methodological limitations due to the use of a simple threshold for the extraction of these flood extents.

To enable effective and relevant assimilation of satellite images, an innovative method based on the Chan-Vese image segmentation model has been developed within a theoretical framework. This approach is integrated into an Ensemble Transform Kalman filter and enables the assimilation of geometric information contained in binary flood extents extracted from SWOT or other satellites such as Sentinel-1 and 2. The results of assimilation experiments show that the method can correctly assimilate shapes, but also reveal the current limitations of the algorithm. In the real-world application, these limitations are related to the calibration of the method's parameters, the computational cost, and the control of parameters in the data assimilation algorithm.

Finally, the thesis evaluates the joint assimilation of in situ data, flood extents from Sentinel-1, and all SWOT products. The assimilation experiment integrating all observations remains the one that shows the most accurate results for the studied flood event. This work demonstrates the major contribution of SWOT and its assimilation to the study and monitoring of floods, while identifying methodological challenges that must be addressed in order to fully exploit satellite data.