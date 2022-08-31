# Tutorial
In this tutorial you can learn how to use the visual knowledge graph browser.

## Table of contents
- [Creating a new graph](#creating-graph)
- [Basic operations on a graph](#basic-operations-on-graph)
- [Faceted filtering](#faceted-filtering)

<a id="creating-graph"></a>
## Creating a new graph
To start exploring a knowledge graph you first need to select a configuration.
This can be done in various ways as depicted on the following screenshot:  
<br>
![Selecting a meta-configuration](/tutorial-screenshots/selecting_a_meta-configuration.png)  
<br>
To select a configuration you can:  
**A)** Choose one of our existing meta-configurations  
**B)** Manually set the configuration using its IRI  
**C)** Open an existing graph which has a configuration already selected  

> **Note**  
> A meta-configuration is a set of specific configurations.

If you opt for **A** then you will also have to select a specific configuration as shown in the following screenshot (it shows how it looks when you choose the *Scientists* meta-configuration):  
<br>
![Selecting a configuration](/tutorial-screenshots/selecting_a_configuration.png)  
<br>
After that you will be asked to choose a starting node for your exploration (the following screenshot was taken after choosing the *Scientists* configuration):  
<br>
![Selecting a starting node](/tutorial-screenshots/selecting_a_starting_node.png)  
<br>
If you choose Albert Einstein, you will end up with this screen:  
<br>
![Initial screen with a graph](/tutorial-screenshots/initial_screen_with_a_graph.png)  
<br>

<a id="basic-operations-on-graph"></a>
## Basic operations on a graph
You can interact with the tool in the following ways as shown in the following screenshot:  
<br>
![Basic operations on a graph](/tutorial-screenshots/basic_operations_on_a_graph.png)  
<br>
**A)** Menu - There you can find settings and perform various actions  
**B)** Search bar - You can search for a node in the graph  
**C)** Node's views - You can use the *expand* buttons to incrementally expand the node   

<a id="faceted-filtering"></a>
## Faceted filtering
When you want to filter a graph you can click the **filtering** tab next to the menu.  
<br>
![Filtering](/tutorial-screenshots/filtering.png)  
<br>
Here's what the buttons do:
- Filter - filters nodes in the graph using filtering criteria that you have set
- Reset - shows all hidden nodes and also unchecks all checkboxes and sets sliders to their extrema
- Reload facets - when you delete nodes some of the facets may end up in an inconsistent state (there may be some information in the facets that aren't in the graph anymore). After clicking this button the facets will be recomputed and they will be in a correct state
