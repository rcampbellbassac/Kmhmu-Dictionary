# Contributing to the Kmhmu' Dictionary

Thank you for helping build this dictionary! Kmhmu' (also spelled Khmu, Khmu', Kammu, or
Khamu — ISO 639-3: `kjg`) has no single standard written form, so every entry here depends
on people who actually know the language. To keep the dictionary trustworthy — for
learners, developers building language tools, and Kmhmu' speakers themselves — every
submission needs to be **traceable to a real source**.

## Before you submit

Each new entry needs:

1. **The word** — in whatever script/romanization you're using (Lao script and/or Latin
   are both fine; note which one).
2. **A gloss** — meaning in Lao, English, or both.
3. **Dialect/region** — Kmhmu' has significant dialectal variation (e.g. Kmhmu' Rok,
   Kmhmu' Yuan, Kmhmu' Lu, and others). Note the dialect or the village/province/country
   it's from if you know it. If you don't know, say "unknown dialect" rather than omit it.
4. **Your source** — one of:
   - Your own native-speaker knowledge (say so, and where you're from/learned it).
   - A specific published dictionary or wordlist (see [`RESOURCES.md`](RESOURCES.md)),
     with page number if possible.
   - A conversation with a named or described speaker/elder (e.g. "confirmed with my
     grandmother, Kmhmu' Rok dialect, Luang Prabang").

Put this information in the **pull request description**, not just the commit — PRs
without a source note will be asked for one before merge.

## How entries get confirmed

Because there's no authoritative online Kmhmu' database to check against automatically,
confirmation here is a **human process**:

- A maintainer or another contributor cross-checks new words against a published source
  where one exists (see `RESOURCES.md`).
- Where no published source covers a word, we look for a **second independent
  confirmation** — ideally from a speaker of the same dialect who isn't the original
  submitter — before merging.
- Entries that can't be corroborated aren't rejected outright, but are held in the PR
  with a note (e.g. "single-source, dialect unconfirmed") so users of the dictionary know
  the confidence level.

If you know other Kmhmu' speakers who'd be willing to review entries, we'd love to add
them as reviewers — open an issue or reach out.

## File format

Add one word per line to `kmhmudict.txt`:

```
<word>	<Lao script (if applicable)>	<gloss>
```

Keep the existing tab/spacing convention already in the file. Don't reformat or reorder
existing lines in the same PR as new additions — keep dictionary-content PRs focused so
they're easy to review.

## Submitting

1. Fork the repo and create a branch.
2. Add your entries to `kmhmudict.txt`.
3. Open a PR describing dialect + source for each new word (see above).
4. A maintainer will review, may ask follow-up questions about sourcing, and will merge
   once entries are confirmed (or clearly marked with their confidence level).

Questions, corrections to existing entries, and disputes about dialect variants are all
welcome as GitHub issues.
