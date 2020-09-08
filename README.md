## Graph visualization

Codes in this depository suggest how to plot graphs, incorporate information about edges weight and nodes size and degree, and make an animated plot of dynamiccally evolving graphs.

<p>&nbsp;</p>

### Plotting graphs

__graph_builder.ipynb__ takes a network of technology clusters in table format, builds year-specific graphs from it with varying node size, coloring according to the degree and weight-specific edge width.


<p>&nbsp;</p>

### Making an animated plot

__graph_dynamics.ipynb__ shows how to take a collection of images and create an animation out of them using annual plots of technology cluster network as an example.


<p>&nbsp;</p>

### Libraries needed:

* re
* numpy
* pandas
* string
* networkx
* matplotlib.plot
* cv2
* os.path

