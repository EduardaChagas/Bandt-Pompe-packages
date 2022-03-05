# Bandt-Pompe packages in Python and R

_Last updated: 2021/11/15_

A list of packages for working with Bandt-Pompe methodology and information theory descriptors.

### Summary table

----

Here, we listed the main features and functionalities used in literature for data characterization and classification using Bandt-Pompe symbolization and information theory descriptors.


|              |   ordpy   |   pyEntropy   |   mpePy   |   Entropia.py   |   AntroPy   |   Teaspoon   |   PE_parameter_selection   |   tsfresh   |
|:------------:|:---------:|:-------------:|:---------:|:---------------:|:-----------:|:------------:|:-----------------------:|:-----------:| 
| Ordinal Patterns |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|   :x:    | :heavy_check_mark: |:x:                | :x: |
| Entropies |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:| :heavy_check_mark:|:heavy_check_mark: |:x: | :heavy_check_mark: | 
| Distances/Divergences |:heavy_check_mark:|      :x:      |   :x:      |  :x: |    :x:      |:x:                 |:x:                | :x: | 
| Statistical Complexity |:heavy_check_mark:|     :x:       |     :x:   |:heavy_check_mark:|     :x:     |:x:                 |:x:                | :x: | 
| HxC Plane | :heavy_check_mark:|     :x:       |    :x:    |  :x:|     :x:     |:x:                 |:x:                | :x: |  
| Fisher-Shannon Plane |:x: |    :x:        |   :x:     |  :x:|     :x:     |:x:                 |:x:                | :x: | 
| Weighted/Amplitude permutation|:x: |:heavy_check_mark:|:heavy_check_mark:|:heavy_check_mark:|   :x:     |:x:                 |:x:                | :x: | 
| Transition Graphs |:heavy_check_mark:|      :x:      |    :x:    |  :x:|     :x:     |:x:                 |:x:                | :x: | 
| Parameters selection |:x: |     :x:       |     :x:   |  :x:|     :x:     |:x:                 | :heavy_check_mark:| :x: | 
| Graphical Interface |:x:         |      :x:      |     :x:   |  :x:    |     :x:     |:x:                 |     :x:           | :x: | 

|                  |   statcomp   |   pdc   |   bandt_pompe   |   Permutation-Entropy   |   NATS   | 
|:----------------:|:------------:|:-------:|:---------------:|:-----------------------:|:--------:| 
| Ordinal Patterns | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| Entropies        | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | 
| Distances/Divergences | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |:x:| :heavy_check_mark: | 
| Statistical Complexity | :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | 
| HxC Plane              | :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | 
| Fisher-Shannon Plane | :x: | :x: | :heavy_check_mark: |:x:| :heavy_check_mark: |  
| Weighted/Amplitude permutation | :heavy_check_mark: | :x: | :heavy_check_mark: |:x:| :heavy_check_mark: |  
| Transition Graphs | :x: | :x: | :heavy_check_mark: |:x:| :heavy_check_mark: |         
| Graphical Interface |    :x:    |   :x:   |      :x:        |:x:| :heavy_check_mark: |    
| Parameters selection |:x:| :heavy_check_mark: |:x:|:x:|:x:|
| Optimization functions in C/Cpp | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |:x:| :heavy_check_mark: |    

### Python Packages
-----

- **ordpy** [[Github]](https://github.com/arthurpessa/ordpy) [[Paper]](https://doi.org/10.1063/5.0049901): A Python package for data analysis with permutation entropy and ordinal network methods.

- **pyEntropy** [[Github]](https://github.com/nikdon/pyEntropy): A small set of functions on top of NumPy that help to compute different types of entropy for time series analysis.

- **mpePy** [[Github]](https://github.com/marisamohr/mpePy): A Python Package for Data Analysis with Multivariate Permutation Entropy for Time Series. mpepy is a pure Python module that implements data analysis methods based on Bandt and Pompe's symbolic encoding scheme. 

- **Entropia.py** [[Github]](https://github.com/jbarberia/Entropia.py): This package centralizes different types of information entropies.

- **AntroPy** [[Github]](https://github.com/raphaelvallat/antropy): AntroPy is a Python 3 package providing several time-efficient algorithms for computing the complexity of time-series. 

- **Teaspoon** [[Github]](https://github.com/sdb2139/tsp-pipeline) [[Documentation]](https://openreview.net/attachment?id=qUoVqrIcy2P&name=Poster): A Comprehensive Python Package for Topological Signal Processing.

- **PE_parameter_selection** [[Github]](https://github.com/Khasawneh-Lab/PE_parameter_selection) [[Documentation]](https://data.mendeley.com/datasets/mxgkstdr8f/2):  Python Script for the Automatic Parameter Selection of Permutation Entropy. This repository has all the script needed to recreate the results found in "On the Automatic Parameter Selection for Permutation Entropy." Specifically, automatic functions for calculating the permutation entropy parameters of delay and dimension are provided.

- **tsfresh** [[Documentation]](https://tsfresh.readthedocs.io/en/latest/index.html):  tsfresh is a python package that automatically calculates a large number of time series characteristics, the so called features. Further the package contains methods to evaluate the explaining power and importance of such characteristics for regression or classification tasks.

### R Packages
-----

- **statcomp** [[Documentation]](https://rdrr.io/rforge/statcomp/): An implementation of local and global statistical complexity measures and entropies for time series analysis based on ordinal statistics. 

- **pdc** [[Github]](https://github.com/brandmaier/pdc) [[paper]](https://www.jstatsoft.org/article/view/v067i05): An R Package for Complexity-Based Clustering of Time Series.

- **bandt_pompe** [[Github]](https://github.com/labepi/bandt_pompe): Implementations of the Bandt-Pompe ordinal patterns transformation.


- **NATS** [[Github]](https://github.com/EduardaChagas/NATS) [[Graphical Interface]](https://natsseries.shinyapps.io/nats/): A non-parametric time series analysis tool. NATS (Non-parametric Analysis Time Series) is a portable, fast and good numerical quality tool that enables interactive and exploratory analysis of data from a time series through techniques from Information Theory. With it, the user has a set of analysis techniques present in the literature to process and examine their data efficiently and with a minimum learning period. The tool is extensible and the system is web-based and developed in R using the Shinny web application framework.


### Python and R
-----
- **Permutation-Entropy** [[Github]](https://github.com/srk-srinivasan/Permutation-Entropy) [[Documentation]](https://kandi.openweaver.com/python/srk-srinivasan/Permutation-Entropy): Github repository with Python and R Codes for Computing ordinal pattern, permutation entropy and Jensen-Shannon Complexity.

If you have any questions, suggestions or you want to report anything, feel free to reach me at: eduarda.chagas@dcc.ufmg.br.
