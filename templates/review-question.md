# A question to the owner (template)

The agent asks the owner only four kinds of thing, and the question begins with which:

- `Money:` spending the owner's money.
- `Public:` anything public or in the owner's name.
- `Mail:` anything sent as the owner.
- `Access:` access, accounts, deleting the owner's data, the rules that do not bend.

Everything else the agent decides on a stronger model's recommendation and records (see
[decision-entry.md](decision-entry.md)).

A question:

- links the review page the owner answers from;
- has two to four options, the recommendation first, each `Label: what choosing it sets in motion` (label at most
  60 characters, detail one line);
- offers real ways to go. "Do it / not now / other" is not a question; something only the owner can do is a task of
  his, with a due date;
- never goes on without an answer if it publishes, sends, spends or speaks for the owner. A question whose next step
  does none of those may go on with the recommendation after two days, and says so where it is shown;
- is asked once. Two asks about the same thing become one.

---

```
Public: may <the article, its PDF and the repo> go out as drafted, and where should the repo live?
See <link to the review page>.

  1. <Recommended way>: <what happens next if chosen>   (recommended)
  2. <Second way>: <what happens next if chosen>
  3. <Third way>: <what happens next if chosen>

  Or tell the agent what to do instead.
```
