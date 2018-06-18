## git Style Guide

### How to use git

// TODO: Put git 101 here

### Branching

Use feature-specific branches as much as you can. Don't use master if your code has been released or depended upon.

Name your branches with this format: `contributorInitials-JIRA-ticketNumber-keywords` Always use dashes, _not_ underscores.

Feel free to leave pieces out if they don't apply, we want to improve readability so if it doesn't make sense to include, don't include it.

### Commits

Try to use your editor for creating git commits (`git commit`, without -m) if you want to be sure the subject is under 50 characters (If you go over 50 characters, the offending characters will be a different color)

1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line (Read the commit to yourself while appending "this commit will")
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how

https://chris.beams.io/posts/git-commit/

### Mistake fixing

You are allowed to use creative git tricks to make your branches clean, but not other branches. Don't rebase `master` and force-push it.

Look at [our presentation about fixing up git branches](/docs/git_102.pdf) to learn more tips.
