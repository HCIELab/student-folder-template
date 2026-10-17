# Your working folder for 6.8500

This is the starter for your working folder, `Documents/6.8500`. You copy it once, in Homework 1 (install and sign in). From then on, every lab puts its files in its own folder in `labs/`, so nothing ends up scattered over your disk.

## What is inside

```
6.8500/
├── README.md          this file
├── CLAUDE.md          rules the AI reads at the start of every session in this folder
├── .gitignore         what git never backs up: your API keys, downloaded PDFs, your paper
├── .claude/
│   ├── settings.json  course settings for the AI (no memory between sessions)
│   └── skills/        your skills, one folder each; the AI uses them on its own
├── homework/          one folder per homework that makes files
├── labs/              one folder per lab (map in labs/README.md)
└── psets/             the pset starters go here
```

Names that start with a dot (`.gitignore`, `.claude`) are hidden. To see them:

- **On a Mac:** in Finder, press Cmd+Shift+. (period).
- **On Windows:** in File Explorer, choose **View → Show → Hidden items**.

## Set it up (Homework 1)

1. Copy this folder into your Documents folder and rename it `6.8500`. Keep it outside Dropbox, iCloud Drive and OneDrive: git and sync folders fight. If your whole Documents folder is synced (on a Mac: iCloud **Desktop & Documents Folders**; on Windows: OneDrive folder backup), put `6.8500` in your home folder instead.
2. In GitHub Desktop, choose **File → Add Local Repository** and pick `6.8500`. It says the folder is not a repository yet: click **create a repository**, then **Create Repository**. Then click **Publish repository**, check that the account is github.mit.edu and **Keep this code private** is checked, and publish.
3. In the Claude desktop app, open the **Code** tab, choose **Local**, and select `6.8500`. Leave the worktree option off, so the AI works in this folder and not in a hidden copy of it.
4. Check that the AI works in your folder. Ask:

   ```
   Hello, what is in the folder?
   ```

   The answer looks something like this (yours will differ):

   > This is your 6.8500 working folder. At the top: README.md (how to set it up), CLAUDE.md (rules for me), .gitignore, and .claude/ with the course settings and an empty skills/ folder. Then homework/, labs/ (one folder per lab, lab01-research-areas to lab15-project-pages) and psets/. The folders are still empty apart from a .gitkeep file each.

   Then check that it works in the folder itself and knows the course rules. Ask:

   ```
   Without opening any file: what is the full path of the folder you work in,
   and which rules do you follow here?
   ```

   The answer looks something like this:

   > /Users/yourname/Documents/6.8500 (on Windows: C:\Users\yourname\Documents\6.8500). I save files only in the lab folder your prompt names, never print or commit an API key, check facts about papers against a source, and leave git to you.

   You are done when the first answer names `CLAUDE.md` and `labs/`, and the second gives a path that ends in `6.8500` and at least one rule, such as never printing keys.

## Rules

- **One folder per lab.** Each lab names its folder in `labs/`. Ask the AI to save its files there.
- **Keys never go into git.** `.gitignore` already covers `semantic-scholar-key.txt`, so GitHub Desktop never lists it under Changes.
- **Back up after each lab.** Open `6.8500` in GitHub Desktop, commit, and click **Push origin**.
- **Commit messages say where and what.** In GitHub Desktop's **Summary** field, start with the lab or homework and the step, then say what changed:
    - `Lab 1 Step 5: research_area.png for soft robotics`
    - `Lab 2 Step 3: status and closest_paper columns in not-carried-over.csv`
    - `Homework 1 Step 6: lab02-idea-patterns folder for the Semantic Scholar test`

  Use the **Description** field for anything longer, such as what you fixed by hand. One commit per step is easiest to read back later, but one per lab is the minimum.
- **Your paper is separate.** `labs/lab04-uist-paper` (from Homework 2a) is its own git repository, linked to Overleaf. Overleaf keeps it, so this folder's backup leaves it out.
- **`CLAUDE.md` is yours.** Add your own rules for the AI at the end of it.

| If you get stuck | Fix |
| --- | --- |
| You cannot see `.gitignore` or `.claude` | They are hidden; see above. |
| The AI cannot find `semantic-scholar-key.txt` | The file got a different name: `semantic-scholar-key.txt.txt` (Windows hides the second ending) or `semantic-scholar-key.rtf` (Mac TextEdit without **Make Plain Text**). Save it again as plain text with the exact name. |
| The AI says it has no access to a folder or to files | You are in the **Chat** or **Cowork** tab. Open the **Code** tab and start a **Local** session on `6.8500`. |
| The AI lists files that are not from the starter, or the path ends in another folder name | The session is on a different folder. Start a new session and select `6.8500` itself, not a folder inside it. |
| The path ends in `.claude/worktrees/...`, or the AI's edits do not show up in your folder | The session was started with the worktree option on, so the AI works in a hidden copy. Start a new session on `6.8500` with it off. |
| The AI cannot name any rule without opening a file | `CLAUDE.md` is missing from the top of `6.8500`. Copy it again from the starter. |
