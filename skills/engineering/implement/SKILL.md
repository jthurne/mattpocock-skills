---
name: implement
description: "Implement a piece of work based on a spec or set of tickets."
disable-model-invocation: true
---

Implement the work described by the user in the spec or tickets.

Use /tdd where possible, at pre-agreed seams.

Run typechecking regularly, single test files regularly, and the full test suite once at the end.

Once done, review the work with this skill set's own code-review skill: /mattpocock-skills:code-review when these skills are installed as the Claude Code plugin, /code-review otherwise. Claude Code's built-in /code-review is a different review; don't substitute it for this step unless you're explicitly asked to.

Commit your work to the current branch.
