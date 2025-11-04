{\rtf1\ansi\ansicpg1252\deff0\nouicompat\deflang1033{\fonttbl{\f0\fnil\fcharset0 Calibri;}}
{\*\generator Riched20 10.0.19041}\viewkind4\uc1 
\pard\sa200\sl276\slmult1\f0\fs22\lang9                                  Breadth first search and Depth First Search\par
\par
\par
Program\par
graph = \{\par
 '5' : ['3','7'],\par
 '3' : ['2', '4'],\par
 '7' : ['8'],\par
 '2' : [],\par
 '4' : ['8'],\par
 '8' : []\par
\}\par
visited = set() # Set to keep track of visited nodes of graph.\par
def dfs(visited, graph, node): #function for dfs\par
 if node not in visited:\par
 print (node)\par
 visited.add(node)\par
 for neighbour in graph[node]:\par
 dfs(visited, graph, neighbour)\par
# Driver Code\par
print("Following is the Depth-First Search")\par
dfs(visited, graph, '5')\par
Output:\par
Following is the Depth-First Search\par
5\par
3\par
2\par
4\par
8\par
7\par
\par
}
