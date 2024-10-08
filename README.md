# 📚 Data Structures and Algorithms Cheat Sheet

استعراض شامل لهياكل البيانات والخوارزميات مع تصنيفها وشرح لكل منها. يمكنك استكشاف المواضيع المختلفة عبر الروابط التالية:

## 🔢 Data Structures
- **[Arrays and Strings](#arrays-and-strings)**  
    استكشاف مختلف العمليات على المصفوفات والنصوص.
    - <a href="#arrays" style="text-decoration: none; color: inherit;">📄 Arrays</a>  
    - <a href="#strings" style="text-decoration: none; color: inherit;">📄 Strings</a>  
    - <a href="#matrixgrid" style="text-decoration: none; color: inherit;">📄 Matrix/Grid</a>
- **[Linked Lists](#linked-lists)**  
    استعراض لهياكل البيانات المرتبطة واستخداماتها المتنوعة.
    - <a href="#singly-linked-list" style="text-decoration: none; color: inherit;">🔗 Singly Linked List</a>  
    - <a href="#doubly-linked-list" style="text-decoration: none; color: inherit;">🔗 Doubly Linked List</a>  
    - <a href="#circular-linked-list" style="text-decoration: none; color: inherit;">🔗 Circular Linked List</a>
- **[Stacks and Queues](#stacks-and-queues)**  
    دراسة هياكل التخزين المعتمدة على المبادئ LIFO وFIFO.
    - <a href="#stack" style="text-decoration: none; color: inherit;">🗂️ Stack</a>  
    - <a href="#queue" style="text-decoration: none; color: inherit;">🗂️ Queue</a>  
    - <a href="#priority-queue" style="text-decoration: none; color: inherit;">🗂️ Priority Queue</a>  
    - <a href="#deque" style="text-decoration: none; color: inherit;">🗂️ Deque</a>
- **[Trees](#trees)**  
    استكشاف الهياكل الشجرية وفروعها المتقدمة.
    - <a href="#binary-tree" style="text-decoration: none; color: inherit;">🌳 Binary Tree</a>  
    - <a href="#binary-search-tree-bst" style="text-decoration: none; color: inherit;">🌳 Binary Search Tree (BST)</a>  
    - <a href="#avl-tree" style="text-decoration: none; color: inherit;">🌳 AVL Tree</a>  
    - <a href="#red-black-tree" style="text-decoration: none; color: inherit;">🌳 Red-Black Tree</a>  
    - <a href="#b-tree" style="text-decoration: none; color: inherit;">🌳 B-Tree</a>  
    - <a href="#b-plus-tree" style="text-decoration: none; color: inherit;">🌳 B+ Tree</a>  
- **[Heaps](#heaps)**  
    دراسة الهياكل البيانية واستخداماتها في تنظيم الأولويات.
    - <a href="#binary-heap" style="text-decoration: none; color: inherit;">🔺 Binary Heap</a>  
    - <a href="#fibonacci-heap" style="text-decoration: none; color: inherit;">🔺 Fibonacci Heap</a>  
- **[Hashing](#hashing)**  
    التعرف على الجداول الهاشية ووظائف التجزئة.
    - <a href="#hash-tables" style="text-decoration: none; color: inherit;">#️⃣ Hash Tables</a>  
    - <a href="#hash-functions" style="text-decoration: none; color: inherit;">#️⃣ Hash Functions</a>  
- **[Graphs](#graphs)**  
    فهم تمثيل الرسوم البيانية وخوارزميات الاستكشاف.
    - <a href="#graph-representation-adjacency-matrixlist" style="text-decoration: none; color: inherit;">📊 Graph Representation (Adjacency Matrix/List)</a>  
    - <a href="#graph-traversal-dfs-bfs" style="text-decoration: none; color: inherit;">📊 Graph Traversal (DFS, BFS)</a>  
    - <a href="#spanning-trees" style="text-decoration: none; color: inherit;">📊 Spanning Trees</a>  
    - <a href="#shortest-path-algorithms-dijkstra-bellman-ford" style="text-decoration: none; color: inherit;">📊 Shortest Path Algorithms (Dijkstra, Bellman-Ford)</a>  

---

## ⚙️ Algorithms
- **[Sorting Algorithms](#sorting-algorithms)**  
    استعراض لمجموعة متنوعة من خوارزميات الترتيب.
    - <a href="#bubble-sort" style="text-decoration: none; color: inherit;">🔄 Bubble Sort</a>  
    - <a href="#selection-sort" style="text-decoration: none; color: inherit;">🔄 Selection Sort</a>  
    - <a href="#insertion-sort" style="text-decoration: none; color: inherit;">🔄 Insertion Sort</a>  
    - <a href="#merge-sort" style="text-decoration: none; color: inherit;">🔄 Merge Sort</a>  
    - <a href="#quick-sort" style="text-decoration: none; color: inherit;">🔄 Quick Sort</a>  
    - <a href="#heap-sort" style="text-decoration: none; color: inherit;">🔄 Heap Sort</a>  
    - <a href="#counting-sort" style="text-decoration: none; color: inherit;">🔄 Counting Sort</a>  
    - <a href="#radix-sort" style="text-decoration: none; color: inherit;">🔄 Radix Sort</a>  
- **[Searching Algorithms](#searching-algorithms)**  
    دراسة خوارزميات البحث عن البيانات.
    - <a href="#linear-search" style="text-decoration: none; color: inherit;">🔍 Linear Search</a>  
    - <a href="#binary-search" style="text-decoration: none; color: inherit;">🔍 Binary Search</a>  
- **[Dynamic Programming](#dynamic-programming)**  
    حل المشكلات المعقدة من خلال تخزين الحلول الجزئية وتحليلها.
    - <a href="#fibonacci-sequence" style="text-decoration: none; color: inherit;">🧮 Fibonacci Sequence</a>  
    - <a href="#longest-common-subsequence" style="text-decoration: none; color: inherit;">🧮 Longest Common Subsequence</a>  
    - <a href="#knapsack-problem" style="text-decoration: none; color: inherit;">🧮 Knapsack Problem</a>  
- **[Greedy Algorithms](#greedy-algorithms)**  
    استخدام خوارزميات الجشع لحل المشكلات بطرق سريعة وفعالة.
    - <a href="#huffman-coding" style="text-decoration: none; color: inherit;">💡 Huffman Coding</a>  
    - <a href="#kruskals-algorithm" style="text-decoration: none; color: inherit;">💡 Kruskal’s Algorithm</a>  
    - <a href="#prims-algorithm" style="text-decoration: none; color: inherit;">💡 Prim’s Algorithm</a>  
- **[Backtracking](#backtracking)**  
    تقنيات العودة لحل مشكلات الاستكشاف بطريقة منهجية.
    - <a href="#n-queens-problem" style="text-decoration: none; color: inherit;">🧩 N-Queens Problem</a>  
    - <a href="#sudoku-solver" style="text-decoration: none; color: inherit;">🧩 Sudoku Solver</a>  
- **[Divide and Conquer](#divide-and-conquer)**  
    تقسيم المشكلة إلى أجزاء صغيرة لحلها بشكل أكثر كفاءة.
    - <a href="#merge-sort" style="text-decoration: none; color: inherit;">⚔️ Merge Sort</a>  
    - <a href="#quick-sort" style="text-decoration: none; color: inherit;">⚔️ Quick Sort</a>  
    - <a href="#binary-search" style="text-decoration: none; color: inherit;">⚔️ Binary Search</a>  
- **[Graph Algorithms](#graph-algorithms)**  
    استعراض خوارزميات متقدمة تتعلق بالرسوم البيانية.
    - <a href="#depth-first-search-dfs" style="text-decoration: none; color: inherit;">🔗 Depth-First Search (DFS)</a>  
    - <a href="#breadth-first-search-bfs" style="text-decoration: none; color: inherit;">🔗 Breadth-First Search (BFS)</a>  
    - <a href="#dijkstras-algorithm" style="text-decoration: none; color: inherit;">🔗 Dijkstra’s Algorithm</a>  
    - <a href="#bellman-ford-algorithm" style="text-decoration: none; color: inherit;">🔗 Bellman-Ford Algorithm</a>  

---

## 📏 Complexity Analysis
- **[Time Complexity](#time-complexity)**  
    تحليل الزمن اللازم لتنفيذ الخوارزميات بفاعلية.
- **[Space Complexity](#space-complexity)**  
    تحليل الذاكرة المطلوبة لتنفيذ الخوارزميات بطريقة فعالة.
- **[Big O Notation](#big-o-notation)**  
    المبادئ الأساسية لتقييم تعقيد الخوارزميات.

---

## 📖 Resources for Learning
- <a href="https://www.geeksforgeeks.org/" style="text-decoration: none; color: inherit;">GeeksforGeeks</a>  
    مقالات شاملة وموسعة حول الخوارزميات وهياكل البيانات.
- <a href="https://www.programiz.com/" style="text-decoration: none; color: inherit;">Programiz</a>  
    دروس تعليمية سهلة ومباشرة للمبتدئين.
- <a href="https://www.w3schools.com/" style="text-decoration: none; color: inherit;">W3Schools</a>  
    تعلم البرمجة بأسلوب تفاعلي وسهل.
- <a href="https://www.tutorialspoint.com/" style="text-decoration: none; color: inherit;">TutorialsPoint</a>  
    شرح مفصل للعديد من المواضيع البرمجية.

---

> **🎯 ملاحظة:** يمكنك تعديل الروابط في هذا المستند لتشير إلى ملفاتك الخاصة بكل موضوع أو إضافة شرح مفصل في ملفات منفصلة.
