*Created in collaboration with AI.*

# Agent Scrum

A sprint methodology for continuous software development by teams of AI coding agents, with
observations from 324 sprints.

**Read the paper:** [web](https://daveremy.github.io/agent-scrum/) · [PDF](paper/agent-scrum.pdf)
· version 0.1, 28 October 2026

## In one paragraph

Agent Scrum keeps Scrum's core devices (a time-boxed sprint, a committed sprint backlog, story
points, velocity, a Definition of Done and a retrospective) and rescales them for agents. Sprints
last two hours instead of two weeks. Capacity comes from model rate limits instead of headcount,
and cost is measured as *token velocity*, the tokens consumed per merged story point. A
product-owner agent holds the conversation with the human and plans; separate scrum-team agents,
started on demand, run the sprints. In the reference implementation, 79% of committed stories
reached done inside the sprint, ceremony took under five minutes per sprint, and the human
stakeholder spent under two hours a day.

## Where to start

Five pieces: a product-owner agent that talks with the human and plans; a separate scrum-master
agent that runs one sprint at a time; short-lived developer and reviewer agents; a committed
sprint backlog with an explicit done condition for each story; and a wrap trigger that lives
outside the agents. Save unfinished work and write a handoff before every context reset, and count
a story only when its done condition holds. Add the rest only as observed failures justify it.

## What this is, and is not

This is a description of one working system, offered so others can try the method, criticise it
and improve it. It is not a product, a framework to install or a commercial offering. The
reference implementation is a personal project; its code is not part of this repository.

## Feedback

Open an issue for questions, counter-examples, or results from your own attempt. Measurements
from other implementations are the most useful contribution: the paper's numbers come from one
team serving one person.

## License

The paper and this README are licensed under
[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/) (see `LICENSE`).
Reuse, adapt and share it, with attribution.

## Citation

Remy, D. *Agent Scrum: A sprint methodology for continuous software development by AI agent
teams, with observations from 324 sprints.* Working paper, version 0.1, October 2026.
https://github.com/daveremy/agent-scrum
