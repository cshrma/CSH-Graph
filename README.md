# CSH-Graph
String mapping Graph

<h4>Problem Statement</h4>
Design and code a responsive webpage which is a graph profile of a string of text. You need to have two input boxes in your UI design, where user can key-in his name and a string of text. The parent node of the graph will represent the given name. The other connected nodes of the graph would be alphabets of the given string; the more number of times an alphabet occurs in the string; the size of the node should represent the same (i.e. higher the occurrence bigger the child nodes). Ensure each alphabet is shown in a different colour node (circle) dynamically.

<h4>Resolution</h4>
A simple responsive webpage is created to map alphabets from a string to graph nodes. There are two input boxes in the UI design. 
1. Add a name in the first input field which acts as the root node of graph.
2. Add a string in the second input field. The other connected nodes of the graph would be alphabets of the given string. The size of each such node is proportional to the frequency of each alphabet, i.e., the higher the frequency of a given alphabet in the string, larger the size of node. Each alphabet is shown in a different color node.</br>
Installation: </br>
Download the project</br>
Export it to your-folder</br>
Start using the website</br></br>

<b>Code Explanation</b></br>
1. The Form Fields data is sent to script.js using angularJs.
2. The function getCounterArray() returns a map of String Characters and their frequency.
3. The function generateRandomColor() generates a hex color code.
4. The function getDataSet() returns the Data Object required by the vis.js graph.
5. The function getMapping() retuns the mapping between the Primary node and the nodes which is required for the vis.js graph.
