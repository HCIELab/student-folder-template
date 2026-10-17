# 6.8500 working folder: rules for the AI

This is a student's working folder for MIT 6.8500 (AI-assisted HCI research). The student does one lab at a time, and each lab has its own folder in `labs/` (map in `labs/README.md`). These rules apply to every session in this folder.

## Where to read and write

- Save new files in the folder the student's prompt names, never in the top folder or in another lab's folder.
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

- Save scripts in the lab folder, next to their output.
- Prefer Python's standard library. Scripts must run on Mac and on Windows: use `pathlib` for paths, no shell-only tricks.

## Git

- Do not commit, push, or create branches or worktrees. The student commits in GitHub Desktop after each lab.

## The student's own rules

Add your rules below this line.
