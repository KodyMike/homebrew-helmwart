# Helmwart Homebrew tap

```bash
brew tap kodymike/helmwart
brew install helmwart
helmwart --version
```

`helmwart` is design-time threat modeling for agentic-AI systems, in your CI. It
reads a real agent config — MCP, n8n, LangGraph, CrewAI and more — and reports
its threat model against OWASP Agentic Top 10, MAESTRO and MITRE ATLAS,
including the lethal-trifecta reachability check.

## What this installs

A single self-contained native binary, matched to your architecture. No Node
runtime is required. The formula fetches the same platform tarball npm serves,
so there is one set of bytes behind both install routes.

The macOS binaries are signed with a Developer ID and notarised by Apple.

## npm works too

```bash
npm i -g helmwart
```

Same binary, same version. Use whichever fits your machine.

## This file is generated

`Formula/helmwart.rb` is produced by `scripts/gen-homebrew-formula.mjs` in the
main repository, from the hashes of the published tarballs. Do not edit it here
— four URLs and four SHA-256 values change every release, and a hash somebody
retyped is a hash nobody can trust.
