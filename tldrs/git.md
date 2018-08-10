## TL;DR (Too long; Didn't Read): git Edition

#### Dos:
- Name your branches `[initials]-[feature description]`, always with hyphens between words.
- Use [karma style commit messages](http://karma-runner.github.io/2.0/dev/git-commit-msg.html).
- Avoid using merges, it destroys history; always use rebases to preserve history.

#### Dont's:
- Don't work on `master` unless it is a brand new project and hasn't been deployed.
- Try to avoid anything too crazy like rebasing branches others are actively using.