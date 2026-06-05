# Rust Installation and First Project

## Why I Decided to Learn Rust

I am actively building in Web3 as a writer and researcher. As I became more interested in cybersecurity, I realized that Web3 security is an important area where cybersecurity skills can remain highly relevant.

I decided to learn Rust because:

* I am interested in cybersecurity.
* I want to understand and contribute to Web3 security.
* Rust is widely used in the Web3 ecosystem, especially around Solana.
* Learning Rust will help me build a stronger technical foundation.

## Environment

* Operating System: Kali Linux
* Installation Method: rustup
* Learning Resource: Rust Playbook

## Installation Experience

I followed the Rust Playbook as a guide during the installation process.

The installation itself completed successfully, but I encountered a few challenges while trying to verify that Rust was working correctly.

## Challenges

### Command Mistakes

As a beginner, I made a few mistakes while entering commands in the terminal.

### Shell Prompt Confusion

At one point, I accidentally entered an incomplete command and got stuck at a `dquote>` prompt because a quotation mark had not been closed properly.

### Understanding Installation Messages

Some of the messages displayed after installation were unfamiliar, and I was not initially sure what they meant or which steps were required next.

## Troubleshooting

To verify the installation, I restarted my terminal and checked whether Rust was available.

I also used:

```bash
which rustc
```

to locate the Rust compiler on my system.

## Verification

I confirmed that Rust was installed successfully when:

```bash
rustc --version
```

returned a valid Rust version.

I also successfully created and ran my first Rust project using Cargo.

## First Rust Program

Using the Rust Playbook, I created and ran a simple Hello World application.

Running:

```bash
cargo run
```

compiled the project and displayed:

```text
Hello, world!
```

This confirmed that Rust and Cargo were installed and functioning correctly.

## Key Achievements

* Installed Rust on Kali Linux.
* Learned how to verify Rust installations.
* Ran my first Rust program.
* Learned basic terminal troubleshooting.
* Created my first Git commit.
* Connected GitHub using SSH authentication.
* Pushed code to GitHub successfully.

## Reflection

Before this setup, I had no experience with Rust.

The process taught me that troubleshooting is a normal part of learning technology. By carefully reading terminal output, following documentation, and testing solutions, I was able to successfully install Rust, run my first program, and begin documenting my learning journey.
