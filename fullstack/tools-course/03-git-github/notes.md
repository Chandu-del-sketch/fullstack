# Git Setup Notes

## Repository Setup
- Navigated to the course repository root.
- Initialized Git at the root level (not inside the module folder) as given as note.


## Files Added
- `notes.md` – documents Git setup
- `workflow.md` – explains Git workflow
- `experiment-01.txt` – used to test commits

## Git Commands Used
git init
git status
git add .
git commit -m "Initialize Git module"
git remote add origin <repo-url>
git pull origin main --allow-unrelated-histories --no-rebase
git push -u origin main

 - By this way the setupe was completed.


# Reason why do not commit these

**Large media files** — They increase repository size and slow down cloning and pulls.

**Data dumps** — They can be huge, sensitive, and should be stored outside Git.

**zip/tar archives** — They contain generated files that Git cannot diff or track efficiently.

**Compiled binaries** — They are machine-generated and should be built from source, not versioned.