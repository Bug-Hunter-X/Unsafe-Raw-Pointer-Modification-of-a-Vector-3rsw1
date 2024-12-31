# Rust Raw Pointer Vector Modification Bug

This repository demonstrates a common error in Rust: attempting to modify a vector's contents using a raw pointer without proper care.  Modifying a vector's data through a raw pointer outside of the vector's own methods is dangerous and can lead to undefined behavior, crashes, or subtle data corruption.

The `bug.rs` file contains code illustrating the unsafe manipulation.  The `bugSolution.rs` demonstrates a safer alternative.   Always prioritize safe and idiomatic Rust techniques for vector manipulation.

**Key Learning:**  Rust's ownership and borrowing system is crucial to memory safety. Raw pointers should be avoided unless absolutely necessary, and even then, extreme caution is advised.