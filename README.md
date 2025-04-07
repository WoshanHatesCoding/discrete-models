# 🧮 Discrete Models: Prime Number Generator

> ⚙️ A multithreaded C++ application that generates prime numbers efficiently using parallel processing techniques.

---

## 📝 Description

This project was developed as part of a **Discrete Mathematical Models** course.  
It explores the concept of **prime number generation** using a high-performance, parallelized algorithm.

We use modern **C++** with **thread pools** and **modular design** to achieve fast, scalable prime number discovery over a specified range.

---

## 🎯 Objectives

- Generate prime numbers efficiently over large ranges  
- Use multithreading for parallel prime checks  
- Apply concepts from discrete mathematics  
- Design a modular, maintainable C++ application  

---

## 📂 Project Structure

```
Discrete_Models_Project/
│
├── main.cpp              # Entry point and orchestrator
├── thread_pool.cpp       # Custom thread pool implementation
├── thread_pool.h         # Thread pool header file
├── CMakeLists.txt        # Build configuration
└── Olta-Ruslan-Baran.pdf # Project report/documentation
```

---

## 🚀 How to Build & Run

### 🛠 Requirements

- C++ compiler (GCC or Clang with C++11+ support)  
- CMake (optional, if using provided `CMakeLists.txt`)  

### ⚙️ Compile Manually

```bash
g++ -std=c++11 main.cpp thread_pool.cpp -o prime_generator -pthread
```

Then run it:

```bash
./prime_generator
```

### 🧱 Or Build with CMake

```bash
mkdir build
cd build
cmake ..
make
./prime_generator
```

---

## ⚡ Features

- Multithreaded prime number computation  
- Custom thread pool implementation  
- Efficient memory and task management  
- Designed for scalability over large number ranges  

---

## 📖 Report

The file `Olta-Ruslan-Baran.pdf` contains a detailed explanation of:
- Algorithm used
- Optimization techniques
- Time complexity and performance insights
- Screenshots and results

---

## 👨‍💻 Authors

- Olta  
- Ruslan  
- Baran  

> ✨ *Efficient computation meets elegant design.*
