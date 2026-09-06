# 1000lines

**Agent work that survives review.**

An agent will hand you thirty thousand lines in one go. 
Splitting that into forty pull requests only helps if they are the *right* forty — each one coherent enough that a reviewer 
can hold it in their head and say yes. Getting the cut right is a planning problem, and it has to be solved before any code is written.

We integrate with GitHub **governance**, to manage the relationship between coding agents, reviewing agents, coordination, and human reviewers.

Branch protection, author-cannot-approve and required reviews are mechanical enforcement a chatbox cannot reproduce: 
a bot cannot approve its own work. 
Review matters: the reviewer needs to understand each PR sufficiently to approve and merge - and ultimately to be responsible for the impact in production.

## What's here today

**symphony** — a fork of [openai/symphony](https://github.com/openai/symphony) by way of Orchestra-Bio's public fork. 
This is the orchestrator: the engine. After installing Elixir, you can run it on your laptop or in the cloud.

## What's coming

- **The GitHub workflows that make it work.** Expected as a code donation from Orchestra Bio — the coordination layer
  that has been running this in production: DAG planning, fan-out into reviewable, non-conflicting, pull requests - in the right sequence; and review-driven replanning.
- **A copier template**, being built on **Saturday 12 September** at the
  [AI Tinkerers "Agents, Everywhere"](https://sf.aitinkerers.org/p/agents-everywhere-bots-channels-more-global-hackathon) hackathon. Turn any repo
  into a place agents can work under review.
- **A terraform module** for running Symphony on AWS. Hoped for, not promised.

## If you're at the hackathon

Bring a repo you own. Not code — a repo. You leave with agent workflows running in your own project, 
and we find out whether this survives contact with a codebase that isn't ours.
