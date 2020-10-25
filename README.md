# LiveTickerPlotter
This is an IPython Notebook which will enable you to see the pricing changes, in the last 20 days, of any ticker supported by the IEX API. Currently, there's 9152 tickers you can choose from.

It includes a function that lets you change the y-axis of the chart to any value you want (default is closing price), and you can change the ticker list by supplying a different csv path.

# Requirements
To run this script locally, you'll need to install the following modules:

ipywidgets

pandas

IPython

plotnine

You can run this on the commandline (if you have pip installed) to install the dependencies:

pip install requirements.txt

(provided that you're in the same folder as requirements.txt - Else you can do pip install {packagename} for each of the 4 packages listed above)

You can also skip this step completely by running it in Google Colab:
https://colab.research.google.com/drive/1OL56HyJW-OnPl4EFJS-Z_28k2kq-vJ9Y?usp=sharing

# Usage
Usage is simple. First you need to run the first and second cells, so it loads the modules and displays a dropdown from where you can select your ticker.

Lastly, after you've selected your ticker, you only need to run the last cell and it will automatically plot a line plot. X axis is days ago, while the Y axis is the price itself.

I plan on adding more charts containing more info to this notebook in the future. Please let me know if there's anything cool you'd like to see here!
