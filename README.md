# cse204-assignment-2-graph-solved
**TO GET THIS SOLUTION VISIT:** [CSE204 Assignment 2-Graph Solved](https://www.ankitcodinghub.com/product/cse204-assignment-2-graph-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96830&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE204 Assignment 2-Graph Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
You have been provided with two different implementations of a <em>Graph</em>: an adjacency matrix implementation (<em>GraphAdjMatrix.cpp</em>) and an adjacency list implementation (<em>GraphAdjList.cpp</em>). Please go through the two files thoroughly to understand each and every line of the program. &nbsp;Here <em>Graph</em> data structure has been implemented using a C++ class <strong>Graph</strong>. In addition to this class, two other classes are <strong>already and fully implemented</strong> in the file: <strong><em>Queue</em></strong> class to be used later by the BFS function of <strong><em>Graph</em></strong> and <strong><em>ArrayList</em></strong> class that has been used by the <strong><em>Graph</em></strong> class to store adjacency list information. Please understand these two helper classes carefully including the constructor and destructor functions.

The graph can be either directed or undirected. This choice will be given as input by the user.

The following functions are already implemented in the <strong>Graph</strong> class:

<ul>
<li><em>void setnVertices(int n)</em>: Sets the number of vertices in the graph. This function initializes the graph data structure by allocating memory for the graph storage.</li>
<li><em>void addEdge(int u, int v)</em>: Adds an edge (<em>u,v</em>) to the graph. In case of undirected graph, edge (<em>u,v</em>) is the same as edge (<em>v,u</em>).</li>
<li><em>void printGraph()</em>: Prints the graph in adjacency list format.</li>
</ul>
For this homework, you are required to add the following functions to the above implementations (<strong>both files</strong>):

Task 1: <em>void removeEdge(int u, int v)</em>: Removes the edge (<em>u, v</em>) from the graph.

Task 2: <em>bool isEdge(int u, int v):</em> Returns true if (<em>u, v</em>) is an edge, otherwise returns false.

Task 3: <em>int getDegree(int u, bool out=true)</em>: Returns the <strong>out degree</strong> of a vertex <em>u </em>if <em>out</em> is true. <em>out</em> is set to true as a default argument. If <em>out</em> is set to false while calling the function, the function should return the <strong>in degree </strong>of the vertex <em>u</em>.

Task 4: <em>void printAdjVertices(int u)</em>: Prints all adjacent vertices of <em>u</em>.

Task 5: <em>bool hasCommonAdjacent(int u, int v)</em>: Returns true if vertices <em>u</em> and <em>v</em> have some common adjacent vertices. Otherwise, it should return false.

Task 6: <em>void bfs(int source)</em>: Runs BFS algorithm on the graph using <em>source</em> as the source vertex. BFS statistics like parent, distance, and color information must be saved in class variables. So, you will need to define these as class private variables. Use the given <strong><em>Queue</em></strong> class in BFS. Define BFS related variables, i.e., parent, distance, and color, as class variables and initialize them memory appropriately in the <strong><em>Graph</em></strong> constructor.

Task 7: <em>int getDist(int u, int v)</em>: Returns the shortest path distance from vertex <em>u</em> to vertex <em>v</em>. You will first need to run BFS on the graph using <em>u</em> as the source vertex. Then, you will use the <em>dist</em> array to find the distance.

Task 8: Graph destructor function: Implement the destructor function for the <strong><em>Graph</em></strong> class. View the destructor functions of <strong><em>Queue</em></strong> and <strong><em>ArrayList</em></strong> to get some hints.

Task 9 (Bonus, <strong>not mandatory</strong>): Modify your adjacency list implementation to enable storing weighted graphs.

In a weighted graph, every edge (<em>u, v</em>) is associated with an integer weight <em>w</em>. For example, in a road network graph, we may need to store the distance of each road segment in the graph. In that case, we will require storing distance value as a weight of each edge that represent a road segment between two junctions.

So, modify your graph implementation (only the adjacency list form, because it is trivial to store weight in a matrix form) so that weight can be stored. Implement this in a <strong>separate file</strong> named <em>GraphAdjListWeighted.cpp </em>. All the functions mentioned above should be implemented in <em>GraphAdjListWeighted.cpp .</em> You can maintain an <strong><em>ArrayList</em></strong> named <em>weightList</em> to store weights of neighbor vertices (similar to <em>adjList</em>).

Several existing functions may need to be changed in <em>GraphAdjListWeighted.cpp</em> such as follows:

<ul>
<li><em>void addEdge(int u, int v, int w)</em> : Adds an edge (<em>u, v</em>) to the graph with weight value <em>w</em>.</li>
</ul>
Modify other class functions wherever required.

All the functions should consider <strong>both directed and undirected graph</strong>, whenever needed. Also, always check whether the vertex number is valid, i.e. between 0 and <em>nVertices</em> (inclusive).

Implementing Task 9 will result in 5 bonus marks.

Your final submission will consist of 2 (or 3) files:

<ul>
<li><em>cpp</em></li>
<li><em>cpp</em></li>
<li><em>cpp </em>(if you do Task 9)</li>
</ul>
Put these files in a folder. The folder should be named with your 7-digit student ID (like 1705001). Create a zipped version of the folder naming it with your 7-digit student ID (like 1705001.zip) and upload it in moodle within 13 July (Saturday) 11:59 pm.

You must also satisfy the following requirements:

<ul>
<li>Write main function codes in all 2 (or 3) cpp files to test all of the above tasks.</li>
<li>You must extend the given code.</li>
</ul>
&nbsp;

<strong><u>Marks: </u></strong>

<em>GraphAdjMatrix.cpp </em>– 10 marks, <em>GraphAdjList.cpp </em>– 10 marks,

<em>GraphAdjListWeighted.cpp </em>– Bonus
