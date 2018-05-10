# 3D Force Graph
Spring 2018 | Geography 4/572 | Geovisualization: Geovisual Analytics 

**Attribution:** [Vasco Asturiano](https://github.com/vasturiano)

The force graph is created using D3 which is a JavaScript library used for visualizing data with HTML, SVG, and CSV. The graph will be comprised of nodes and links connecting informaiton to form a graph that will have the ability to allow users to maipulate the graph through pulling the nodes, roatating the graph (since it has a 3D aspect), and mouse over to view the data that each node represents. 

## 1. Set up the workspace

In your IDE (Webstorm), open a blank `HTML` document to prepare for editing.

We will begin by adding the `d3.js` file to your blank `HTML` by adding it inside the `head` tag.

```JavaScript
<script src="https://unpkg.com/3d-force-graph@1.31.4/dist/3d-force-graph.js"></script>
```

Once you have done that your document should look like this with the `d3.js` inside the `head` tag.

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <script src="https://unpkg.com/3d-force-graph@1.31.4/dist/3d-force-graph.js"></script>
</head>
<body>

</body>
</html>
```

