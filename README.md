# Hi, I'm Wujunhao

I'm learning and building around AI application engineering: Agent systems,
RAG workflows, tool calling, and practical product prototypes.

I use this profile as a public record of real engineering practice: reading
issues, tracing code paths, making small focused changes, writing tests, and
going through GitHub review.

## Current Focus

- AI Agent and RAG application engineering
- Python backend and runtime logic
- React console / admin UI
- GitHub collaboration, testing, and code review
- Turning vague product problems into small verifiable patches

## Open Source Practice

I'm currently contributing to
[QwenPaw](https://github.com/agentscope-ai/QwenPaw), an AI assistant / Agent
project with channels, tools, skills, runtime, and console UI.

Recent contribution tracks:

- [QwenPaw #5630](https://github.com/agentscope-ai/QwenPaw/issues/5630):
  Telegram custom BaseURL support
  - Focus: config flow, CLI/UI settings, channel runtime behavior
  - Learning target: how a user-facing setting travels through the system

- [QwenPaw #5638](https://github.com/agentscope-ai/QwenPaw/issues/5638):
  per-cron-job model override
  - Focus: cron request, runtime, agent builder, model selection
  - Learning target: request-level behavior without mutating global config

## How I Work

For each issue, I try to answer these before editing code:

1. What user problem does this issue describe?
2. Which code path actually owns the behavior?
3. What is the smallest change that proves the behavior?
4. Which test would fail if the behavior regresses?
5. How should the PR explain the root cause and verification?

## Learning Notes

I'm building depth through real tasks instead of only tutorials:

- read project structure before coding
- trace callers before changing shared functions
- prefer small patches over speculative abstractions
- write one useful test for non-trivial behavior
- review the final diff and explain it in plain language

## GitHub Stats

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=WujunhaoGPU&layout=compact&hide_border=true)

![GitHub stats](https://github-readme-stats.vercel.app/api?username=WujunhaoGPU&show_icons=true&hide_border=true)
