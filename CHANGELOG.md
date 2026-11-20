# Changelog

## V.01 — 2026-11-20
- App version shown under the header.
- Groq vision model switched to `qwen/qwen3.8-27b` (`llama-4-scout` was shut down by Groq on 2026-07-17, so analysis was failing).
- Reasoning `<think>` output is stripped before parsing the JSON reply.
- Hosting no longer publishes dotfiles (`.git`, `.firebase`) or test files.
