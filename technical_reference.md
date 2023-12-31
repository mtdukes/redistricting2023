# Technical reference

## Duke precinct vote to block crosswalk

The crosswalk file created by the Duke University team contains the vote breakdown for multiple statewide races by block, based on precinct level election results. Generated from [the team's shapefile](https://git.math.duke.edu/gitlab/gjh/redistricting2020results/-/blob/main/NC/Shapefiles/cblocks_w20210812Pcts.zip) by exporting to CSV using QGIS Oct. 9, 2023.

*Filename: block_precinct_vote_crosswalk.csv*

*Source: Duke Quantifying Gerrymandering Team*

| field | description | notes
|--|--|--|
|county_id| County ID| |
|tract| Tract ID | |
|block| Block ID | |
|geo_id| 15-character combined Census ID | |
|prec_id| SBOE precinct ID | |
|county| County name | |
|pop2020cen| Block population, 2020 census | |
|g20_ag_d| 2020 attorney general, Dem votes | |
|g20_ag_r| 2020 attorney general, Rep votes | |
|g20_ad_d| 2020 auditor, Dem votes | |
|g20_ad_r| 2020 auditor, Rep votes | |
|g20_ca_d| 2020 agriculture commissioner, Dem votes | |
|g20_ca_r| 2020 agriculture commissioner, Rep votes | |
|g20_ci_d| 2020 insurance commissioner, Dem votes | |
|g20_ci_r| 2020 insurance commissioner, Rep votes | |
|g20_cl_d| 2020 labor commissioner, Dem votes | |
|g20_cl_r| 2020 labor commissioner, Rep votes | |
|g20_gv_d| 2020 governor, Dem votes | |
|g20_gv_r| 2020 governor, Rep votes | |
|g20_lg_d| 2020 lt. governor, Dem votes | |
|g20_lg_r| 2020 lt. governor, Rep votes | |
|g20_sst_d| 2020 secretary of state, Dem votes | |
|g20_sst_r| 2020 secretary of state , Rep votes| |
|g20_tr_d| 2020 treasurer, Dem votes | |
|g20_tr_r| 2020 treasurer, Rep votes | |
|g20_pr_d| 2020 president, Dem votes | |
|g20_pr_r| 2020 president, Rep votes | |
|g20_uss_d| 2020 U.S. Senate, Dem votes | |
|g20_uss_r| 2020 U.S. Senate, Rep votes | |
|g08_pr_d| 2008 president, Dem votes | |
|g08_pr_r| 2008 president, Rep votes | |
|g08_ag_d| 2008 attorney general, Dem votes | |
|g08_ag_r| 2008 attorney general, Rep votes | |
|g08_ad_d| 2008 auditor, Dem votes | |
|g08_ad_r| 2008 auditor, Rep votes | |
|g08_ca_d| 2008 agriculture commissioner, Dem votes | |
|g08_ca_r| 2008 agriculture commissioner, Rep votes | |
|g08_ci_d| 2008 insurance commissioner, Dem votes | |
|g08_ci_r| 2008 insurance commissioner, Rep votes | |
|g08_cl_d| 2008 labor commissioner, Dem votes | |
|g08_cl_r| 2008 labor commissioner, Rep votes | |
|g08_gv_d| 2008 governor, Dem votes | |
|g08_gv_r| 2008 governor, Rep votes | |
|g08_lg_d| 2008 lt. governor, Dem votes | |
|g08_lg_r| 2008 lt. governor, Rep votes | |
|g08_uss_d| 2008 U.S. Senate, Dem votes | |
|g08_uss_r| 2008 U.S. Senate, Rep votes | |
|g10_uss_d| 2010 U.S. Senate, Dem votes | |
|g10_uss_r| 2010 U.S. Senate, Rep votes | |
|g12_lg_d| 2012 lt. governor, Dem votes | |
|g12_lg_r| 2012 lt. governor, Rep votes | |
|g12_sst_d| 2012 secretary of state, Dem votes | *Note: Corrected from g12_ss_d in original data* |
|g12_sst_r| 2012 secretary of state, Rep votes | *Note: Corrected from g12_ss_r in original data* |
|g14_uss_d| 2014 U.S. Senate, Dem votes | |
|g14_uss_r| 2014 U.S. Senate, Rep votes | |
|g12_pr_d| 2012 president, Dem votes | |
|g12_pr_r| 2012 president, Rep votes | |
|g16_pr_d| 2016 president, Dem votes | |
|g16_pr_r| 2016 president, Rep votes | |
|g16_uss_d| 2016 U.S. Senate, Dem votes | |
|g16_uss_r| 2016 U.S. Senate, Rep votes | |
|g16_gv_d| 2016 governor, Dem votes | |
|g16_gv_r| 2016 governor, Rep votes | |
|g16_lg_d| 2016 lt. governor, Dem votes | |
|g16_lg_r| 2016 lt. governor, Rep votes | |
|g16_ag_d| 2016 attorney general, Dem votes | |
|g16_ag_r| 2016 attorney general, Rep votes | |
|g12_gv_d| 2012 governor, Dem votes | |
|g12_gv_r| 2012 governor, Rep votes | |
|g12_ci_d| 2012 labor commissioner, Dem votes | |
|g12_ci_r| 2012 labor commissioner, Rep votes | |
|vap2020cen| Voting age population, 2020 census | |
|bvap2020ce| Black voting-age population, 2020 census | |

## Ensemble files

Raw distribution files generated by the Duke Gerrymandering team showing vote percentages for the Democratic candidate under the conditions of a past election for each district and each of the 100,000 maps generated in the team's ensemble.

*Source: [Duke Quantifying Gerrymandering team](https://git.math.duke.edu/gitlab/gjh/redistricting2020results/-/tree/main/NC/Ensembles?ref_type=heads)*


## Proposed block assignment files

Block assignment files describe the makeup of individual districts in the N.C. House, N.C. Senate and U.S. House using each district's component census blocks. All block assignment files have the same layout.

| block | district |
|--|--|
| 15-character combined Census ID for block | District number|

Block assignment files were generated by the N&O from shapefiles provided by the N.C. General Assembly with [Dave's Redistricting App](https://davesredistricting.org/).

### Block assignment file, NC House 2023

[N.C. House Bill 898](https://ncleg.gov/BillLookUp/2023/H898) filed Oct. 18, 2023.

### Block assignment file, NC Senate 2023

[N.C. Senate Bill 758](https://ncleg.gov/BillLookUp/2023/S758) filed Oct. 18, 2023.

### Block assignment file, U.S. House 2023

[N.C. Senate Bill 756](https://ncleg.gov/BillLookUp/2023/S756) filed Oct. 18, 2023.

### Block assignment file, U.S. House 2023

[N.C. Senate Bill 757](https://ncleg.gov/BillLookUp/2023/S757 filed Oct. 18, 2023.

## Past block assignment files

Block assignment files describe the makeup of individual districts in the N.C. House, N.C. Senate and U.S. House using each district's component census blocks. All block assignment files have the same layout.

| block | district |
|--|--|
| 15-character combined Census ID for block | District number|

### Block assignment file, NC House 2022

North Carolina House district plan. Enacted by the NC General Assembly on February 17, 2022 as [House Bill 980](https://ncleg.gov/BillLookUp/2021/H980), becoming Session Law 2022-4.

*Filename: baf_nc_house_2022.csv*

*Source: [N.C. General Assembly](https://ncleg.gov/Files/GIS/Plans_Main/House_2022/SL%202022-4%20House%20-%20Block%20Assignment%20File.zip)*

### Block assignment file, NC House 2021

North Carolina House district plan. Enacted by the NC General Assembly on November 4, 2021 as [House Bill 976](https://www.ncleg.gov/BillLookUp/2021/H976), becoming Session Law 2021-175.

*Filename: baf_nc_house_2021.csv*

*Source: [N.C. General Assembly](https://www.ncleg.gov/Files/GIS/Plans_Main/House_2021/SL%202021-175%20House%20-%20Block%20Assignment%20File.zip)*

### Block assignment file, NC Senate 2022

North Carolina Senate district plan. Enacted by the NC General Assembly on February 17, 2022 as [Senate Bill 744](https://ncleg.gov/BillLookUp/2021/S744), becoming Session Law 2022-2.

*Filename: baf_nc_senate_2022.csv*

*Source: [N.C. General Assembly](https://ncleg.gov/Files/GIS/Plans_Main/Senate_2022/SL%202022-2%20Senate%20-%20Block%20Assignment%20File.zip)*

### Block assignment file, NC Senate 2021

North Carolina Senate district plan. Enacted by the NC General Assembly on November 4, 2021 as [Senate Bill 739](https://www.ncleg.gov/BillLookUp/2021/S739), becoming Session Law 2021-173.

*Filename: baf_nc_senate_2021.csv*

*Source: [N.C. General Assembly](https://www.ncleg.gov/Files/GIS/Plans_Main/Senate_2021/SL%202021-173%20Senate%20-%20Block%20Assignment%20File.zip)*

### Block assignment file, US House 2022

North Carolina US Congressional district plan ordered by the NC Courts on February 23, 2022 in Harper v. Hall, File No. 21 CVS 015426, Wake County Superior Court. 

*Filename: baf_us_house_2022.csv*

*Source: [N.C. General Assembly](https://ncleg.gov/Files/GIS/Plans_Main/Congress_2022_Court/2022%20Interim%20Congressional%20-%20Block%20Assignment%20File.zip)*

### Block assignment file, US House 2021

North Carolina congressional district plan. Enacted by the NC General Assembly on November 4, 2021 as [Senate Bill 740](https://www.ncleg.gov/BillLookUp/2021/S740), becoming Session Law 2021-174. District boundaries are based on 2020 census tabulation blocks.

*Filename: baf_us_house_2021.csv*

*Source: [N.C. General Assembly](https://www.ncleg.gov/Files/GIS/Plans_Main/Congress_2021/SL%202021-174%20Congress%20-%20Block%20Assignment%20File.zip)*
