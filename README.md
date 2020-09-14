# Asset-inventment-clustering-and-portfolio-optimisation

Using 42 unnamed assets historical performance to perform cluster analysis and portfolio optimisation

- Data
  The data contains 42 unnamed assets' historical daily trading prices between 1998 and 2019.

- Initial analysis

1. Initial analysis has found two broad types of assets, based on the daily return correlation matrix.
2. Deeper analysis on these two types of assets revealed different volitility levels, most clearly demonstrated by the price chart around 08, 09 financial crisis.

- Portfolio building

1. Using scipy minimise method to find a portfolio with the highest Sharpe ratio. This has found that most of the 42 assets are not contributing much to increasing return/reducing volitility.
2. Using the most important 4 assets to chart a the bullet shape of different portfolio performances built with different weights of these 4 assets.
3. Using the scipy minimise again to find the porfolio frontier, where given risk preference, average annual return is found.

- Comparison with SP500
  The comparison between the best Sharpe ratio portfolio and SP500 has found the porfolio to have higher Sharpe ratio, largely because of large propotion of safe (low volitility) assets.

To do:
Plot SP500 Sharpe ratio line on the bullet chart to find the cutting points where given the risk preference, whether portfolio or SP500 is the better option
