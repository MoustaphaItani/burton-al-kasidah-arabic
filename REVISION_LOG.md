# trAIceabLe — revision and contribution log

A preliminary AI-generated Arabic translation, undergoing human revision and awaiting independent validation.

## Project and contributors

- Work: Richard Francis Burton, *The Kasidah*.
- Repository: https://github.com/MoustaphaItani/burton-al-kasidah-arabic
- Project initiator and human editor: **Moustapha Itani**.
- Editor's GitHub account: **MoustaphaItani**.
- Preliminary translation: **ChatGPT / OpenAI**, directed by Moustapha Itani.
- Reported first-draft model label and duration: **GPT-6.1 Sol Max; 1h 10m 13s**, as recorded by the project initiator.
- This log template: prepared with ChatGPT; future entries describe the actual contributors to each revision.

## Baseline — v0.1-ai-draft

- Source archive: `v0.1-ai-draft.zip`, exported from the compiling Overleaf project before human literary revision.
- Archive SHA-256: `8d8fbca01bd2b6abcd8f288567275157a87d4cf996132191167f5b568c71511f`.
- Status: preliminary AI-generated translation; independent validation pending.
- Existing global couplet numbers are the stable identifiers for verse revisions. Preserve them when editing wording.
- No human verse revision has yet been entered in this log.

The archive checksum identifies the exported ZIP. It is not a Git commit identifier.

## What the history records

GitHub records saved versions and the text differences between them. Overleaf's GitHub integration attributes its pushes to the connected GitHub account owner. Synchronization is manual; multiple edits since the previous push may appear together in a single commit. Edits by collaborators are also attributed to the linked account when pushed through this integration.

This log records actual wording contributors, human or AI involvement, reasons, sources, and review status. Those are declared by the contributors; Git account attribution alone does not establish them.

Overleaf documentation:
https://docs.overleaf.com/integrations-and-add-ons/git-integration-and-github-synchronization/github-synchronization

## Editing routine

1. Make one coherent change, such as a single couplet or a related group of edits.
2. Append an entry below using the template. The default contributor for your own wording is Moustapha Itani. Declare AI assistance or other contributors when present.
3. Recompile in Overleaf.
4. Push to GitHub using a short message with the passage and origin, for example `Human revision: couplet [number] — [reason]`.
5. Check the saved commit and its differences on GitHub. The commit also contains the corresponding log entry.

Use separate pushes for changes you want to see as separate stages. Keep earlier log entries and append subsequent revisions, including reversions. The Git differences preserve before and after wording, so copying both versions into this log is optional.

## Contribution labels

| Label | Meaning |
| --- | --- |
| Human | Wording or quotation selection supplied by a human without AI drafting of that change. |
| AI-generated | AI supplied the wording adopted in this change. |
| AI-assisted | A human developed or revised the wording with AI drafting or suggestions. |
| Mixed | A batch contains distinct human and AI contributions; identify each passage. |

Record technical changes, such as LaTeX formatting, separately from literary changes when helpful. A human reviewer can validate AI-generated wording without becoming its wording author; record the reviewer in the review field.

## Revision entries

Append completed entries here. The template below is not a completed revision.

### R[0001] — [short description]

- Date: [YYYY-MM-DD].
- Passage: [global couplet number, prose section, or file].
- Source file: [for example poem/02.tex].
- Wording contributor: Moustapha Itani [change if another contributor supplied the wording].
- Origin: [Human / AI-generated / AI-assisted / Mixed].
- Change type: [meaning correction / poetic phrasing / quotation / punctuation / formatting / other].
- Reason: [short explanation].
- Source or quotation evidence: [citation or URL, or not applicable].
- AI assistance, if any: [tool and contribution, or none].
- Review status: [pending independent review / reviewed / requires further source checking].
- Reviewer and review date: [when applicable].

The commit containing this completed entry links it to the changed source. Add a commit link later if useful.
