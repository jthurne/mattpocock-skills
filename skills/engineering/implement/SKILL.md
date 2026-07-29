---
name: implement
description: "Implement a piece of work based on a spec or set of tickets."
disable-model-invocation: true
---

Implement the work described by the user in the spec or tickets.

Use /tdd where possible, at pre-agreed seams.

Run typechecking regularly, single test files regularly, and the full test suite once at the end.

Once done, review the work with this skill set's own code-review skill: /mattpocock-skills:code-review when these skills are installed as the Claude Code plugin, /code-review otherwise. Do not use Claude Code's built-in /code-review — that is a different review.

Commit your work to the current branch.
