# 6.8500 working folder: rules for the AI

This is a student's working folder for MIT 6.8500 (AI-assisted HCI research). The student does one lab at a time, and each lab has its own folder in `labs/` (and each homework in `homework/`). The folders start empty: each lab or homework hands out its files in a starter zip at its start. These rules apply to every session in this folder.

## Where to read and write

- Save new files in the folder the student's prompt names, never in another lab's folder. The top folder holds only `README.md`, this file, `my-research-areas.md` (the research areas the student has looked at) and one progress page per research area (`<research-area>.md`, e.g. `circuit-prototyping.md`); write there only when a prompt names one of these files.
- Students can explore more than one research area, so from Lab 1 on, each lab keeps one folder per research area, named after it in lowercase with hyphens (for example `labs/lab01-research-areas/circuit-prototyping/`, the same name as its progress page). Work only in the folder of the research area the student named for this session; never write into another research area's folder. If you don't know which research area (or, in Lab 2, which technology) the student is working on, ask.
- Keep the folders easy for the student to read. A lab folder holds:
  - `data/`: the starter files, shared by all research areas.
  - `scripts/`: every script you write.
  - one folder per research area. Its top level is for the lab's results file (`<lab>-results.md`) and the files the student opens or hands in (charts, the technology file `technology-<technology>.md`, spreadsheets). Inside it, `data/` holds the data files a prompt names with `data/` in its path (for example `labs/lab01-research-areas/circuit-prototyping/data/circuit-prototyping-papers.csv`); save a file there only when the prompt names it there. `intermediate-files/` holds every other file you make: intermediate CSV or JSON files, test output, any file the prompt does not name.
  - In Lab 2 (idea patterns), each research-area folder has one folder per technology (for example `labs/lab02-idea-patterns/circuit-prototyping/laser-cutter/`), laid out the same way. Work only in the folder of the technology the student named.
  - A homework folder without research-area folders (for example `homework/hw1b-uist-previews`) has `data/`, `scripts/` and `intermediate-files/` directly inside it.
  Create `scripts/` and `intermediate-files/` if they are missing, and do not tell the student to open their files.
- When you read a file a prompt names and it is not where the prompt says (for example a starter file at the top level instead of in `data/`), tell the student where you found it and ask them to move it; do not work from a copy elsewhere.
- Read only the files and folders the prompt names. Labs often check what you know before a step: when asked which files you can see, or what you know about earlier results, answer only from the folder named. Do not open other labs' folders to fill gaps.
- `labs/lab04-uist-paper/` is the student's paper, a separate git repository linked to Overleaf. Edit it only when the prompt asks for it.
- Ask before you delete, move or overwrite a file you did not create in this session.

## Keys

- Never print, copy, paste or commit an API key. A script reads `semantic-scholar-key.txt` from the file and sends it in the request header; the key never appears in your answer or in a file you write.
- If a key appears in your output by mistake, tell the student, so they can ask the teaching team for a new one.

## Sources

- Facts about papers (titles, authors, years, venues, quotes) come from a source you query or a file in the folder (Semantic Scholar, Crossref, a PDF), not from memory. Say which source. Mark anything you could not check as unverified.
- Quote passages exactly. Do not paraphrase inside quotation marks.

## Scripts

- Save scripts in the `scripts/` subfolder of the lab's or homework's folder. Run them yourself; do not ask the student to run them.
- Prefer Python's standard library. Scripts must run on Mac and on Windows: use `pathlib` for paths, no shell-only tricks.

## Git

- Do not commit, push, or create branches or worktrees.

## The student's own rules

Add your rules below this line.
