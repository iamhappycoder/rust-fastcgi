FastCGI Library for Rust (Modified Fork)
========================================

Copyright (c) 2025 Jasper V. Ferrer

Licensed under the MIT License. See `LICENSE.txt`

This is a **fork** of the original [fastcgi](https://github.com/mohtar/rust-fastcgi) library for Rust by Mohd Tarmizi Mohd Affandi.

### ✨ What's different in this fork?

This version adds support for **single-request handling** — useful in cases where the FastCGI
application should handle a single request and then exit (e.g., CGI-style environments), rather than running as a
persistent server.

---

Below is the unmodified README from the original project for reference:


FastCGI library for Rust
========================

Copyright (c) 2015 Mohd Tarmizi Mohd Affandi

Licensed under the MIT License. See `LICENSE.txt`

Documentation
-------------

Read the generated API documentation:
https://docs.rs/fastcgi
