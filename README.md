# jump-program — archived

This repo is no longer the working copy. It's kept for history.

**Where things went:**

- **Programme reference** (principles, goals, macrocycle plan, phases 0–6, reactive
  profile assessment, upper body work, transcripts) → the Obsidian vault at
  `~/Development/vault`. That's the live copy — edit it there, not here.
- **Session logging and all measured metrics** → Apex (`~/Development/apex`), which is
  also what's on the phone.

**Still here and still load-bearing:**

- `profile.yaml` and `logs/cycle-1.yaml` are fetched at runtime from
  `raw.githubusercontent.com/Matthew-Burfield/jump-program/main/` by the dashboard that
  used to live at `index.html`. Do not delete or move them while anything still serves
  that dashboard.
- `index.html` was removed in the commit that added this README. Restore with
  `git checkout <that commit>^ -- index.html` if the hosted dashboard is still wanted.
- `tracking.md` — empty per-cycle result tables, superseded by Apex. Kept because it isn't
  a straight duplicate: its testing-method section was rewritten into `Testing Protocol.md`
  in the vault, but the result tables exist nowhere else.

All 20 migrated `.md` files were deleted from this repo once each vault copy was verified
to contain the original byte-for-byte. Git history still has them. There is now exactly one
copy of each, in the vault.
