# Canadian Living Planet Index
The Living Planet Index — a biodiversity indicator that assesses the relative change of aggregate vertebrate abundance data — is an indicator used in global (e.g., Kunming Montreal Global Biodiversity Framework) and national (e.g., Canada’s 2030 Nature Strategy) biodiversity monitoring frameworks. In Canada, the LPI has been modified (C-LPI) — adopting differing methodological choices relative to the global LPI. However, there is no clear consensus on the most appropriate analytical methods, particularly as they pertain to the treatment of zeros, credible intervals and uncertainty, time series length and number of data points required, modelling of short time series, removal of outliers, weighting species, and the impact of baseline year selection. Our analysis transparently explores multiple methodological options for each of these decision points. Our research does not evaluate the superiority of a single approach but rather reinforces the need for transparency and accountability in reporting. We hope that the transparency provided in this study will further strengthen the utility of the C-LPI and provide decision makers with the necessary information to appropriately interpret patterns, evaluate progress, and inform conservation action.
## Navigating methodological decisions: Balancing rigor and data volume of the Canadian Living Planet Index 
### Authors: Jessica Currie, Sarah M Ravoth, Valentina Marconi, Louise McRae, Maria I Arce-Plata, Sandra Emry, Robin Freeman, Maximiliane Jousse, Gaëlle Mével, Shuaishuai Li, Cristian A Cruz-Rodríguez, David AGA Hunt, Philippa Oppenheimer, Lauren Gill, Janaina Serrano, Stefanie Deinet

We showcase the impact of methodological decisions associated with seven parameters on the C-LPI: (i) treatment of zero values, (ii) credible intervals and uncertainty, (iii) time series length and number of data points, (iv) modelling of short time series, (v) removal of outliers, (vi) weighting of species, and (vii) selection of the baseline year. Methodological changes were compared to current approaches employed by the C-LPI (Table 1). Native vertebrate trends were calculated predominantly using selectable options under the publicly available rlpi R package (Freeman et al. 2017), with indices spanning from 1970 to 2022.

## Notes
The attached code permits calculation of the Canadian Living Planet Index (synonymous with Environment and Climate Change Canada's "Canadian Species Index"). Note that confidential records (those deemed confidential by the data contributor) have been removed in the dataset, and thus results will not align perfectly.
The code differs from the global Living Planet Index in a variety of ways including assignment of replicates, treatment of zeroes, modelling, credible intervals, and weightings. Consequently, when running an analysis for Canada, it may be best to begin with this code, which uses the original rlpi package. Note that any updates to the dataset are not captured here. Additional data records can be downloaded from the Zoological Society of London’s Living Planet Index Data Portal. Please be sure to sort for Canada, and to exclude replicates.

### Scripts
* Data can be found in “00_data”
* Run all scripts in “02_scripts”, ensuring “final-analyses-figures” is run last
* Figures to match those in our paper will be output in “03_figures”, with the data in “01_outdata”



