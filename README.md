#  minigrep — A Simple CLI Text Search Tool in Rust

`minigrep` is a  beginner-friendly command-line tool written in Rust, inspired by the Unix `grep` utility. It allows you to search for lines containing a query string within a text file. This project shows file I/O, error handling, and ownership in Rust.

##  Features

- Search for exact matches of a query string in a file.
- Case-insensitive search option using an environment variable.
- Graceful error handling with user-friendly messages.
- Demonstrates idiomatic Rust patterns such as `Result`, `Option`, `struct`, and module organization.

## Built With

- [Rust](https://www.rust-lang.org/) (Edition 2021)
- [Cargo](https://doc.rust-lang.org/cargo/) package manager

## 🚀 Getting Started

### Prerequisites

- Ensure Rust and Cargo are installed  
  You can install Rust using [rustup](https://rustup.rs/):

  ```bash
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

  ```
  ## Clone the repository

  ```bash
  git clone https://github.com/jolah1/minigrep.git
  cd minigrep
  ```
  ## Build the Project

  ```bash
  cargo build --release
  ```

  ## Run the project
  ```bash
  cargo run -- body poem.txt
  ```

