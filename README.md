This repository contains two folders: [code] and [output], to reproduce all the results of the paper 'Co-occurrence between size groups within populations decreases with maximum body size across marine fish populations'. 


a. The [code] folder contains eight R scripts, which should be run sequentially from 01 to 08.


b. The [output] folder contains following files:

1. [cpue.length.subarea.yearqua.csv] is compiled time series of cpue per body length per subarea for each year for each population, generated from <05_calculate_indices.Rmd>

2. [cpue.year.csv] is compiled time series of cpue per year for each population, generated from <05_calculate_indices.Rmd>

3. [cpue.pair] is compiled time series of cpue per size group per year for each population, generated from <06_calculate_overlap.Rmd>

4. [co.dd.csv] is compiled time series of Alpha MLE for each size group pair of each population, generated from <07_calculate-cooccurrence.Rmd>

5. [trait.table.csv] is compiled life history traits for each studied populations, generated from <08_plot_cooccurrence.Rmd>


Data supporting the results of this paper is available at Dryad (link). 

