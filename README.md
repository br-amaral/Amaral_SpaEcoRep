# Amaral_SpaEcoRep
 
Code to run the species distribution models (SDMs) for the Wood Thrush (B1 to B5) and a landscape metrics analysis of areas surrounding 11 National Parks (P1 to P4) in the Northeastern US.

**B1_Get_bcr:** code to get extent of the SDM analysis, that includes 5 Bird Conservation Regions (BCR) in the Northeartern US.

**B2_Get_landcover:** code to get landcover types for all 5 BCR used in the SDM

**B3_Occ:** code to import eBird data and intersect with landcover data to run an occupancy model

**B4_RanFor:** code to import eBird data and intersect with landcover data to run a random forest model

**P1_Landscape_parks:** import land cover maps for 11 National Parks for 6 years (2001 to 2019)

**P2_Buffer_intersect:** import shape files of National Park boundaries and create a buffer aropund them. Intersect buffer with landcover map and select land uses to run the analysis.

**P3_Landscape_metrics:** use the landscape metrics package to calculate landscape metrics for all 11 parks in 6 different years.

**P4_metrics_plots:** plot the landscape metrics results.
