## git Style Guide

### Branching

- Use feature-specific branches as much as you can. Don't work on master if your code has been released or depended upon.

- Name your branches with this format: `contributorInitials-JIRA-ticketNumber-keywords` Always use dashes, _not_ underscore s.

- Branch names that are easy to read and understand are the goal; feel free to exclude keywords etc if it will enhance readability.

### Commit Messages

1. Capitalize the subject line.
2. Do not end the subject line with a period.
3. Separate subject from body with a blank line.
4. Use the imperative mood in the subject line (Read the commit to yourself while appending "this commit will ...").
5. Limit the subject line to 50 characters.
**ProTip:** Use your editor for creating git commit messages (`git commit`, without `-m` on the command line). If you want to be sure the subject is under 50 characters. In commit messages longer than 50 characters, the offending characters will be a different color.
6. Wrap the body at 72 characters.
7. Use the body to explain what and why vs. how.

Basically follow [these](https://chris.beams.io/posts/git-commit/) rules whenever possible.

### Mistake fixing

- You are allowed to use creative git tricks to make your branches clean, but not other branches. Don't rebase `master` and force-push it.

- Look at [our presentation about fixing up git branches](/docs/git_102.pdf) to learn more tips.
