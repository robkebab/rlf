# rlf

## What is it?
An opinionated framework and CLI tool for running agents in a "Ralph" loop.

## Who is it for?
Developers

## Install

### From source
```bash
git clone https://github.com/robkebab/rlf
cd rlf
pnpm install
pnpm build
pnpm link --global
```

## Quick Start

```bash
rlf info        # overview of the Ralph methodology and tool
rlf config      # edit configuration (prefered agent, LLM Gateway, sandbox provider, base path, etc.)
rlf new         # start a new project or feature
rlf plan        # run a Ralph loop to create or update your IMPLEMENTATION_PLAN.md
rlf build       # run a Ralph loop to build your plan
rlf clean       # clean up files such as IMPLEMENTATION_PLAN.md needed for the Ralph orchestration
```
