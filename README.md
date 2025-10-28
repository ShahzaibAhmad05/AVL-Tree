# AVL Tree (C++)

This repository contains a single-file C++ implementation of an AVL (self-balancing binary search) tree.

Features
- Insert and delete operations with automatic balancing (rotations).
- Tree traversals (in-order, pre-order, post-order) and height tracking.
- Clean, single-file example in `AVLTree.cpp` that can be compiled and run directly.

Getting started

Requirements
- A C++ compiler supporting C++11 or later (GCC, Clang, MSVC).

Build (PowerShell / Windows)

```powershell
# Using g++ (MinGW or similar):
g++ -std=c++17 -O2 -Wall AVLTree.cpp -o AVLTree.exe

# Or using MSVC (Developer PowerShell):
cl /EHsc /std:c++17 AVLTree.cpp /Fe:AVLTree.exe
```

Run

```powershell
.\AVLTree.exe
```

If `AVLTree.cpp` contains a main() that reads/writes from stdin, feed input accordingly. Otherwise, open the file to see example usage or add a small `main()` to test the tree.

Contributing

- If you want to add features (e.g., iterators, unit tests, benchmarking), please open an issue or submit a pull request.

License

This project is provided under the MIT License. See `LICENSE` if you add one, or contact the repository owner for licensing details.

Contact

For questions, contact the repository owner.
