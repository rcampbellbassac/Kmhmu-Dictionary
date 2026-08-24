# Security Policy

## Reporting a Vulnerability

If you discover a security concern related to this repository, please
report it privately rather than opening a public issue:

- Use GitHub's [private vulnerability reporting](https://github.com/rcampbellbassac/Kmhmu-Dictionary/security/advisories/new)
  for this repository.
- If that isn't available to you, please contact the maintainer through
  GitHub directly rather than filing a public issue.

## Scope

This repository is a plain-text word list (`kmhmudict.txt`) with no build
pipeline, executable code, or runtime application. There's minimal attack
surface here — the main concerns would be malicious/corrupted content
being merged in, or supply-chain risk for any downstream project that
parses this file programmatically. Reports along those lines are welcome.
