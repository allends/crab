# Crab (Rust Shell) Project

Welcome to the Crab Project!

## Goal
The goal of this project is to provide a minimal shell implementation in Rust. The shell is able to execute commands, support environment variables, and provide a basic set of built-in commands. The shell is interactive, allowing users to enter commands and see the output. The shell also supports external commands, allowing users to run any command available on the system (as long as it is in the system's PATH). Adding built-in commands is easy, and the shell can be extended to support more complex functionality through its `Command` struct.

## Features

- Interactive shell prompt
- Command execution
- Environment variable support
- Built-in commands (e.g., `type`, `echo`, `exit`)
- Support for external commands (e.g., `ls`, `cat`, `grep`)
