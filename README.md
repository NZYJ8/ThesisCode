# ThesisCode

Repository containing all major code used throughout MSc thesis. 

Codes for simulations, processing, and plotting were run in Jupyter Notebooks and have been compiled into functions, with commenting (which in some cases is extended to explain the rationale of various decisions), and saved within various .py files.
These functions are demonstrated in Jupyter Notebooks ([SimulationDemo](NotebookDemos/SimulationDemo.ipynb) and [PlottingDemo](NotebookDemos/PlottingDemo.ipynb), with the exception of those within ProcessHypsometry.py which are instead designed to be run within the terminal and thus are not demonstrated. Additionally note that Figure 4 was only added to the thesis a few days before the deadline and since its workflow is adapted from this [OGGM tutorial](https://tutorials.oggm.org/stable/notebooks/tutorials/full_prepro_workflow.html), I signpoint you to this notebook instead of including my own code for it. 

Whilst efforts have been taken to make these functions as reusable as possible, in some cases they are more finely tuned to the specific purpose of my thesis and would need tweaking for other uses. In many cases, given the size of the datasets produced during simulations, I relied upon trial and error to get bits of the code to work as I intended to so, whilst all functional, it is likely that some areas are less pythonic than others. 

For privacy, all filepaths have been replaced with 'custom_filepath'

OGGM v1.6.2 (latest release) was used for all simultions.
OGGM's documentation can be found [here](https://docs.oggm.org/en/stable/) and helpful code for OGGM can be found [here](https://tutorials.oggm.org/stable/notebooks/welcome.html)

Note: During the final formatting of the thesis, a number of small modifications were made to the plotting code to make some cosmetic updates to a number of figures, therefore these functions now don't 100% replicate the figures within the thesis, but they will be incredibly similar. 
