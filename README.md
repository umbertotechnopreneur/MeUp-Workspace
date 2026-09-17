# MeUp Workspace

This repository brings together the MeUp projects:

- [MailMeUp](MailMeUp)
- [PromptMeUp](PromptMeUp)
- [TrackMeUp](TrackMeUp)

They remain independent Git repositories, included here as submodules at their `main` branches. The workspace root contains the shared working agreement for all three projects.

## Clone on a new computer

```powershell
git clone --recurse-submodules https://github.com/umbertotechnopreneur/MeUp-Workspace.git
```

For an existing checkout, retrieve the configured project revisions with:

```powershell
git pull --recurse-submodules
git submodule update --init --recursive
```

Each project keeps its own history, remote, and project-specific instructions. Commit and push changes from the relevant submodule; commit a workspace update only when the submodule revision needs to be recorded here.
