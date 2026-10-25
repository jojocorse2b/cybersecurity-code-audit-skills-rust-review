# rust-review

Performs comprehensive Rust security review for safe/unsafe boundary issues, memory safety in unsafe blocks, concurrency hazards, panic-induced DoS, FFI safety, and async runtime mistakes. Use when auditing Rust crates, services, or libraries — particularly those with `unsafe`, FFI, or concurrent code.

## Overview

This directory contains the operational guidance for the `rust-review` skill. Start with [SKILL.md](SKILL.md), which defines when to use it and the workflow it provides.

## Usage

Install or reference this directory through your agent's skill-discovery mechanism, then invoke `rust-review` when the task matches the description above. Review linked resources in `SKILL.md` only when that workflow calls for them.
