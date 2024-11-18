# Upskill Problems


### Optional Hwk08 - Due Sunday, Dec 1st

This is our final problem set and we're going to do something different.  First, this is an optional assignment.  I'll drop everyone's lowest homework score so if you decide to skip this homework, you'll get a zero for it and it will not be used in calculating your course average.  Second, you'll use generative AI (any one you want) for some of the problems and you'll do independent work for others of the problems.

**The rules:**
(a) only use generative AI if a TODO is prefixed with "GenAI Prompt:",
(b) only use the quoted text I provide with that prompt, and 
(c) don't use generative AI for anything else in solving these problems.

#### Binary Trees

1. GenAI Prompt:  "What is a binary tree?"  Read until you understand the words.
2. GenAI Prompt:  "Implement a Java binary tree."  Read until you understand the code.
3. Add the genAI binary tree code to an Android Studio project and run it.
4. Create a MeAtRootFamilyTree class.  Include your info at the root, your parents info at the next level, your grandparents info at the next level,  your great-grandparents info at the next level, finally, your great-great grandparents info is at the leaf level.  Just make up info for any family members you don't know but prepend an asterisk to those made up names.  Each person's info includes the name, the birth and death dates, and their state of birth.  The maternal info is always on the right side of the tree and the paternal info is always on the left side of the tree.
5. Traverse your tree using only root.left and root.right to output your mother's info, then your grandfather's info, then your great-grandmother's info, and then your great-great grandfather's info.
6. Output your tree using inOrderTraversal().  Make sense of the output by relating the output to #5's output.  Also output your tree using pre-order and post-order traversals.
7. Output the name-age pairs of everyone in your family tree.
8. Search your family tree for the state of your birth and return the percentage of your family tree that was born in the same state.
9. How many in your family tree were lucky enough to be alive when you were born?
10. Return a list of all the names in your family tree of people who were alive during Obama's presidency.
11. Create a list of people (not just names) who have an asterisk prepended to their name(s).
12. GenAI Prompt: "Java implementation of level order traversal of a binary tree".
13. Create a list of people (not just names) who have an asterisk prepended to their name(s but this time include their relationship to you.
14. GenAI Prompt: "Java implementation of level order traversal using a List of children".  Notice that this implement is different than the previous left/right binary tree implementation.  In your own words, describe how these implementations differ.
15. Create a FamilyTree class that has your info and siblings at the root, your parent's info and siblings at the next level, your grandparents info and siblings at the next level,  your great-grandparents info and siblings at the next level, finally, your great-great grandparents info and siblings at the leaf level.  Just make up info for any family members you don't know but prepend an asterisk to those made up names.  If you're unsure of the names of siblings, call a funtion that randomly chooses 0..10 names from these names [Ahmed, Ashleigh, Atravian, Chioma, Darren, Destinee, Dominick, Jalen, Jayce, Joneya, Kendall, Michael, Rodney, Ryan, Shawn, Tristian, William, Zharia] and prepend an asterisk to those randomly chosen names.

#### Binary Search Trees

16. GenAI Prompt:  "What is a binary search tree?"  Read until you understand the words.  How does a BST differ from a binary tree?
17. GenAI Prompt:  "Why is BST called a search tree?"
18. GenAI Prompt:  "Implement a Java BST".  Read until you understand the code.  Compare this code to the earlier binary tree code.  How does it differ?
19. Add the genAI BST code to an Android Studio project and run it.
20. Output the BST using pre-order, in-order, and post-order traversal.  Does either of these traversal methods order the elements in the BST?
21. Build a BST of family members (no siblings) based on the shuffled values from your previous family trees.  Use the BST property based on the age of each family members. Output your family BST.
22. GenAI Prompt: "What is the height of a BST in Java?"  Add this method to your BST code and read repeatedly until you understand how that recursive code works.
23. Write a recursive method that returns the name of the oldest person in your BST.
24. Write a recursive method that returns the name of the youngest person in your BST.
25. Write a recursive method that returns the name of the oldest person in your BST.
26. Write a recursive method that returns a list of the names in the Nth level (or depth).
27. GenAI Prompt: "What is a perfect, a full, and a complete binary tree?"  Read carefully.  You'll see this again in Algorithms and in Discrete Math.
28. Write a recursive method that returns true if your BST is perfect, otherwise returns false.
29. Build your own perfect binary tree of at least 6 nodes and output in pre-order traversal.
30. Build your own full binary tree of at least 6 nodes that is not perfect and output in in-order traversal.
31. Build your own complete binary tree of at least 6 nodes that is not perfect or full and output in post-order traversal.
32. What is the total of all the ages in your family BST?
33. How many nodes in your family BST?
34. Does the left side of your family BST have more nodes than the other side of your family BST?
35. Use [VisualGo](https://visualgo.net/en/bst?slide=1) to explore BSTs.

#### Graphs

36. GenAI Prompt: "What is a Java graph that stores an adjacency matrix as a 2d list?"  Read carefully.  You'll see this again in Algorithms and in Discrete Math.  Run the generated code.
37. GenAI Prompt: "What is a Java graph that stores an adjacency list as a map?"  Read carefully.  You'll see this again in Algorithms and in Discrete Math.  Run the generated code.
38. Use [VisualGo](https://visualgo.net/en/graphds?slide=1) to explore graphs.
39. Build a graph of the A-E parking lots shown [here](https://www.xula.edu/mainstudent/mainstudent-asset/final-updated-xula-map.jpg).  The vertices are the 5 parking lot letters.  Each edge is a street that joins two lots.  You graph should have at least 7 edges.
40. GenAI Prompt:  "How does BFS work?"
41. GenAI Prompt:  "How does BFS web crawling work?"
42. GenAI Prompt:  "How does BFS find the shortest path in a maze?"
43. Use [VisualGo](https://visualgo.net/en/dfsbfs?slide=1) to explore BFS and DFS graph traversal methods.
44. Based only on watching VisualGo and [this](https://www.cs.usfca.edu/~galles/visualization/DFS.html) visualization, in your own words, explain how DFS works.
45. Why does BFS use a queue?  Why does DFS use a stack?  Why do both BFS and DFS use a visited list?
46. GenAI Prompt: "What is Dijkstra's Single Source Shortest Path algorithm in Java?"
47. In your own words, explain how DSSSP is related to Google Maps?


#### Lots of value in participating in open source projects
48. Watch [this](https://www.youtube.com/watch?v=CML6vfKjQss), [this](https://www.youtube.com/watch?v=v2X51AVgl3o), and [this](https://www.youtube.com/watch?v=RGd5cOXpCQw).
49. List the URLs of 3 interesting open source projects.  For each of those projects, list 3 issues and the issue numbers of contributions you think you can make.

