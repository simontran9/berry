<h1><img src="docs/logo.svg" width="50px"> berry</h1>

C header-only generic containers library

## Motivation

By rule 5 of Rob Pike's 5 Rules of Programming:
> Data dominates. If you've chosen the right data structures and organized things well, the algorithms will almost always be self-evident. **Data structures, not algorithms, are central to programming**.

## Features

| Abstract Data Type        | Container(s)                                                   |
| ------------------------- | -------------------------------------------------------------- |
| List                      | Dynamic Array, Linked List (Singly and Doubly)                 |
| Stack                     | Dynamic Array, Linked List (Singly)                            |
| Queue                     | Dynamic Circular Array, Linked List (Singly)                   |
| Priority Queue            | Binary Heap (Max and Min)                                      |
| Map and Set               | Hash Table (Closed Chaining and Open Addressing), Trie         |
| Ordered Map and Ordered Set | AVL Tree, Red-Black Tree, Splay Tree, In-Memory B-Tree       |
| Disjoint Set              | Forest with Path Compression and Union by Rank Heuristic       |
| Graph                     | Adjacency List, Adjacency Matrix                               |

> [!NOTE]
> Containers are not thread-safe, but future iterations of this library will likely include a few.

## Installation

### Prerequisite dependencies

**Core dependencies**
- [C Compiler (C99 or later)](https://gcc.gnu.org/)
- [GNU Make](https://www.gnu.org/software/make/)
- [jemalloc](https://jemalloc.net/)

**Dev dependencies**
- [ClangFormat](https://clang.llvm.org/docs/ClangFormat.html)
- [Clang-Tidy](https://clang.llvm.org/extra/clang-tidy/)
- [Valgrind](https://valgrind.org/)
- [perf](https://www.swift.org/documentation/server/guides/linux-perf.html)
- [hyperfine](https://github.com/sharkdp/hyperfine)

### Static library installation

```
git clone git@github.com:simontran9/berry.git
make
```

### Dynamic library installation

## Usage

#### General usage

```
```

#### Example (`ForestDisjointSet`)

```c
```

See `docs/api.md` to learn more about the available containers and its methods.

> [!WARNING]
> You will probably encounter issues if you're going use this library through the FFI

## Benchmarks

See `docs/benchmarks.md` for more information.

## Credits

Heavy inspiration from [Abseil containers](https://abseil.io/docs/cpp/guides/container), [Rust collections](https://doc.rust-lang.org/std/collections/index.html), and [Go containers](https://pkg.go.dev/container).
