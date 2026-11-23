# 6.8500 working folder: rules for the AI

This is a student's working folder for MIT 6.8500 (AI-assisted HCI research). The student does one lab at a time, and each lab has its own folder in `labs/` (map in `labs/README.md`). These rules apply to every session in this folder.

## Where to read and write

- Save new files in the folder the student's prompt names, never in the top folder or in another lab's folder.
- Keep that folder easy for the student to read: its top level is for the lab's results file (`<lab>-results.md`) and the files the student opens or hands in (charts, `technology.md`, spreadsheets). Each lab or homework folder has two subfolders for everything else:
  - `data/`: the starter files and the data files a prompt names with `data/` in its path (for example `labs/lab01-research-areas/data/research-area-papers-with-technology.csv`). Save a file there only when the prompt names it there.
  - `ai-work/`: everything else you make: scripts, intermediate CSV or JSON files, test output, any file the prompt does not name. Create the folder if it is missing, and do not tell the student to open these files.
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

- Save scripts in the `ai-work/` subfolder of the folder you work in. Run them yourself; do not ask the student to run them.
- Prefer Python's standard library. Scripts must run on Mac and on Windows: use `pathlib` for paths, no shell-only tricks.

## Git

- Do not commit, push, or create branches or worktrees.

## The student's own rules

Add your rules below this line.
