#### Air-Gapped AI Embedded System ####

## About This Project
This project explores the idea of running an "AI assistant completely offline" to help with embedded system development.

Many engineering environments such as **military, industrial control systems, and secure labs** cannot connect to the internet. Because of that, cloud-based AI tools cannot be used.  
This project is an experiment to see whether a "local AI model can assist engineers in an air-gapped environment".

The system runs "local Large Language Models (LLMs) using Ollama inside WSL and connects them with VS Code to help generate code and assist development tasks.

## What I Am Trying to Build
The goal of this project is to create a **secure offline AI assistant** that can help with:

- Embedded C programming
- Understanding hardware datasheets
- Firmware development
- Embedded system architecture
- Technical documentation

All of this is done **without internet access**.

## Tools Used
This experiment currently uses:

- WSL (Windows Subsystem for Linux)
- Ollama
- VS Code
- DeepSeek 1.5B model
- Git & GitHub

## Hardware Setup
This project is currently being tested on a **very limited laptop setup**:

- Intel i5 (5th generation)
- 4 GB RAM
- Windows with WSL Ubuntu

Because of these limitations, the system runs slowly, but the goal is to **test whether offline AI development is possible even with low hardware resources**.

## Current Status
Right now the system can:

- Run a local LLM using Ollama
- Connect with VS Code
- Generate simple code from prompts

However, due to hardware limitations, generation can be **very slow**.

## Future Plans
In the future I plan to expand this project by adding:

- Local knowledge base from **PDF datasheets**
- Embedded documentation indexing
- Vector database for hardware knowledge
- Faster and more capable models
- A full **offline AI development environment for embedded engineers**

## Why This Project Matters
Secure environments often cannot use cloud AI tools.  
If local AI systems can be developed for these environments, it could help engineers work faster while keeping systems **fully isolated from the internet**.

This repository documents my experiments and progress while exploring this idea.

---

Author: **Sachith Roshan**
