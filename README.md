# mplstyle-for-finance

## About

A stylesheet compatible with the python library matplotlib - widely used for visualizations in python. It is designed to be suitable for plotting complex stock charts and making stock analytics, but can be used for any data visualization with matplotlib. Underneath you will find an example of the style being used for plotting both candlestick diagrams with volumes as well as just a simple stock chart.
#### Example: Candlestick diagram
![finance_dark_candlestick2](https://user-images.githubusercontent.com/63104057/84801336-54a76800-afff-11ea-9f32-86f1735771f1.jpg)

#### Example: Stock chart
![finance_dark_stock](https://user-images.githubusercontent.com/63104057/84801527-946e4f80-afff-11ea-97d7-97766d687f61.jpg)

## How to implement and use the finance_dark stylesheet

To use the style yourself, just download the mplstyle-file listed above and place it in your current folder where your other python-files and data is stored. To activate it in a session, just put the following code in your python program:
```python
plt.style.use('finance_dark.mplstyle')
```

Now, if you would like to be able to call the style like any other mplstyle, you are going to have to add it to your matplotlib styles-folder. 

Usually styles are stored under the path:  
```
~/.local/lib/python3.8/site-packages/matplotlib/mpl-data/stylelib
```
although your architecture might be different. To locate the styles-folder you can open the terminal and run:
```
find -name “*stylelib*“
```
Depending on the number of python environments you have installed on your computer, you will get a few hits. You wll find there are quite a few default styles present already, that may sound familiar - like ggplot.mplstyle or classic.mplstyle. After placing the stylesheet in the stylelib-folder, you will now be able to call it as any other style:
```python
plt.style.use('finance_dark')
```
## Requirements: python, matplotlib

Python is required for using the stylesheet (of course).

The library matplotlib is a requirement for using a mplstyle. If not already installed, you can do so by using the following code in the terminal:
```
pip install matplotlib
```
This will let you download and install any library (in this case the matplotlib library).

Be sure to import the matplotlib library for your program before using the style. Do so by writing the following code in the top of your program:
```python
import matplotlib as plt
```

## Free use

You can use and modify the stylesheet as you want. Feel free to report any bugs.  
