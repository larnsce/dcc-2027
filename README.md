# DCC 2027 workshop submission

Workshop proposal by Lars Schöbitz (Global Health Engineering, ETH Zurich) for the Data Curation Conference 2027 of the Research Data Management Network at the University of Basel. The title is "From raw data to a website for humans: a live curation workflow with every AI step disclosed". The abstract is final and goes to the organisers by email on 21 October 2026.

## Conference

- Data Curation Conference 2027, "Don't ghost your data or it will haunt you", a cross-disciplinary conference on research data curation, reusability and AI
- Organiser: Research Data Management Network, University of Basel
- Date and place: Thursday 14 January 2027, University of Basel
- Format submitted: workshop session, 30 to 50 minutes, hands-on and interactive
- Submission rules: title and abstract of at most 350 words, naming the discipline, the use case and the data curation aspects, by email to researchdata@unibas.ch with the subject "Submission DCC"
- Due 21 October 2026 (extended), notification by 15 November 2026
- Accepted presentations go on Zenodo under CC BY 4.0 or CC BY-SA 4.0
- Conference page: https://researchdata.unibas.ch/en/services/data-curation-conference-2027/

## AI disclosure

An AI coding agent (Claude Code with Claude Fable 5.1) drafted the abstract from a spoken draft and a prompt that I wrote without AI. I chose between the drafts, reviewed every version and approved the final text. Every commit in this repository names its author type in a trailer, and the prompts behind the AI assisted commits are archived in `prompts/`. The full statement, with what the agent did, what I did and how to verify it, is in [ai-disclosure.md](ai-disclosure.md).

## Folders and files

- `submission/` - The abstract as submitted: `abstract-workshop.qmd` is the source, `abstract-workshop.docx` the rendered file attached to the email
- `ai-disclosure.md` - The full AI disclosure statement
- `drafts/` - What the abstract was built from: `spoken-draft.md` and `initial-prompt.md`, written without AI, and the two earlier versions with review notes
- `planning/` - `session-plan.md`, planning notes for the 50 minutes, not part of the submission
- `prompts/` - Archived prompts behind the AI assisted commits, one file each
- `references/` - The call for proposals, kept local and out of git
