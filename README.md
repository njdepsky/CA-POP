# CA-POP

The GeoTIFF raster grids in this repository represent the CA-POP databased, which consists of statewide population layers of California. These layers were constructed using dasymetric mapping techniques to produce 100m x 100m estimates for 9 variables from the 2020 United States Census (P.L. 94-171 Resdistricting Summary File), using census block estimates as the population 'source zones', as described in **_Depsky et al. 2022_** (_submitted, under review_).

## Gridded Population Variables 
2020 Census Block Level Population Totals Obtained (P.L. 94-171 Code)  | CA-POP Grid Name
---------------------------------------------------------------------- | -------------
_**Grids created for each variable:**_
Population (P002001) | TOTAL
Hispanic or Latino (P002002) | HISP
Not-Hispanic or Latino, White alone (P002005) | NHWHITE
Not-Hispanic or Latino, Black or African American alone (P002006) | NHBLACK
Not-Hispanic or Latino, American Indian and Alaska Native alone (P002007) | NHAMIND
Not-Hispanic or Latino, Asian alone (P002008) | NHASIAN
Not-Hispanic or Latino, Native Hawaiian and Other Pacific Islander alone (P002009) | NHHIPI
--  | --
_**OTHER/MULTI grid created from sum of:**_ | OTHERMULTI
Not-Hispanic or Latino, Some Other Race alone (P002010) | --
Not-Hispanic or Latino, Population of two or more races (P002011) | --
--  | --
_**MINORS grid (population < 18 years old) created from:**_ | OTHERMULTI
Not-Hispanic or Latino, Some Other Race alone (P002010) | --
Not-Hispanic or Latino, Population of two or more races (P002011) | --
