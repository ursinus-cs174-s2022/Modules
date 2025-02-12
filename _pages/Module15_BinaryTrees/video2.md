---
layout: module
permalink: /Module15/Video2
title: "CS174: Module 15: Binary Trees: Inorder Traversal"
excerpt: "CS174: Module 15: Binary Trees: Inorder Traversal"

info:
  prev: "./Exercise1"
  next: "./Exercise2"
---

Please watch the video below, and click the next button once you have finished

<iframe width="560" height="315" src="https://www.youtube.com/embed/sSOLy7rNpd4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<h2>Notes</h2>


<ul>
<li>An <b>inorder traversal</b> can be defined as visiting the nodes in the order they are printed by the following recursive function
<p>
<pre><code>inorder(node)
    inorder(node->left)
    print(node)
    inorder(node->right)</code></pre>
</p>
</li>
<li>
If the nodes are setup so that for every node, the value in a node is greater than the values of all nodes in its left subtree and less than the values of all nodes in the right subtree, then an inorder traversal will visit the nodes in sorted order.
</li>
</ul>

<img src = "../images/Module15/BinaryTree_Inorder.png">
