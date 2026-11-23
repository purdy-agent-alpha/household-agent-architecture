# Decision records (templates)

Two kinds of record keep the owner's word and the agent's choices apart.

## A project the owner asked for (decision log, kept by the setup assistant)

A project starts only once the owner's words are recorded verbatim, with where and when he said them. A summary or
a proposal by the agent is a draft that waits for his yes.

```markdown
## <date> <time>: <project name>

Owner's words (verbatim, spelling kept): "<exactly what he wrote or said>"
Where: <the channel or session it came from>
What it starts: <the project, in one line>
Plan: <link to the plan, written afterwards and checked against the words above>
```

## A decision the agent takes itself (a comment on the task)

Design, which candidate, research direction, whether to merge or go on: decided on the recommendation of a stronger
model, written in one comment, and collected for the owner's weekly read. He can reverse any of them.

```
Decided: <what was chosen, in one line>. Why: <the reason that settled it, and what was weighed against it>.
To reverse: <the concrete steps, including what to undo or withdraw>.
```

Example:

```
Decided: draw the architecture diagram as a hand-written SVG rather than in a diagramming tool. Why: the source is
plain text, so a change shows in a diff and needs no tool or account; a tool would lay it out faster. To reverse:
redraw it in the tool and keep its export beside the SVG.
```
