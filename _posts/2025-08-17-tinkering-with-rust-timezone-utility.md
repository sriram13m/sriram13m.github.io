---
layout: post
title: "Tinkering with Rust: Building a Timezone Utility"
comments: true
description: "How I built a command-line timezone converter in Rust using Ghostty and Helix editor"
keywords: "rust, timezone, cli, ghostty, helix, programming"
---

I built `timeplease` - a Rust CLI for timezone conversions. 

This is my hand at building a CLI tool which solves a problem I have - trying to get time in different timezones while scheduling meetings. Thought it would be a good gateway project for Rust.

## Usage

Current time anywhere:
```bash
timeplease current london
```

Convert between timezones:
```bash
timeplease convert 10:00 india london  
```

## Tools I tried

- **Ghostty** for terminal 
- **Helix** editor
- Rust libraries: `chrono`, `clap`, `serde_json`

Available on [GitHub](https://github.com/sriram13m/timeplease) - `cargo install timeplease`
