# 4. Model Linkage

The linkages between SATIM and eSAGE involve an **iterative process** that facilitates the exchange of information. In this context, alternate runs of SATIM and eSAGE are performed from the initial year to the end year, with the modeling frameworks exchanging information via **data links**.

During these exchanges, SATIM performs optimization for the entire period, with investment adjustments and changes in electricity generation cost being passed on to eSAGE, which in turn uses this information to calculate changes in electricity prices over time. Notably, adjustments to production coefficients in the eSAGE model are made based on the results of SATIM, particularly for the use of energy in economic activities beyond just electricity. Additionally, eSAGE adjusts household energy consumption, including transportation, based on the results provided by SATIM.

It's important to highlight that eSAGE is a **myopic dynamic model**, where the Social Accounting Matrix (SAM) is rebalanced annually. The shocks imposed by SATIM in the in-between periods are iteratively used to adjust the SAM, reflecting the adjustments made in each period as a result of the interaction between SATIM and eSAGE.

More information on the linkage between the models can be found in the working paper linked [here](https://www.wider.unu.edu/sites/default/files/wp2017-40.pdf) *(P6-7)*.