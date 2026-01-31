# Nodevisa

*We handle instrument communication, so you can focus on using them.*

## What is Nodevisa?

Nodevisa is a modern instrumentation stack built for teams that need **deterministic behavior**, **concurrent access**, and **production-grade reliability** when communicating with test and measurement hardware.

It is designed for environments where instruments are no longer controlled by a single script, but by services, pipelines, remote users, and automated systems running in parallel.

**We provide a full instrument communication stack that establishes, manages, secures, and keeps connections alive across failures, concurrency, and long-running sessions — delivered as a secure, scalable, PyVISA-compatible drop-in replacement with bindings for C, Rust, and Python, and a rich, growing SCPI library.**

## Why Nodevisa exists

Traditional instrument control software quietly assumes:

- a single process  
- a single user  
- a single connection  
- best-effort logging  
- loosely defined failure modes  

Those assumptions fail under real-world conditions: parallel experiments, shared infrastructure, CI systems, remote access, and long-running services.

Nodevisa exists to make those scenarios boring — predictable, observable, and safe.

## Built by users and developers

Nodevisa is built by people who **use instruments daily** and who **build the software that controls them**.

We are users, developers, and maintainers of instrumentation systems — not just library authors.  
The problems Nodevisa addresses come from real experiments, real labs, real failures, and real production systems.

This perspective shapes every design decision: fewer assumptions, clearer semantics, and behavior you can rely on when things get complex.

## Design principles

Nodevisa is built around a small set of non-negotiables:

- **Correctness over shortcuts**  
- **Explicit behavior beats implicit magic**  
- **Concurrency is a first-class concern**  
- **Logs are structured data, not strings**  
- **APIs reflect real protocol semantics**  

If something looks strict, it probably is — and intentionally so.

## Interested

- 🌐 https://www.nodevisa.com  
- 📧 hello@nodevisa.com

If you are building serious instrumentation software — especially at scale — Nodevisa is built for you.
