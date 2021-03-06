[![Build status](https://ci.appveyor.com/api/projects/status/de18xc6i431xnlvg?svg=true)](https://ci.appveyor.com/project/Dirkster99/treelib)

# TreeLib
This projects produces a
a ![.Net Standard](https://docs.microsoft.com/en-us/dotnet/standard/net-standard)
Library with Generic methods to travere k-nary trees (k >=1) in any order required.

The project in this repository contains a demo console project to demo its usage.

# Suported Generic Traversal Methods

## Breadth First
### Level Order
See TreeLib.BreadthFirst.Traverse.LevelOrder implementation for:

* trees with 1 root (expects &lt;T> root as parameter)
* trees with multiple root node (expects IEnumerable&lt;T> root as parameter)

## Depth First
### PreOrder
See TreeLib.BreadthFirst.Traverse.PreOrder implementation for:

* trees with 1 root (expects &lt;T> root as parameter)
* trees with multiple root node (expects IEnumerable&lt;T> root as parameter)

### Postorder
See TreeLib.BreadthFirst.Traverse.Postorder implementation for:

* trees with 1 root (expects &lt;T> root as parameter)
* trees with multiple root node (expects IEnumerable&lt;T> root as parameter)

# Tip
* Read about ![Generic Tree and Linked List Traversal in C#](http://www.codeducky.org/easy-tree-and-linked-list-traversal-in-c/) to understand the usefullnes of *Generic* traversal methods.

* Watch the
![Binary tree traversal: Preorder, Inorder, Postorder](https://www.youtube.com/watch?v=gm8DUJJhmY4)
video to better understand what is what (and why these Traversal Order Names make some sense):
