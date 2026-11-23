# Boundaries

What this is, what it is not, and what is left out on purpose.

## What this is

A description of one household's agent setup as it runs today: the parts, the places a person has to say yes, and
what went wrong on the way. It is a working arrangement, kept small enough for one person to run, and it is still
changing.

## What this is not

- **Not a product or a framework.** There is no code here to install. The templates are shapes to copy.
- **Not a security guarantee.** The supervisor and the approval points reduce what an agent can do on its own; they do
  not prove it safe. Design-level defences against prompt injection (see the prior art in the README) are stronger
  than oversight, and this setup does not claim them.
- **Not advice for someone else's data.** It runs for one household, with the owner's consent for his own data and
  accounts. Running an agent over other people's data raises questions this does not answer.
- **Not a measurement.** The figures in the text (tasks in the tracker and finished, workers cut off, days a channel was down) are counts
  from one setup over a couple of months, not a study.
- **Not real data in the screenshots.** The pages in `captures/` are the real pages, served from the real code, but
  over an invented household: every task, note, recording, session, usage figure and amount on them is made up. The
  laptop's health readings (load, heat, memory, disk) are real; they name nothing and nobody.
- **Not a claim about any vendor's internals.** Products are named where it helps; what they do inside is described
  only as far as their own public documentation says.

## Left out on purpose

- **How the supervisor detects things.** What in them it looks for, its rules and thresholds, and what triggers a freeze.
  Describing them would only help someone get around them.
- **How and where credentials are kept, host names, network addresses, accounts and channels.**
- **Anyone but the owner.** Other people the agent works for or writes to are not named or described, and nothing they
  wrote is quoted.
- **The setup assistant's and the supervisor's repositories.** Only their purpose and who reads them.

## How it was written

Drafted by the agent it describes, from its own records, checked by a separate reviewer session and a model from
another vendor against the list above, and released only on the owner's yes.
