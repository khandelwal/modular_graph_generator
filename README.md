# Random Modular Network Generator

This is the source code used for the following paper:

Sah, Pratha\*, Lisa O. Singh, Aaron Clauset, and Shweta Bansal. "Exploring community structure in biological networks with random graphs." BMC Bioinformatics 2014, 15:220\. doi:10.1186/1471-2105-15-220

This Python script generates undirected, simple, connected graphs with a specified degrees and pattern of communities, while maintaining a graph structure that is as random as possible.

email: ps875@georgetown.edu, sb753@georgetown.edu

Please cite the paper above, if you use our code in any form or create a derivative work.

# Dependencies

* Python 3.8 or higher
* Networkx 3.3 or higher
* NumPy 1.24 or higher
* Matplotlib 3.7 or higher

You can install all dependencies using pip:
```bash
pip install -r requirements.txt
```

# Usage

For a quick demo of the code, open the script "random\_modular\_generator\_variable\_modules.py" and scroll down to the _main_ function. Adjust the model parameters, degree distribution function and module size distribution function and run in terminal using the command:

```bash
python random_modular_generator_variable_modules.py
```

# Sample Code

For users unfamiliar with Python, I have uploaded a sample code file (mock\_code.py) demonstrating how the graph generator can be imported and used in a script. The mock code can be run using the command:

```bash
python mock_code.py
```

# Output

The code saves the adjacency matrix of the generated random modular graph under the filename 'adjacency\_matrix.txt'. The graph is also saved in a graphml format under the filename "random\_modular\_graph.graphml". The graphml file can be uploaded in Gephi (<http://gephi.github.io/>) for graph visualization. Note that Gephi currently does not have a layout plugin to visualize modular graphs. In the near future, I am planning to add a function in random-modular-network-generator.py code to assign each node a particular coordinate that allows easy visualization of modules (I have done this in Figure 2). Shoot us an email if you need this feature sooner than later.

# Sample Output Graph

![alt tag](https://github.com/prathasah/random-modular-network-generator/blob/master/Figure2.jpg)

Modular random graphs with network size = 150, 375 edges, 3 modules (or communities) of size, *s* = 50 and degree distribution is power law with modularity values of: a) *Q* = 0.1; b) *Q* = 0.3; and c) *Q* = 0.6. 

From Figure 2, Sah *et al.* (2014)

=========




