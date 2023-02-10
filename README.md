<!DOCTYPE html>
<html>

<head>
    <title>Graph v/s Tree</title>
    <style>
        body {
            background-color: #fcfaf7;
        }
    </style>
</head>

<body>
    <p id="top" align="right"><a href="#bottom"><img
                src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR9ejiGGFJF3XA_FoQIuaM9zgumwC_rjQSDmt4BF2kP7s8h7EVkocrrcAAXY2WDloXRuPE&usqp=CAU"
                height="50" width="50"></a>
    </p>
    <h1 align="middle"><b><img height=200 width=500
                src="https://static.javatpoint.com/ds/images/tree-vs-graph-data-structure5.png"></b></h1>
    <hr>
    <hr>
    <h2><a href="https://www.geeksforgeeks.org/graph-data-structure-and-algorithms/">Graph:</a></h2>
    <p>A graph is a collection of two sets V and E where V is a finite non-empty set of vertices and E is a finite
        non-empty set of edges.</p>
    <ul>
        <li>Vertices are nothing but the nodes in the graph.</li>
        <li>Two adjacent vertices are joined by edges.</li>
        <li>Any graph is denoted as G = {V, E}.</li>
    </ul>
    <h3>For example:</h3>
    <p aling="middle"><img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/undirectedgraph.png" height="300"
            width="600"></p>
    <p>G = {{V1, V2, V3, V4, V5, V6}, {E1, E2, E3, E4, E5, E6, E7}} </p>
    <p align="middle"><iframe width="560" height="315" src="https://www.youtube.com/embed/1n5XPFcvxds"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe></p>
    <hr>
    <hr>
    <h2><a href="https://www.geeksforgeeks.org/binary-tree-data-structure/">Tree:</a></h2>
    <p>A tree is a finite set of one or more nodes such that :</p>
    <a
        href="https://practice.geeksforgeeks.org/courses/Data-Structures-With-Python?utm_source=geeksforgeeks&utm_medium=inarticle_dsapython_diffbetweeen&utm_campaign=inbound_promotions">
        <img src="https://media.geeksforgeeks.org/wp-content/post-ads-banner/2023-02-03-18-25-40-dsa-python.png"
            height="300" width="800"></a>
    <ol>
        <li>There is a specially designated node called root.</li>
        <li>The remaining nodes are partitioned into n>=0 disjoint sets T1, T2, T3, …, Tn<br>
            where T1, T2, T3, …, Tn are called the subtrees of the root.</li>
    </ol>
    <p>The concept of a tree is represented by following Fig.</p>
    <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/binary-tree-to-DLL.png" height="300" width="400">
    <hr>
    <hr>
    <h1 align="middle"><b>Difference between graph and tree</b></h1>
    <p align="middle">
    <table>
        <thead>
            <th><mark>The basis of Comparison</mark></th>
            <th><mark>Graph</mark></th>
            <th><mark>Tree</mark></th>
        </thead>
        <tbody>
            <tr>
                <th>Definition</th>
                <td>Graph is a non-linear data structure.</td>
                <td>Tree is a non-linear data structure.</td>
            </tr>

            <tr>
                <th>Structure</th>
                <td>It is a collection of vertices/nodes and edges.</td>
                <td>It is a collection of nodes and edges.</td>
            </tr>

            <tr>
                <th>Edges</th>
                <td>Each node can have any number of edges.</td>
                <td>If there is n nodes then there would be n-1 number of edges</td>
            </tr>

            <tr>
                <th>Edges</th>
                <td>Each node can have any number of edges.</td>
                <td>If there is n nodes then there would be n-1 number of edges</td>
            </tr>

            <tr>
                <th>Types of Edges</th>
                <td>They can be directed or undirected</td>
                <td>They are always directed</td>
            </tr>

            <tr>
                <th>Root node</th>
                <td>There is no unique node called root in graph.</td>
                <td>There is a unique node called root(parent) node in trees.</td>
            </tr>

            <tr>
                <th>Loop Formation</th>
                <td>A cycle can be formed.</td>
                <td>There will not be any cycle.</td>
            </tr>

            <tr>
                <th>Traversal</th>
                <td>For graph traversal, we use <br>Breadth-First Search (BFS), and <br> Depth-First Search (DFS).</td>
                <td>We traverse a tree using in-<br>order, pre-order, or post-<br>order traversal methods.</td>
            </tr>

            <tr>
                <th>Applications</th>
                <td>For finding shortest path in networking graph is used.</td>
                <td>For game trees, decision trees, the tree is used.</td>
            </tr>
        </tbody>
    </table>
    </p>
    <hr>
    <hr>
    <h1>Feedback:</h1>
    <form>
        <h3>Email&nbsp;&nbsp&nbsp;&nbsp;&nbsp;&nbsp;:<input type="text"></h3>
        <h3>Comment:<input type="text"></h3>
        <input type="submit">
    </form>
    <hr>
    <hr>
    <p align="middle" id="bottom">
        <a href="https://www.geeksforgeeks.org/"><img
                src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210420155809/gfg-new-logo.png"></a>
    </p>
    <p align="right"><a href="#top"><img src="https://i.pinimg.com/736x/ed/6e/12/ed6e12fea429c904d76b9009d4b81d18.jpg"
                height="50" width="50"></a></p>
</body>

</html>
