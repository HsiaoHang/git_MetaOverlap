# git_MetaOverlap

This repository contains two folders: [data], [code], and [output], to reproduce all the results of the paper 'Co-occurrence between size groups within populations decreases with maximum body size across marine fish populations'. 

a. The [data] folder contains following files:

1. [Beukhof_2019_TraitData.xlsx] is life history trait data downloaded from <Beukhof E, Dencker TS, Palomares MLD et al. A trait collection of marine fish species from North Atlantic and Northeast Pacific continental shelf seas. 2019, DOI: 10.1594/PANGAEA.900866.>

2. [a_common_name_all_stocks.csv] has scientific and corresponding common name for each species.

Note: The CPUE in the North Sea and Scottish West Coast regions are downloaded from ices data portal <https://datras.ices.dk/Data_products/Download/Download_Data_public.aspx> in the format of CPUE per length per subarea per year quarter. All the CPUE data (North Sea, Scottish West Coast, Eastern Bering Sea) are available upon request to authors.


b.The [code] folder contains seven R scripts, which should be run sequentially from 01 to 07.


c. The [output] folder contains following files:

1. [cpue.length.subarea.yearqua.csv] is compiled time series of cpue per body length per subarea for each year for each population, generated from <05_calculate_indices.Rmd>

2. [cpue.year.csv] is compiled time series of cpue per year for each population, generated from <05_calculate_indices.Rmd>

3. [cpue.pair] is compiled time series of cpue per size group per year for each population, generated from <06_calculate_overlap_new>

4. [co.dd.csv] is compiled time series of Alpha MLE for each size group pair of each population, generated from <07_calculate-cooccurrence.Rmd>

5. [trait.table.csv] is compiled life history traits for each studied populations, generated from <08_plot_cooccurrence.Rmd>



