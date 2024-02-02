
# Caching Project

## Overview

This project introduces different caching algorithms implemented in Python. Caching is a technique used to store frequently accessed data in a fast-accessible memory space to reduce the time-consuming process of fetching data from the original source.

The caching algorithms covered in this project include:

1. Basic Cache
2. FIFO Cache (First-In-First-Out)
3. LIFO Cache (Last-In-First-Out)
4. LRU Cache (Least Recently Used)
5. MRU Cache (Most Recently Used)
6. LFU Cache (Least Frequently Used)

## Table of Contents

1. [Files and Directories](#files-and-directories)
2. [General Requirements](#general-requirements)
3. [How to Use](#how-to-use)
4. [Caching Algorithms](#caching-algorithms)

## Files and Directories

- **`base_caching.py`**: Parent class providing a basic structure and methods for caching.
- **`0-basic_cache.py`**: Implements the BasicCache class inheriting from BaseCaching.
- **`1-fifo_cache.py`**: Implements the FIFOCache class inheriting from BaseCaching.
- **`2-lifo_cache.py`**: Implements the LIFOCache class inheriting from BaseCaching.
- **`3-lru_cache.py`**: Implements the LRUCache class inheriting from BaseCaching.
- **`4-mru_cache.py`**: Implements the MRUCache class inheriting from BaseCaching.
- **`100-lfu_cache.py`**: Implements the LFUCache class inheriting from BaseCaching.
- **`0-main.py` to `100-main.py`**: Example usage files for each caching algorithm.

## General Requirements

- All scripts are written and tested using Python 3.7 on Ubuntu 18.04 LTS.
- Files must end with a new line.
- The first line of all files must be `#!/usr/bin/env python3`.
- A `README.md` file at the root of the project directory is mandatory.
- Code must adhere to the PEP 8 style guide (checked using `pycodestyle` version 2.5).
- All files must be executable.
- Documentation is required for modules, classes, and functions.

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/your-username/alx-backend.git
```

2. Navigate to the project directory:

```bash
cd alx-backend/0x01-caching
```

3. Run the example usage files:

```bash
./0-main.py
./1-main.py
# ... and so on
```

## Caching Algorithms

### 0. Basic Cache

- Class: `BasicCache`
- Description: A simple caching system without a size limit.

### 1. FIFO Cache

- Class: `FIFOCache`
- Description: Implements the First-In-First-Out caching algorithm.

### 2. LIFO Cache

- Class: `LIFOCache`
- Description: Implements the Last-In-First-Out caching algorithm.

### 3. LRU Cache

- Class: `LRUCache`
- Description: Implements the Least Recently Used caching algorithm.

### 4. MRU Cache

- Class: `MRUCache`
- Description: Implements the Most Recently Used caching algorithm.

### 5. LFU Cache (Advanced)

- Class: `LFUCache`
- Description: Implements the Least Frequently Used caching algorithm.
