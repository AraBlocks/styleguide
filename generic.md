## Ara Generic Programming Guidelines

### Table of Contents

  1. [Comments](#comments)
  1. [Debugging](#debugging)
  1. [Secrets](#secrets)
  1. [Code Smells](#code-smells)
  1. [(Programming) Life Protips](#life-protips)

### Comments

- **Multi-line Comments**: Not allowed inside of classes and functions.

  - Remember another person will read this. Be as explicit, clear, and precise as you can be.

- **Single-line Comments**: Allowed anywhere but use sparingly.

  - Too many comments is a code smell (bad thing) and means your code isn't self-descriptive.

### Debugging

- **Debuggers**: Non-triage debugging functionality should not be committed.

  - If it doesn't help future people figure out why a system crashed, don't put it in `master`.
  - Do not commit code that is only useful during debugging (shimming something, etc). If it isn't useful for running in production, don't put it in `master`.

### Code Smells

- **Excessive variable declarations**: Try to avoid declaring non-constant variables that will only be used once.

  - Excessive non-meaningful code distracts from more important code.

- **Magic Values**: Avoid having hard-coded strings / numbers / values in your code, put them in a constant with a descriptive variable name.
