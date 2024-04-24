# 507final
A compilation of the necessary things to finish my 507 class. 

This document will be brief. Firstly, there were several packages that I imported to allow for the success of this project. The import statments I utilized are as follows: 
import pandas as pd
import numpy as np
import geopandas as gpd
import networkx as nx
import matplotlib.pyplot as plt
import json

Geopandas is not necessarily a reuirement, as one of my imported datasets was imported as a geojson but I ended up treating it like a regular json instead, thus nullifying the geopandas requirement. I also utilized Jupyter notebook instead of Python or Google Colab. That is a requirement. 

The instructions for interacting with my program are as follows: The program starts with a prompt asking the user to either enter a command or enter ‘help’ to see the options for commands. If the user is unfamiliar with the program and follows the prompt to type ‘help’ into their command line, they will be given a list of the available commands which appears like so:
 Available Commands:
    - filter [column] [condition]: Filters the data
    - sort [column]: Sorts the data by the given column
    - plot [type];[column name]: Plots the given column data as the specified type
    - exit: Exits the program
Note how these options specify the format that the user must enter their column and additional parameters for the program. Beneath these options, the program instantaneously displays the original prompt of either entering a command or ‘help’ for options. From there, the user can enter either filter, sort, plot, or exit. Filter allows the user to refine the data based on categories and values both determined by the user. Sort allows the user to view the data in specified order based on a chosen column. Plot allows the user to make graphs based on the column. Exit allows the user to leave the program. 

