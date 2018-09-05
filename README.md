# Getting familiar with vis.js

In this lab, you’ll make a small project using the Javascript library vis.js. This library is used extensively in your semester-long project, so getting to know it well is very important! The documentation for vis.js can be found here: <http://visjs.org/docs/network/>

Work with your partner on this lab. Practice pair programming. Push your changes to the `vis.html` file when you've finished the whole lab.

#### Instructions:

1.  Clone this project to your local computer.
2.  Open `vis.html` in both your browser and your favorite Javascript editor. (I recommend Atom with the "Atom Beautify" package installed.)
3.  On your browser, play with the graph that's displayed in the top-left corner. Zoom in, click, drag, etc.
4.  In your favorite Javascript editor, explore the code that creates the graph. Add 8 or more new nodes (should be at least 9). All nodes should have a unique id and a label with the name of a Raikes student in your cohort (try to include past/present roommates for each student). Both you and your partner for this lab need to be included.
5.  Add edges between two nodes if those two students have ever been roommates. Each edge should have a unique id. (Self-loops, or edges from a node back to itself, should not be included.)
6.  Before the graph is created, use the `options` object to make all the nodes red with black borders.
7.  Before the graph is created, use the `options` object to change the shape of the nodes to "box".
8.  After the network is created, add code to get the nodes that represent you and your partner, and set their color to be yellow with orange borders, even when selected (clicked on). Hint: use the "update" function of DataSet.
9.  For either your node or your partner's node, get the ids of the connected nodes (nodes which share an edge) and print them to the console.
