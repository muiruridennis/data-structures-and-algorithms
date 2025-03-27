#  Data Structures and Algorithms Mastery Journal

![GitHub last commit](https://img.shields.io/github/last-commit/muiruridennis/data-structures-and-algorithms)
![GitHub code size](https://img.shields.io/github/languages/code-size/muiruridennis/data-structures-and-algorithms)
![License](https://img.shields.io/badge/license-MIT-blue)


## 📋 Table of Contents
- [🌟 Why This Repository?](#-why-this-repository)
- [📚 Curriculum Roadmap](#-curriculum-roadmap)
  - [🔍 Searching Algorithms](#-searching-algorithms)
  - [🔄 Sorting Algorithms](#-sorting-algorithms)
  - [🏗 Data Structures](#-data-structures)
- [🚀 Getting Started](#-getting-started)
- [🧪 Testing](#-testing)
- [📊 Benchmarking](#-benchmarking)
- [🤝 Contribution](#-contribution)
- [📜 License](#-license)

---

Welcome to my hands-on journey through **Data Structures and Algorithms**! This repository serves as both my learning journal and a practical reference for core CS concepts implemented in JavaScript.

## 🌟 Why This Repository?

- **Learn by Doing**: Clean, commented implementations of fundamental algorithms
- **Interview Ready**: Covers 90% of DSA questions asked in tech interviews
- **Performance Conscious**: Includes time/space complexity analysis for each implementation
- **Growing Resource**: Continuously updated with new topics and optimizations

## 📚 Curriculum Roadmap

### 🔍 Searching Algorithms
| Algorithm       | Best Case | Worst Case | Implementation | Tests |
|-----------------|-----------|------------|----------------|-------|
| Linear Search   | O(1)      | O(n)       | [Code](/src/searching/linearSearch.js) | [Tests](/src/searching/tests/) |
| Binary Search   | O(1)      | O(log n)   | [Code](/src/searching/binarySearch.js) | [Tests](/src/searching/tests/) |

### 🔄 Sorting Algorithms
| Algorithm       | Best Case | Worst Case | Implementation | Visual Guide |
|-----------------|-----------|------------|----------------|--------------|
| Bubble Sort     | O(n)      | O(n²)      | [Code](/src/sorting/bubbleSort.js) | [📊]() |
| Merge Sort      | O(n log n)| O(n log n) | [Code](/src/sorting/mergeSort.js) | [📊]() |

### 🏗 Data Structures
```mermaid
graph TD;
    A[Data Structures] --> B[Linear];
    A --> C[Hierarchical];
    B --> D[Arrays];
    B --> E[Linked Lists];
    B --> F[Stacks/Queues];
    C --> G[Trees];
    C --> H[Graphs];