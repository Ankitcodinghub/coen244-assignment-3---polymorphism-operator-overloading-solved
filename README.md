# coen244-assignment-3---polymorphism-operator-overloading-solved
**TO GET THIS SOLUTION VISIT:** [COEN244 Assignment 3 – Polymorphism + Operator Overloading Solved](https://www.ankitcodinghub.com/product/coen244-assignment-3-polymorphism-operator-overloading-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96239&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COEN244 Assignment 3 – Polymorphism + Operator Overloading Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>Problem statement
A Graph is formally define as G=(N,E) consisting of the set N of vertices (or nodes) and the set E of edges, which are ordered pairs of the starting vertex and the ending vertex. Each vertex has ID and value as its basic attributes. Each edge has weight, starting vertex and ending vertex.

A Graph can be a directed graph where vertices are connected by edges, and all the edges are directed from one vertex to another.

A Directed Acyclic Graph (DAG) is a finite directed graph with directed cycles. This means from any vertex v, there is no way to follow a sequence of edge that eventually loops back to v again.

An undirected graph is a graph where the edges are bidirectional.

The definition of the abstract class Graph is provided below. Note that all its member functions are pure virtual. This is because the implementation of these functions is different from one graph to another. You are allowed to slightly modify this class by adding new member functions.

class Graph{ public:

Graph();

virtual ~Graph();

//add in one vertex; bool returns if it is added successfully.

virtual bool addVertex(Vertex&amp; v)=0;

virtual bool addVertices(Vertex* vArray) = 0;

//the edges that has connection with this vertex need to be removed; virtual bool removeVertex (Vertex &amp;v)= 0;

//remove a edge; as a result, some node may remain as orphan. virtual bool addEdge(Edge&amp; e) = 0;

// remove the edge

virtual bool remove(Edge&amp; e)=0;

// return bool if a vertex exists in a graph; virtual bool searchVertex(const Vertex&amp; v) = 0;
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1/2

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
COEN 244 – Winter 2022

</div>
</div>
<div class="layoutArea">
<div class="column">
// return bool if a Edge exists in a graph;

virtual bool searchEdge(const Edge&amp; e) =0;

// display the whole graph with your own defined format

virtual void display() const = 0;

// convert the whole graph to a string such as 1‐2‐4‐5; 1‐3‐5; each path is separated by ‘;’ or just print the edges of the graph as a list

// define your own format of a string representation of the graph.

virtual string toString () const = 0; //remove all the vertices and edges; virtual bool clean() = 0;

// you may consider the following in your project:

// add/remove a set of edge; as a result, some node may remain as orphan.

//virtual bool addEdges(Edge* eArray) = 0; //virtual bool removeEdges(Edge* eArray) = 0; // display the path that contains the vertex; virtual void display(Vertex&amp; v) const = 0;

// display the path that contains the edge; virtual void display(Edge&amp; e) const = 0;

};

Problem 1: Abstract Class and Polymorphism

1. Create a class Vertex and Edge to represent the vertices and edges of a graph. Provide programming code of your classes.

2. Create a concrete derived class of Graph. It can be directed, undirected or DAG. Provide full code of the derived class.

3. Create a driver class with the main function to test the creation of a graph, and invoking each member function.

Problem 2: Operator Overloading

Improve the class created in Problem 1 by overloading the operators =, ==, ++, &lt;&lt;, &gt;, +. These operators are defined as follows

<ol>
<li>G1 == G2 returns true if G1 and G2 have the exact same vertices and edges</li>
<li>G1 = G2, assign Graph G2 to Graph G1;</li>
<li>G++ and ++G, increases the weights of all edges by one;</li>
<li>G3 = G1 + G2, returns a graph that contains all the nodes of G1 and G2, all the edges of
G1 and G2;
</li>
<li>G1 &gt; G2, returns boolean if the sum of weights of G1’ edges are larger than the sum of
weights of G2’s edges.
</li>
<li>&lt;&lt;G outputs the graph G.</li>
<li>Create a driver class with the main function to test the creation of graphs, and</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
invoking each operator.

</div>
</div>
<div class="layoutArea">
<div class="column">
2/2

</div>
</div>
</div>
