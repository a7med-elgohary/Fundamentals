# 📚 Data Structures and Algorithms Cheat Sheet

استعراض شامل لهياكل البيانات والخوارزميات مع تصنيفها وشرح لكل منها. يمكنك استكشاف المواضيع المختلفة عبر الروابط التالية:

## 🔢 Data Structures

- **[Arrays and Strings](#arrays-and-strings)**  
    - استكشاف العمليات المختلفة على المصفوفات والنصوص.
    - 🔍 **ملاحظة:** المصفوفات تُستخدم للوصول السريع إلى العناصر، بينما السلاسل النصية تُستخدم لمعالجة البيانات النصية.
    - [Arrays](#arrays)
    - [Strings](#strings)
    - [Matrix/Grid](#matrixgrid)

- **[Linked Lists](#linked-lists)**  
    - هياكل البيانات المرتبطة واستخداماتها.
    - 🔍 **ملاحظة:** توفر القوائم المرتبطة مرونة في إدارة البيانات مقارنة بالمصفوفات.
    - [Singly Linked List](#singly-linked-list)
    - [Doubly Linked List](#doubly-linked-list)
    - [Circular Linked List](#circular-linked-list)

- **[Stacks and Queues](#stacks-and-queues)**  
    - هياكل التخزين القائمة على المبادئ LIFO وFIFO.
    - 🔍 **ملاحظة:** تُستخدم الأكوام (Stacks) في معالجة البيانات بشكل عكسي، بينما تُستخدم الطوابير (Queues) لترتيب البيانات.
    - [Stack](#stack)
    - [Queue](#queue)
    - [Priority Queue](#priority-queue)
    - [Deque](#deque)

- **[Trees](#trees)**  
    - الهياكل الشجرية وفروعها المتقدمة.
    - 🔍 **ملاحظة:** تُستخدم الأشجار في تنظيم البيانات بشكل هيراركي مما يسهل البحث والتعديل.
    - [Binary Tree](#binary-tree)
    - [Binary Search Tree (BST)](#binary-search-tree-bst)
    - [AVL Tree](#avl-tree)
    - [Red-Black Tree](#red-black-tree)
    - [B-Tree](#b-tree)
    - [B+ Tree](#b-plus-tree)

- **[Heaps](#heaps)**  
    - هياكل البيانات الهرمية واستخداماتها في ترتيب الأولويات.
    - 🔍 **ملاحظة:** تُستخدم الهرمات (Heaps) في تطبيقات تنظيم الأولويات مثل الجداول الزمنية.
    - [Binary Heap](#binary-heap)
    - [Fibonacci Heap](#fibonacci-heap)

- **[Hashing](#hashing)**  
    - الجداول الهاشية ووظائف التجزئة.
    - 🔍 **ملاحظة:** تُستخدم الجداول الهاشية في تخزين البيانات بطريقة تسهل الوصول السريع إليها.
    - [Hash Tables](#hash-tables)
    - [Hash Functions](#hash-functions)

- **[Graphs](#graphs)**  
    - تمثيل الرسوم البيانية وخوارزميات الاستكشاف.
    - 🔍 **ملاحظة:** تُستخدم الرسوم البيانية لتمثيل العلاقات المعقدة بين البيانات، مثل الشبكات الاجتماعية.
    - [Graph Representation (Adjacency Matrix/List)](#graph-representation-adjacency-matrixlist)
    - [Graph Traversal (DFS, BFS)](#graph-traversal-dfs-bfs)
    - [Spanning Trees](#spanning-trees)
    - [Shortest Path Algorithms (Dijkstra, Bellman-Ford)](#shortest-path-algorithms-dijkstra-bellman-ford)

---

## ⚙️ Algorithms

- **[Sorting Algorithms](#sorting-algorithms)**  
    - مجموعة متنوعة من خوارزميات الترتيب.
    - 🔍 **ملاحظة:** تُستخدم خوارزميات الترتيب لتنظيم البيانات، مما يسهل الوصول إليها.
    - [Bubble Sort](#bubble-sort)
    - [Selection Sort](#selection-sort)
    - [Insertion Sort](#insertion-sort)
    - [Merge Sort](#merge-sort)
    - [Quick Sort](#quick-sort)
    - [Heap Sort](#heap-sort)
    - [Counting Sort](#counting-sort)
    - [Radix Sort](#radix-sort)

- **[Searching Algorithms](#searching-algorithms)**  
    - خوارزميات البحث في البيانات.
    - 🔍 **ملاحظة:** تساعد خوارزميات البحث في تحديد مواقع العناصر في مجموعة بيانات.
    - [Linear Search](#linear-search)
    - [Binary Search](#binary-search)

- **[Dynamic Programming](#dynamic-programming)**  
    - حل المشكلات المعقدة عبر تخزين الحلول الجزئية.
    - 🔍 **ملاحظة:** تُستخدم البرمجة الديناميكية لتحسين الأداء عن طريق تجنب الحسابات المتكررة.
    - [Fibonacci Sequence](#fibonacci-sequence)
    - [Longest Common Subsequence](#longest-common-subsequence)
    - [Knapsack Problem](#knapsack-problem)

- **[Greedy Algorithms](#greedy-algorithms)**  
    - خوارزميات الجشع لحل المشكلات بطريقة سريعة.
    - 🔍 **ملاحظة:** تعتمد خوارزميات الجشع على اتخاذ أفضل خيار محلي في كل خطوة.
    - [Huffman Coding](#huffman-coding)
    - [Kruskal’s Algorithm](#kruskals-algorithm)
    - [Prim’s Algorithm](#prims-algorithm)

- **[Backtracking](#backtracking)**  
    - تقنيات العودة لحل مشكلات الاستكشاف.
    - 🔍 **ملاحظة:** تُستخدم تقنيات العودة لاستكشاف جميع الحلول الممكنة لمشكلة معينة.
    - [N-Queens Problem](#n-queens-problem)
    - [Sudoku Solver](#sudoku-solver)

- **[Divide and Conquer](#divide-and-conquer)**  
    - تقسيم المشكلة إلى أجزاء صغيرة وحلها.
    - 🔍 **ملاحظة:** تُستخدم هذه التقنية لتحسين الأداء من خلال حل مشكلات أصغر بشكل متكرر.
    - [Merge Sort](#merge-sort)
    - [Quick Sort](#quick-sort)
    - [Binary Search](#binary-search)

- **[Graph Algorithms](#graph-algorithms)**  
    - خوارزميات الرسوم البيانية المتقدمة.
    - 🔍 **ملاحظة:** تُستخدم خوارزميات الرسوم البيانية في حل مشكلات مثل البحث عن المسار الأقصر.
    - [Depth-First Search (DFS)](#depth-first-search-dfs)
    - [Breadth-First Search (BFS)](#breadth-first-search-bfs)
    - [Dijkstra’s Algorithm](#dijkstras-algorithm)
    - [Bellman-Ford Algorithm](#bellman-ford-algorithm)

---

## 📏 Complexity Analysis

- **[Time Complexity](#time-complexity)**  
    - تحليل الزمن اللازم لتنفيذ الخوارزميات.
    - 🔍 **ملاحظة:** يُستخدم لتحليل فعالية الخوارزميات بناءً على حجم المدخلات.

- **[Space Complexity](#space-complexity)**  
    - تحليل الذاكرة المطلوبة لتنفيذ الخوارزميات.
    - 🔍 **ملاحظة:** يُستخدم لتقييم مقدار الذاكرة المستخدمة أثناء تنفيذ الخوارزمية.

- **[Big O Notation](#big-o-notation)**  
    - الأساسيات لتقييم تعقيد الخوارزميات.
    - 🔍 **ملاحظة:** تُستخدم لوصف أسوأ حالة لأداء الخوارزمية.

---

## 📖 Resources for Learning

- [GeeksforGeeks](https://www.geeksforgeeks.org/)  
    - مقالات شاملة وموسعة حول الخوارزميات وهياكل البيانات.
- [Programiz](https://www.programiz.com/)  
    - دروس تعليمية سهلة ومباشرة للمبتدئين.
- [W3Schools](https://www.w3schools.com/)  
    - تعلم البرمجة بأسلوب تفاعلي وسهل.
- [TutorialsPoint](https://www.tutorialspoint.com/)  
    - شرح مفصل للعديد من المواضيع البرمجية.

---

> **🎯 ملاحظة:** يمكنك تعديل الروابط في هذا المستند لتشير إلى ملفاتك الخاصة بكل موضوع أو إضافة شرح مفصل في ملفات منفصلة.
