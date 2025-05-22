# PSLRAR — Prototype of Self-Learning Recursive Artificial Retardation

> A recursive self-improving code-based memory and generation system.

## Status

Prototype — early concept stage. Expect instability, experimentation, and fun bugs.

---

## Core Idea

PSLRAR is an experimental project aiming to simulate a form of recursive memory, data association, and code evolution.
It works not only with knowledge of code fragments, but with *associative memory* and *meta-level mutation* of its own logic.

The system is designed to:

* Store **code fragments** as meaningful, context-rich objects.
* Connect fragments with **associative keys** ("smell of rain" model).
* Retrieve, combine, mutate, and improve code pieces.
* Remember what worked — and what didn’t.
* Evolve its own behavior and logic over time.

This is **not a traditional AI/ML system**. It's a sandbox to explore a weird idea: what if memory, pattern-matching, and code-gen lived together — and kept rewriting each other?

---

## Core Components

### Code Fragment

Basic unit of information. Each fragment contains:

* The actual code.
* Metadata (language, purpose, dependencies).
* Importance weight.
* Contextual keys (e.g. "file reading", "error-prone", "fast loop").
* Links to other fragments (influences, usage history, etc).

### Associative Keys

Like smells or visual memory. They are fuzzy, descriptive handles like:

* `"recursion"`, `"I/O"`, `"unsafe"`, `"clean but slow"`, `"async"`
* Used to connect, retrieve, and mutate fragments.

### Self-Modifying Engine

The engine does:

* Retrieves fragments by context.
* Merges, rewrites, replaces code.
* Generates new code when needed.
* Evaluates result (via tests or heuristics).
* Updates memory based on success/failure.
* **Can rewrite its own logic.**

---

## Recursion and Self-Evolution

The project is recursive at its core:

* The memory system can modify its own structure.
* The generation engine can rewrite its own generation methods.
* Old data can decay or be overwritten.

---

## Planned Features

* Graph-based fragment storage.
* Key weighting and fuzzy matching.
* Mutation and variation engine.
* Simple compiler/tester loop.
* Feedback-based memory shaping.
* Visualization of memory clusters.

---

## Disclaimer

This project is experimental, absurd, and potentially useless — but fun.
It is not based on any formal AI architecture. It is a prototype of something in between madness and code art.

---

## Repo Structure (planned)

* `src/` – code for memory engine and logic
* `fragments/` – initial hand-written fragments
* `tests/` – simple scenarios to test generation
* `docs/` – design ideas, visualizations, rambling

---

## License

TBD. Possibly MIT, possibly something weird.

---

## Author

Initiated by @Hasatel — inspired by strange dreams, recursive thoughts, and my schizophrenia.

---

> “The system forgets nothing. But it forgets how it remembered.”
