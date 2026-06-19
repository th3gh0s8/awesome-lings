# Awesome Lings [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of **Rustlings-style** interactive learning tools, CLI exercises, and koans for various programming languages and technologies. Inspired by the original [Rustlings](https://github.com/rust-lang/rustlings) project.

## Table of Contents
- [What is a "Lings" Project?](#what-is-a-lings-project)
- [Programming Languages](#programming-languages)
  - [Systems Languages](#systems-languages)
  - [General Purpose & Web](#general-purpose--web)
  - [Functional Programming](#functional-programming)
  - [Mobile & Other](#mobile--other)
- [Specialized Tools & Concepts](#specialized-tools--concepts)
- [Blockchain & Smart Contracts](#blockchain--smart-contracts)
- [The Koan Ecosystem (Direct Precursors)](#the-koan-ecosystem-direct-precursors)
- [Multi-Language CLI Platforms](#multi-language-cli-platforms)

---

## What is a "Lings" Project?
A "lings" project is a CLI-based interactive tutorial. Typically, it:
1. Presents you with a set of exercises containing compilation or runtime errors.
2. Watches your filesystem for changes as you work.
3. Guides you to fix the broken code step-by-step, explaining concepts along the way.
4. Provides immediate terminal feedback as soon as you save your progress.

---

## Programming Languages

### Systems Languages
*   **[Rustlings](https://github.com/rust-lang/rustlings)** (Rust) - The original project that started the trend.
*   **[Golings](https://github.com/mauricioabreu/golings)** (Go) - Interactive exercises to learn Go.
*   **[goforgo](https://github.com/stonecharioteer/goforgo)** (Go) - An alternative Go CLI tutorial.
*   **[Ziglings](https://codeberg.org/ziglings/exercises)** (Zig) - Self-contained Zig exercises (hosted on Codeberg).
*   **[Cplings](https://github.com/rdjondo/cplings)** (C++) - Learn C++ by fixing compiler errors.
*   **[Clings-Btw](https://github.com/tonybanters/clings)** (C) - Clings by Tony-Btw.
*   **[Clings](https://github.com/danwritecode/clings)** (C) - C learning exercises.
*   **[Asmlings](https://github.com/KazeTachinuu/asmlings)** (x86-64 Assembly) - Learn Assembly programming.
*   **[Nimlings](https://github.com/sergiotapia/nimlings)** (Nim) - Learn the Nim language.

### General Purpose & Web
*   **[Pythonlings](https://github.com/sigmages/pythonlings)** (Python) - Interactive Python exercises.
*   **[Pylings](https://github.com/CompEng0001/Pylings)** (Python) - A Python CLI learning tool.
*   **[Egglings](https://github.com/numbertheory/egglings)** (Python) - Another Python exercise suite.
*   **[Typescriptlings](https://github.com/ayakovlenko/typescriptlings)** (TypeScript) - Learn TypeScript by fixing code.
*   **[tslings](https://github.com/ut-code/tslings)** (TypeScript) - Alternative TypeScript exercises.
*   **[Javalings](https://github.com/oppahansi/javalings)** (Java) - Interactive Java CLI exercises.
*   **[Exlings](https://github.com/zoedsoupe/exlings)** (Elixir) - Guided Elixir exercises.
*   **[Boxlings](https://github.com/ortus-boxlang/boxlings)** (BoxLang) - Interactive exercises for BoxLang.
*   **[prjs](https://github.com/samuelroland/prjs)** (JavaScript) - Practice runner for JavaScript.

### Functional Programming
*   **[Fronds](https://github.com/gs0510/ofronds)** (OCaml) - An interactive tutorial for OCaml.
*   **[Haskell MOOC](https://haskell.mooc.fi/part1)** (Haskell) - Interactive course and exercises for Haskell.

### Mobile & Other
*   **[Swiftlings](https://github.com/tornikegomareli/swiftlings)** (Swift) - Learn Swift syntax.
*   **[Kotlin Koans](https://kotlinlang.org/docs/koans.html)** (Kotlin) - Official interactive coding exercises.

---

## Specialized Tools & Concepts
*   **[Threadlings](https://github.com/Florob/threadlings)** - Learn parallel programming in Rust.
*   **[Dockerlings](https://github.com/furkan/dockerlings)** - An interactive TUI for learning Docker commands.
*   **[GitLings](https://github.com/kjuulh/gitlings)** - Learn Git version control.
*   **[Bashlings](https://github.com/qobulovasror/bashlings)** - Learn Bash scripting through interactive CLI exercises.
*   **[zedtutor](https://github.com/llamaha/zedtutor)** - Learn the Zed editor.

---

## Blockchain & Smart Contracts
*   **[Starklings](https://github.com/onlydustxyz/starklings)** - Learn Cairo and Starknet development.
*   **[Noirlings](https://github.com/raven-house/noirlings)** - Learn the Noir zero-knowledge programming language.

---

## The Koan Ecosystem (Direct Precursors)
Before the "lings" format became popular, the "Koans" format was the gold standard for test-driven, CLI-based learning. These work identically: you download the repository locally, run a test watcher, and modify the code (often filling in blanks like `__`) to make the assertions pass.

*   **[Ruby Koans](https://github.com/edgecase/ruby_koans)** (Ruby) - The classic project that popularized this learning style.
*   **[Python Koans](https://github.com/gregmalcolm/python_koans)** (Python) - A highly popular interactive TDD suite for learning Python 3.
*   **[DotNet Koans](https://github.com/DotNetKoans/DotNetKoans)** (C# / .NET) - Cross-platform exercises for learning C# syntax.
*   **[SQL Koans](https://github.com/phillipjohnson/sql-koans)** (SQL) - Interactive queries where you fill in missing SQL parameters.
*   **[Clojure Koans](https://github.com/functional-koans/clojure-koans)** (Clojure) - Interactive exercises for the Clojure language.
*   **[JavaScript Koans](https://github.com/mignev/javascript-koans)** (JavaScript) - A test-driven learning suite for JavaScript.
*   **[Go Koans](https://github.com/cdarwin/go-koans)** (Go) - An alternative interactive suite for learning idiomatic Go.
*   **[CppKoans](https://github.com/torbjoernk/CppKoans)** (C++) - Learn C++ standard libraries and features using MSTest or GTest styles.

---

## Multi-Language CLI Platforms
If a specific language doesn't have a dedicated "lings" project, these multi-language platforms are excellent CLI-based alternatives:

*   **[Exercism (CLI)](https://exercism.org/)** - A platform supporting 70+ languages. You download exercises using their CLI, solve them locally, run tests, and upload your solution.
*   **[NodeSchool (Workshopers)](https://nodeschool.io/)** - Command-line workshops for JavaScript, Node.js, and related technologies. Key workshops include:
    *   **[learnyounode](https://github.com/workshopper/learnyounode)** - Node.js basics.
    *   **[learnyoubash](https://github.com/denysdovhan/learnyoubash)** - Bash scripting.
