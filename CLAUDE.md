# Claude Code: rules for this repo

## Never touch a main local folder (Charlie, 15 Oct 2026)

A session must never reset, checkout, clean or stash a main local folder: the copy of this repo (or any Aposlo repo) that lives in Charlie's own folders, such as `C:\Dev\Aposlo\aposlo-next` or a client site under `C:\Dev\Website`. No `git reset`, `git checkout -- <file>`, `git restore`, `git clean` or `git stash` there, and no deleting or overwriting its files.

- Work only in your own worktree or a fresh clone made from GitHub, and push from there.
- If you find uncommitted changes in a main folder, leave them exactly as they are and tell Charlie what they are. He decides what happens to them.
