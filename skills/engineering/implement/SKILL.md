---
name: implement
description: "Implement a piece of work based on a spec or set of tickets."
disable-model-invocation: true
---

Implement the work described by the user in the spec or tickets.

If the user passes a ticket reference, fetch it from the issue tracker and state its title before starting. If the reference is ambiguous, ask.

Call the Skill tool with "tdd" where possible, at pre-agreed seams.

Run typechecking regularly, single test files regularly, and the full test suite once at the end.

Once done, call the Skill tool with this skill set's own code-review skill to review the work: "mattpocock-skills:code-review" when these skills are installed as the Claude Code plugin, "code-review" otherwise. Claude Code's built-in code-review is a different review; don't substitute it for this step unless you're explicitly asked to.

Commit your work to the current branch.
