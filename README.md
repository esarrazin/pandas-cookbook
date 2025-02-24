Pandas cookbook
===============

**Fork from https://github.com/jvns/pandas-cookbook**

[pandas](http://pandas.pydata.org/) is a Python library for doing
data analysis. It's really fast and lets you do exploratory work
incredibly quickly.

The goal of this cookbook is to give you some concrete examples for
getting started with pandas. The [docs](http://pandas.pydata.org/pandas-docs/stable/)
are really comprehensive. However, I've often had people
tell me that they have some trouble getting started, so these are
examples with real-world data, and all the bugs and weirdness
that entails.

It uses 3 datasets:

* 311 calls in New York
* How many people were on Montréal's bike paths in 2012
* Montréal's weather for 2012, hourly

It comes with batteries (data) included, so you can try out all the
examples right away.

Table of Contents
=================


* [A quick tour of the Jupyter Notebook](cookbook/A%20quick%20tour%20of%20%20Notebook.ipynb)
  <br> Shows off Jupyter's awesome tab completion and magic functions.
* [Chapter 1: Reading from a CSV](cookbook/Chapter%201%20-%20Reading%20from%20a%20CSV.ipynb)
  <br> Reading your data into pandas is pretty much the easiest thing. Even when the encoding is wrong!
* [Chapter 2: Selecting data & finding the most common complaint type](cookbook/Chapter%202%20-%20Selecting%20data%20&%20finding%20the%20most%20common%20complaint%20type.ipynb)
  <br>It's not totally obvious how to select data from a pandas dataframe. Here I explain the basics (how to take slices and get columns)
* [Chapter 3: Which borough has the most noise complaints? (or, more selecting data)](cookbook/Chapter%203%20-%20Which%20borough%20has%20the%20most%20noise%20complaints%20%28or%2C%20more%20selecting%20data%29.ipynb)
  <br>Here we get into serious slicing and dicing and learn how to filter dataframes in complicated ways, really fast.
* [Chapter 4: Find out on which weekday people bike the most with groupby and aggregate](cookbook/Chapter%204%20-%20Find%20out%20on%20which%20weekday%20people%20bike%20the%20most%20with%20groupby%20and%20aggregate.ipynb)
  <br> The groupby/aggregate is seriously my favorite thing about pandas and I use it all the time. You should probably read this.
* [Chapter 5: Combining dataframes and scraping Canadian weather data](cookbook/Chapter%205%20-%20Combining%20dataframes%20and%20scraping%20Canadian%20weather%20data.ipynb)
  <br>Here you get to find out if it's cold in Montreal in the winter (spoiler: yes). Web scraping with pandas is fun!
* [Chapter 6: String operations! Which month was the snowiest?](cookbook/Chapter%206%20-%20String%20Operations-%20Which%20month%20was%20the%20snowiest.ipynb)
  <br> Strings with pandas are great. It has all these vectorized string operations and they're the best. We will turn a bunch of strings containing "Snow" into vectors of numbers in a trice.
* [Chapter 7: Cleaning up messy data](cookbook/Chapter%207%20-%20Cleaning%20up%20messy%20data.ipynb)
  <br> Cleaning up messy data is never a joy, but with pandas it's easier &lt;3
* [Chapter 8: Parsing Unix timestamps](cookbook/Chapter%208%20-%20How%20to%20deal%20with%20timestamps.ipynb)
  <br> This is basically a quick trick that took me 2 days to figure out.
* [Chapter 9 - Working with geospatial data.ipynb](cookbook/Chapter%209%20-%20Working%20with%20geospatial%20data.ipynb)
  <br> How to work with geospatial data.

How to use this cookbook
========================

To install locally, you can get these using [pixi](https://pixi.sh/latest/)

```bash
git clone https://github.com/esarrazin/pandas-cookbook.git
cd pandas-cookbook
pixi install
pixi shell
jupyter-lab
```

A tab should open up in your browser at `http://localhost:8888`

Happy pandas!

License
=======

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

