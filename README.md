Asset Management Advisor

This project is part of a data science portfolio constructed by Srikesava Ghadiyaram.

The purpose of this project is to perform exploratory data analysis (EDA) to help Teclov, a hypothetical venture capitalist firm select companies to invest in based on criteria such as investment size and type, as well as the location and popularity of the company among investors. The data used is real investment data and therefore can potentially provide meaningful insights into investment patterns that real companies with similar strategies to Teclov could employ.

Methods Used:

	-Data Visualization

	-Inferential Statistics


Technologies:

	-Python

	-NumPy/Pandas

	-Matplotlib/Seaborn



Teclov is a hypothetical investment firm looking for new companies to invest in. Its investment strategy largely centers around investing in companies that have also attracted other outside investment, as there are likely to be safer bets. Additionally, Teclov would like to invest primarily in companies based in English-speaking countries for ease of conducting business. The investment strategy further entails selecting investment opportunities based on funding round and market sector, as these are correlated with the amount of attention from investors a company is likely to receive.

The data is taken from crunchbase.com and is divided into three separate files (mapping, companies, and rounds2). After cleaning the data using NumPy and Pandas, we utilize various data visualization techniques in matplotlib and Seaborn such as boxplots, pairplots, countplots, and barplots, we aim to compare groups of companies using various criteria such as investment round, country, and sector in order to identify which of each of these characteristics offers the most attractive investment opportunity to Teclov. The main challenge faced when working with this dataset was cleaning, as many of the company and investment listings were incomplete, and determining which entries should be discounted without discarding too many and skewing results was crucial to the accuracy of the results. The first two notebooks detail the cleaning process while the last notebook contains country, funding round, and sector analysis.

While further analysis would need to be done to conclusively identify individual candidates for investment, this exploratory analysis helps to identify the types of companies Teclov should look at when searching for candidates that fit their criteria for potential investment.
