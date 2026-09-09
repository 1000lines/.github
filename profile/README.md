# 1000lines

**Agent work that survives review.**

An agent will hand you thirty thousand lines in one go. Splitting that into forty
pull requests only helps if they are the right forty, each one coherent enough that
a reviewer can hold it in their head and say yes. Getting the cut right is a planning
problem, and it has to be solved before any code is written. Correctness lives in the
plan, not in the diff.

The longer argument, on what code review is for once agents write most of it:
[1000lines](https://github.com/1000lines/.github/blob/main/README.md)

## What's here

- **symphony**: our fork of [openai/symphony](https://github.com/openai/symphony),
  by way of Orchestra-Bio's public fork. The orchestrator. Install Elixir and run it
  on a laptop or in the cloud.
- **symphony-example**: a repository wired for agent work, as a worked example, from Orchestra Bio.
- **the template**: one command to turn an existing repository into one agents can
  work in under review. Being built on Saturday 12 September at the
  [AI Tinkerers hackathon](https://sf.aitinkerers.org/p/agents-everywhere-bots-channels-more-global-hackathon).

## If you're at the hackathon

Bring a repo you own. Not code, a repo. You leave with agent workflows running in
your own project, and we find out whether this survives contact with a codebase that
isn't ours.
