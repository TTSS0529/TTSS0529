## Hi, I'm Yufeng FAN

Currently at École 42, building backend and systems projects with Go, C, and C++.  
I'm currently looking for backend / systems internship opportunities, with a focus on Go backend development while continuing to build on my C/C++ systems background.

---

## Technical Focus

- **Languages**: Go, C++, C, Go, x86-64 Assembly; Python for scripting
- **Go**: HTTP servers, REST APIs, PostgreSQL, authentication, concurrency, testing
- **Backend**: HTTP services, concurrency, REST APIs, PostgreSQL, authentication, Docker
- **Modern C++ (C++11–17)**: RAII, move semantics, smart pointers, template metaprogramming, type traits
- **Concurrency**: goroutines, channels, std::thread, mutex, condition_variable, future, thread pools
- **Systems & Runtime**: Linux, epoll, memory management, low-level system calls, runtime abstractions, threading, networking
- **Tooling**: CMake, Make, Git, Docker, GoogleTest, Google Benchmark, Github Actions

---

## Featured Projects

### 🚀 Greenlight API

A production-style RESTful movie catalog API built with Go and PostgreSQL, following practical backend engineering patterns.

- RESTful JSON API with CRUD operations, filtering, sorting, and pagination
- PostgreSQL full-text search and database connection pooling
- Authentication, authorization and token-based authentication
- Request validation, rate limiting, graceful shutdown, and structured logging
- Containerized deployment with Docker Compose and Caddy
- Automated testing and CI with GitHub Actions

→ [GitHub Repository](https://github.com/TTSS0529/greenlight-api)

---

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

## Background

My systems programming background comes from building projects in **C and C++**, including process management, networking, concurrency, memory management, and low-level runtime behavior.

More recently, I have been using **Go to develop backend services**, focusing on HTTP APIs, databases, concurrency, testing, and production-oriented engineering practices.

## Career Focus

Seeking backend or systems internships / junior opportunities, particularly in:

- Go backend development
- C/C++ systems programming
- Networking and infrastructure
- Concurrency
- Runtime and low-level systems

I'm interested in roles where I can combine practical backend engineering with my existing systems programming background.
