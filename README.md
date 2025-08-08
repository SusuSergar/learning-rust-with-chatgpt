# Rust Training Plan – Pragmatic Learning

A clearly structured, pragmatic learning plan for Rust, ideal as a GitHub repository base.  
This plan combines practical tasks, clear goals, and fast feedback loops.  
Goal: Gradually deepen skills in Systems Programming and Rust.

---

## Prompt for Each Session

> **Instructions for the coach or reviewer:**
> - First, read the **Status** and the last **Session Log**.
> - Evaluate today’s session using the rubric below (0–5).
> - Write a short explanation and update the checklists.
> - Provide 3–5 focused tasks from the next relevant block.
> - Avoid long theory sections – keep it short, with clear goals and quick feedback.

---

## Rules

- Direct communication, no unnecessary fluff.
- Short tasks, quick iteration.
- If a task stalls: identify the blocker, give a targeted hint, continue.
- Focus blocks: 25–40 min work, 5 min break. Max 2 h per session.
- Start with the **`std`** library, then add crates as needed (Tokio, Rayon, Serde, Clap).
- Working & tested code > perfect architecture.

---

## Evaluation Scale

| Score | Meaning |
|-------|---------|
| 0     | not started |
| 1     | started, stuck |
| 2     | partially done |
| 3     | completed with help |
| 4     | completed cleanly |
| 5     | strong result + extra/refactor/tests |

---

## Session Template

```
Date: __________  Duration: ____
Goals today:
- [ ] ...
- [ ] ...
Results/Notes:
Blockers/Questions:
Next session:
Score (0–5): __   Comment: _______________________________
```

---

## Status (Self-Assessment, 0–5)

- Std Basics
- Ownership/Borrowing
- Error Handling
- Collections/Iterators
- Strings/Slices
- Modules/Crates
- File I/O / CLI
- Threads/Sync (std)
- Rayon (Data Parallelism)
- Networking (std)
- Tokio/Async
- Serde/Formats
- Bit Manipulation
- Unsafe/FFI Basics
- Testing/Bench/Performance

---

## Roadmap (8 Weeks, Adjustable)

### Week 1 – Std Basics (Strings, Slices, I/O, Result)
- Practice strings and slices (`trim`, `split`, `join`).
- Error handling (`Result`, `?`, optional `thiserror`).
- File read/write (`std::fs`, `BufRead`, `Write`).
- **Mini Project:** `wc` clone.

### Week 2 – Collections & Iterators
- Work with Vectors, HashMaps, HashSets.
- Iterator chains with `map`, `filter`, `collect`.
- **Mini Project:** Log Analyzer.

### Week 3 – Threads & Sync
- `thread::spawn`, `JoinHandle`.
- Channels (`mpsc`), `Arc<Mutex<T>>`.
- **Mini Project:** Parallel Downloader.

### Week 4 – Rayon
- `par_iter`, `map`, `reduce`.
- **Mini Project:** Parallel Prime Sieve.

### Week 5 – Networking (`std::net`)
- TCP server/client, basic protocol design.
- **Mini Project:** Key-Value Server (blocking).

### Week 6 – Async with Tokio
- Runtime, `async/await`, `tokio::net`.
- **Mini Project:** Chat Server or Port Scanner.

### Week 7 – Bit Manipulation & Binary Formats
- Bitwise operators, masks, endianness.
- **Mini Project:** Binary Parser.

### Week 8 – Unsafe & FFI
- `unsafe` blocks, raw pointer basics, `repr(C)`.
- **Mini Project:** Small C-FFI Demo.

---

## Task Pool (Extra or Replacement Tasks)

- Light `hexdump`
- Mini INI/CSV parser
- Top-K with BinaryHeap
- Minimal HTTP client
- Chat server with user lists
- JSON/YAML with Serde
- Bitflags type for permissions
- Property testing (`proptest`)

---

## Milestones

- [ ] `wc` clone
- [ ] Log Analyzer
- [ ] Parallel Downloader
- [ ] Rayon speedup
- [ ] KV Server
- [ ] Tokio Project
- [ ] Binary Parser
- [ ] Unsafe/FFI Demo

---

## Resources

- Rust `std` documentation
- Tokio docs
- Rayon docs
- Serde docs
- *The Rust Programming Language* (book)

---

## Score History

| #  | Date  | Score | Comment |
|----|-------|-------|---------|
| 1  |       |       |         |
| 2  |       |       |         |
| 3  |       |       |         |
| 4  |       |       |         |
| 5  |       |       |         |
| 6  |       |       |         |
| 7  |       |       |         |
| 8  |       |       |         |
