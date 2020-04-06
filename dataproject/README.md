# Data analysis project

Our project is titled **Denmark International Trade**. For a tiny country as Denmark, international trade plays an important role and it is relevant to consolidate particular national business sectors besides helping diversifying the economy and final markets. For this reason we have decided to try to analise the most important features of Denmark imports and exports.   
After a brief analysis on general trends and Balance of Trade pattern, we decide to focus on the trade of goods mainly because it seems to be more relevant in comparison to trade in services. However, this analysis can be conducted in the same way for the service case if someone could be interested in.  
The specific analysis of trade in goods tries to detect interesting information and features regarding the trade partners as well the composition of imports and exports by type of goods.  
Our project is structured in 4 main sections. In *Section 1* we import packages and in *Section 2* we construct, clean and prepare the dataframes that will be used to realise the figures of *section 3: Analysis* which can be considered the core of our project. Section 4 concludes with some personal statements regarding the results obtained.  
All the data are from *Statistics Denmark* and are seasonally adjusted to allow measurement of real changes, patterns of growth or decline and to compare data from different point in time.

For this project we **loades three datasets** uploaded in this same folder besides relying in the Statistics D:

1. TRDS.xlsx downloaded from statistikbanekn.dk
2. TRDG.xlsx downloaded from statistikbanekn.dk
3. TRDC.xlsx downloaded from statistikbanekn.dk

The **results** of the project can be seen from running [Data project.ipynb]. Please if the interactive graphs don't work at the first attempt rerun all the notebook.
**Dependencies:** Apart from a standard Anaconda Python 3 installation, the project requires the following installations:

pandas_datareader # install with `pip install pandas-datareader`  
pydst # install with `pip install git+https://github.com/elben10/pydst`
