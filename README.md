# Trip Planner Using B+ Trees

A high-performance travel management system developed in **C**, designed to efficiently store, retrieve, and manage trip records using a **B+ Tree indexing structure**. The project demonstrates the practical application of advanced data structures, file persistence, and modular software engineering principles to solve real-world data management problems.

---

## Overview

Traditional linear search approaches become inefficient as the number of records grows. This project addresses that challenge by implementing a **B+ Tree-based indexing system**, enabling fast search, insertion, deletion, and update operations on trip data.

The application provides a menu-driven interface for managing travel records while maintaining efficient data access through optimized indexing mechanisms.

---

## Key Features

- Create and manage trip records
- Efficient trip lookup using B+ Tree indexing
- Insert, update, and delete trip information
- Persistent storage using file handling
- Navigation and itinerary management
- Modular architecture with clear separation of concerns
- Scalable design for handling large datasets

---

## Technical Highlights

### B+ Tree Indexing

Implemented a B+ Tree data structure to:

- Support efficient record insertion and retrieval
- Reduce lookup complexity compared to linear search
- Maintain sorted records for structured access
- Improve scalability as data volume increases

### Persistent Storage

- File-based storage for trip records
- Data retained across application executions
- Structured record management

### Modular Design

The project follows a modular architecture to improve maintainability, reusability, and extensibility.

---

## System Architecture

```text
User Interface
      │
      ▼
 Menu System
      │
      ▼
 Trip Management Layer
      │
      ├── B+ Tree Index
      │       ├── Insert
      │       ├── Search
      │       ├── Delete
      │       └── Update
      │
      └── File Storage Layer
              ├── Read Records
              └── Write Records
```

---

## Project Structure

```text
.
├── main.c              # Application entry point
├── menu.c              # Menu-driven interface
├── menu.h
├── trip.c              # Trip management logic
├── trip.h
├── tripList.c          # Trip list operations
├── tripList.h
├── navigation.c        # Navigation utilities
├── navigation.h
├── bptree.c            # B+ Tree implementation
├── bptree.h
├── fileio.c            # File handling and persistence
├── fileio.h
├── util.c             # Utility functions
└── util.h
```

---

## Technologies Used

- C Programming
- Data Structures & Algorithms
- B+ Trees
- File Handling
- Dynamic Memory Allocation
- Modular Software Design

---

## Core Concepts Demonstrated

- Advanced Tree Data Structures
- Indexing and Search Optimization
- Memory Management
- Persistent Data Storage
- Algorithmic Problem Solving
- Software Modularity
- Complexity-Aware Design

---

## Complexity Analysis

| Operation | Time Complexity |
|------------|----------------|
| Search | O(log n) |
| Insert | O(log n) |
| Delete | O(log n) |
| Update | O(log n) |

*Complexities are based on B+ Tree operations.*

---

## Build and Run

### Compile

```bash
gcc *.c -o tripplanner
```

### Execute

```bash
./tripplanner
```

---

## Engineering Takeaways

This project was built to explore how database-inspired indexing structures can significantly improve application performance. It demonstrates practical implementation of:

- Efficient record management systems
- Tree-based indexing mechanisms
- Scalable data organization strategies
- Real-world applications of advanced data structures

---

## Future Enhancements

- Graph-based route optimization
- Shortest path algorithms (Dijkstra/A*)
- Recommendation engine for destinations
- Database integration (SQLite/PostgreSQL)
- REST API backend
- Web-based user interface
- AI-powered itinerary generation

---

## Resume Impact

**Trip Planner Using B+ Trees**
- Designed and implemented a travel management system in C utilizing a B+ Tree indexing structure for efficient record storage and retrieval.
- Achieved logarithmic-time search, insertion, and deletion operations through optimized tree-based indexing.
- Developed a modular architecture incorporating file persistence, navigation management, and dynamic memory allocation.
- Applied data structure and algorithm design principles to build a scalable record management solution.

---
