# A review page (template)

One page per piece of work that needs the owner's eye, readable on a phone. It is built from a small manifest; the
page server draws it, keeps what the owner writes, and posts each note to the task.

## The sections, in order

1. **Intent** (always first, a few lines): what the work is for, what the owner is asked to decide, and the one or two
   things that need his eye. He should be able to answer from this alone.
2. **The work**, one section per thing to read, open or try: a draft, a PDF, a preview in a frame, a video.
3. **What was checked**: the quality pass's findings, what it checked, and suggestions the owner may take.
4. **Earlier rounds** (only on a later round): what each round was told and how the work answered it. Notes from
   earlier rounds are folded away, not deleted.
5. **Anything else**: a note on the whole page.
6. **Your answer**: the task's question with its options, drawn by the tracker, and a line for "do this instead".

Under every section: a text note (likes, dislikes), a voice recording (transcribed on the machine, and summarised),
and images (metadata stripped before they are kept). Each lands as a comment on the task.

## The manifest

```json
{
  "task": "<task id>",
  "date": "<yyyy-mm-dd>",
  "title": "<what this is, in a few words>",
  "summary": "<the intent again, in two or three lines, for the index>",
  "root": "<folder served for links and previews; never one that holds keys>",
  "sections": [
    { "id": "intent", "title": "What this is for", "body": "<markdown>" },
    { "id": "article", "title": "The article", "file": "article.md",
      "links": [{ "label": "PDF", "href": "article.pdf" }] },
    { "id": "quality", "title": "What was checked", "body": "<markdown>" }
  ],
  "weigh_in": "<what changes if the owner weighs in>",
  "if_not": "<what happens if he does not>"
}
```
