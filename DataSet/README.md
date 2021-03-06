# Dataset Description

The dataset presented consists of 2279 SKUs i.e., observation points with 9 features.
Selected features only include numerical data and a lot of information beyond what is utilized
by a classical ABC analysis. Each observation corresponds to a loaded pallet. Each of the features have a contribution on the inventory management. These
features can be classified on the basis of their nature of impact in two groups: handling-
related features (expiry date, pallet height, number of units per pallet and pallet weight) and
turnover-related features (total outbound and number of outbound orders). The turnover
related feature even though look redundant are made into different factors, because both the
demand size and the demand frequency are important to the problem. The missing data is denoted by 0 in the dataframe.

This dataset was obtained by the work of:

Jackson, Ilya & Avdeikins, Aleksandrs & Tolujew, Juri. (2019). "Unsupervised Learning-Based Stock Keeping Units Segmentation: Selected Papers from the 18th International Conference on Reliability and Statistics in Transportation and Communication", RelStat’18, 17-20 October 2018, Riga, Latvia. 10.1007/978-3-030-12450-2_58.
