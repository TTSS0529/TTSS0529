## Hi, I'm Yufeng FAN

Currently at 42, building real-world systems with a focus on **low-level design, concurrency, and backend infrastructure**.

Open to opportunities in:
**C++ system programming, backend engineering (Go), concurrency frameworks, and runtime/compiler systems**

---

## Technical Focus

- **Languages**: C++, C, Go, x86-64 Assembly; Python for scripting
- **Modern C++ (C++11–17)**: RAII, move semantics, smart pointers, template metaprogramming, type traits
- **Backend Engineering (Go)**: HTTP services, concurrency (goroutines, channels), REST APIs, service architecture
- **Concurrency & Multithreading**: std::thread, mutex, condition_variable, future, thread pools
- **Systems & Runtime**: Linux, epoll, memory management, low-level system calls, runtime abstractions, threading, networking
- **Tooling**: CMake, Git, Docker, GoogleTest, Google Benchmark

---

## Featured Projects

### 🧵 modern-cpp-thread-pool
A lightweight, modern C++17 thread pool designed for clarity, correctness, and practical performance.

- Header-only design using `std::thread`, `std::future`, perfect forwarding, and RAII
- Well-defined graceful vs immediate shutdown semantics
- Benchmarked against Boost.Asio thread pool

→ [GitHub Repository](https://github.com/TTSS0529/modern-cpp-thread-pool)

---

### 🌐 webserv-refactor (HTTP/1.1 server)
A lightweight, fully custom HTTP/1.1 server originally built during the 42 curriculum, now extended as a **refactoring and systems design exploration project**.

- Event-driven architecture based on `epoll`
- HTTP/1.1 compliant: persistent connections, chunked transfer encoding
- CGI execution model (Python / PHP) with timeout & error handling
- Nginx-like configuration system with virtual hosts and routing

**Refactor focus:**
- Decoupling configuration from runtime via environment-based paths (`$WEBSERV_ROOT`)
- Modularization of request → response pipeline
- Cleaner execution flow and separation of concerns
- Experimental thread pool integration (CPU-bound workload exploration)

→ [GitHub Repository](https://github.com/TTSS0529/Webserv-Refactor)

---

### 🧬 x86_64‑libasm‑runtime
A **low-level C runtime & utility library** reimplemented in x86_64 assembly.

- Hand-crafted in **x86_64 assembly** following System V ABI and Linux syscall conventions
- Reimplements essential libc functions and linked-list primitives **without libc dependencies**
- Reinforces understanding of **calling conventions, stack layout, registers, and syscall interfaces**

→ [GitHub Repository](https://github.com/TTSS0529/x86_64-libasm-runtime)

---

### 🧠 Interpreter / Language Runtime Project
A personal project exploring parsing, execution models, and memory management.

- Hand-written parser and evaluator
- Focus on runtime behavior and control flow
- Reinforces understanding of low-level abstractions and ownership

→ [GitHub Repository](https://github.com/TTSS0529/lox-interpreter-cpp)

---

## Learning & Career Goals

- Evolving Webserv into a **modern event-driven HTTP server architecture**
  (epoll + concurrency + clean request lifecycle design)
- Deepening Go backend engineering (distributed systems, service design, concurrency patterns)
- Building a bridge between **systems programming (C++) and backend services (Go)**
- Exploring compiler fundamentals: IR design, parsing, and code generation
- Improving performance engineering and runtime-level optimization skills

---

## Career Focus

Seeking opportunities in:
- System-level C++ development
- Backend engineering (Go)
- High-performance networking systems
- Runtime / compiler / infrastructure engineering

with a strong emphasis on **concurrency, low-level design, and production-grade architecture thinking**
