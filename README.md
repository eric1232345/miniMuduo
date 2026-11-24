# MiniMuduo

A lightweight C++17 TCP networking library inspired by [Muduo](https://github.com/chenshuo/muduo).

## Overview

MiniMuduo is a personal software engineering project focused on Linux network programming, modern C++, concurrent programming, and event-driven architecture.

The goal is to incrementally implement a lightweight TCP networking library based on the Reactor pattern and Linux I/O multiplexing.

## Technology Stack

- C++17
- Linux / Ubuntu / WSL2
- POSIX Socket API
- epoll
- CMake
- GDB
- Git and GitHub

## Project Structure

```text
miniMuduo/
├── include/minimuduo/
├── src/
├── examples/
├── tests/
├── docs/
├── CMakeLists.txt
├── README.md
└── LICENSE
```

## Build and Run

### Prerequisites

- Linux environment
- GCC/G++ with C++17 support
- CMake 3.16 or later

### Build

```bash
cmake -S . -B build
cmake --build build
```

### Run

```bash
./build/hello
```

## Development Progress

- [x] Project initialization
- [x] CMake build system
- [ ] Basic TCP network programming
- [ ] I/O multiplexing
- [ ] Single Reactor architecture
- [ ] TCP networking components
- [ ] Multithreaded Reactor architecture
- [ ] Application development
- [ ] Performance testing

For more details, see the [Development Roadmap](docs/roadmap.md).

## References

- [Muduo Networking Library](https://github.com/chenshuo/muduo)
- [Muduo Tutorial](https://github.com/chenshuo/muduo-tutorial)
- Linux Multithreaded Server Programming — Shuo Chen

## Project Status

Under active development.

## License

BSD 3-Clause License.