# Rust Syntax 03

A comprehensive collection of Rust learning projects following "The Rust Programming Language" book (The Rust Book). This repository contains practical implementations and exercises covering fundamental to advanced Rust concepts.

## Project Structure

This repository is organized into multiple independent Rust projects, each focusing on specific chapters and concepts from The Rust Book:

- **adder_11** - Chapter 11: Automated Testing
  - Unit tests and test organization

- **minigrep_12** - Chapter 12: I/O & CLI Project
  - Command-line argument parsing
  - File I/O operations
  - Error handling
  - Test-driven development
  - Environment variables

- **iterators_13a** - Chapter 13: Iterators & Closures
  - Closures and anonymous functions
  - Iterator patterns and adaptors
  - Performance optimizations

- **crates_14** - Chapter 14: Cargo & Crates
  - Custom build profiles
  - Cargo workspaces
  - Publishing to crates.io

- **pointer_15a** - Chapter 15: Smart Pointers
  - Box<T> for heap allocation
  - Deref and Drop traits
  - Reference counting (Rc<T>)
  - RefCell<T> for interior mutability

- **oop_16** - Chapters 16-17: Concurrency & OOP
  - Object-oriented programming patterns in Rust
  - Threads and message passing
  - Shared-state concurrency

## Topics Covered

### Core Concepts
- Variables and Mutability
- Ownership and Borrowing
- References and Slices
- Structs and Methods
- Enums and Pattern Matching

### Collections
- Vectors
- HashMaps
- Strings

### Advanced Features
- Generics
- Traits
- Lifetimes
- Error Handling (Result, Option, panic!)
- Smart Pointers
- Concurrency
- Unsafe Rust
- Macros

## Running the Projects

Each subdirectory is an independent Cargo project. To run a specific project:

```bash
cd <project_name>
cargo run
```

To run tests:

```bash
cargo test
```

## Notes

See [notes.md](notes.md) for detailed topic breakdowns and chapter summaries from The Rust Book.

## License

See [LICENSE](LICENSE) file for details.
