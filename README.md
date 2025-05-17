# Caching I/O System – Computer Systems Project

This project was completed as part of Brown’s *Computer Systems* course. The goal was to build a simplified version of a caching system that simulates how an operating system manages file input/output operations with buffering and caching strategies.

I implemented this project in C, gaining hands-on experience with systems-level programming, memory management, file descriptors, and simulating realistic OS behavior under different cache configurations.

---

## Project Summary

- **Language**: C
- **Domain**: Operating systems, file I/O, caching
- **Focus**:
  - Low-level buffer management
  - Read/write system calls
  - File offset tracking and error handling
  - Cache hits/misses statistics and eviction logic

---

## Key Features

- **Custom I/O Layer**: Replaced standard `read()`/`write()` calls with a layer that simulates caching behavior for sequential and random access.
- **Buffer Caching**: Implemented a caching strategy to reduce redundant disk reads using a fixed-size buffer, mimicking real OS performance optimizations.
- **Eviction Policy**: Designed and tested least-recently-used (LRU) style logic for buffer eviction.

---

The code for this project is private due to academic integrity policies. However, I’m happy to share implementation details or demo the project upon request from recruiters or hiring managers.

