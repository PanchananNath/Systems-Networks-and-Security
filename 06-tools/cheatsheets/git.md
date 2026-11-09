# Git cheat sheet

| Task | Command |
|---|---|
| New branch | `git switch -c feature/x` |
| Stage interactively | `git add -p` |
| Amend last commit | `git commit --amend` |
| Rebase onto main | `git fetch && git rebase origin/main` |
| Undo last commit, keep changes | `git reset --soft HEAD~1` |
| Find a bad commit | `git bisect start; git bisect bad; git bisect good <sha>` |
| Rename keeping history | `git mv old new` |
| Pretty log | `git log --oneline --graph --decorate --all` |

Commit messages follow [Conventional Commits](https://www.conventionalcommits.org): `docs(networks): add QUIC notes`.
