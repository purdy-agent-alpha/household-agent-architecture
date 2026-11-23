# Change request (template)

The agent may not change its own runtime: its configuration, its accounts and connections, the host, or anything
that runs as another user. It asks for such a change by writing one file like this. The owner approves or denies
it, and the setup assistant carries out the approved ones.

Rules for the file:

- Under 3,000 characters, in the agent's own words. No pasted outside text (a mail, a web page, a log line from
  another program): the reader is approving the agent's request, not someone else's.
- No secret values, not even the one being rotated.
- Never edited after filing. A changed need is a new request; a mistaken one is withdrawn by the owner.
- The task that needs it is blocked `Waits for <the setup assistant> on <file> (until <date>)`, so it comes back on
  its own when the setup assistant answers on the task, or on the date.

---

```markdown
# <What to change, in one line> (<task id>)

Need: <the change, exactly: what, where, and how to do it safely (for example "restart rather than reload, at a
moment no worker is mid-turn")>.

Why: <what went wrong or what it unblocks, with the evidence: what was seen, when, and how often. Facts, not
guesses.>

What was tried: <what the agent did on its own side, and what it may not do itself. "Nothing" is a fine answer.>

What done looks like: <a check anyone can run afterwards: "the next channel change is followed by a restart, and
no delivery failure is logged after it".>

The agent's side: <what changed in its own rules or tools so the same need does not come back>.
```
