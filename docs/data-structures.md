# 📚 Data Structures Documentation

```mermaid
graph TD
    A[src/data-structures] --> B[Linked Lists]
    A --> C[Stacks]
    A --> D[Queues]
    A --> E[Trees]
    A --> F[Graphs]
    B --> B1[Singly Linked]
    B --> B2[Doubly Linked]
    E --> E1[Binary Search Trees]
    E --> E2[AVL Trees]
    
1. Linked Lists
📂 Implementation Files
LinkedList.js

DoublyLinkedList.js

🧠 Core Concepts
javascript
Copy
// From LinkedList.js
class Node {
  constructor(value) {
    this.value = value;
    this.next = null;
  }
}
🏋️‍♂️ Practice Problems
Reverse a Linked List (Solution)

Detect Cycle (Solution)

2. Stacks & Queues
📂 Implementation Files
Stack.js

Queue.js

🎯 Real-World Use Cases
Structure	Use Case	Code Reference
Stack	Browser history	BrowserHistory.js
Queue	Printer spooling	PrinterQueue.js
3. Trees
🌳 Types Implemented
Binary Search Tree (BST.js)

AVL Tree (AVLTree.js)

📊 Complexity Comparison
mermaid
Copy
pie
    title BST Operations
    "Search" : 40
    "Insert" : 30
    "Delete" : 30
4. Graphs
📂 Implementation Files
AdjacencyList.js

Dijkstra.js

🛠 How to Test
bash
Copy
npm test src/data-structures/graphs/tests/
🔗 Navigation Guide
markdown
Copy
[➡️ Go to Stack Implementation](/src/data-structures/stack/Stack.js)  
[⬆️ Back to Repository Root](/README.md)