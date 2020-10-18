# LiveTickerPlotter
This is an IPython Notebook which will enable you to see the pricing changes, in the last 20 days, of any ticker supported by the IEX API. Currently, there's 9152 tickers you can choose from.
# Requirements
To run this script locally, you'll need to install the following modules:

ipywidgets

pandas

IPython

plotnine

You can also skip this step completely by using the Google Colab file:

# Usage
Usage is simple. First you need to run the first and second cells, so it loads the modules and displays a dropdown from where you can select your ticker.

Lastly, after you've selected your ticker, you only need to run the last cell and it will automatically plot a line plot. X axis is days ago, while the Y axis is the price itself.
I plan on adding more charts containing more info to this notebook in the future. 
