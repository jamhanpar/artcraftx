# Contributor guidance

Read [CLAUDE.md](CLAUDE.md) for the existing project structure and coding conventions.

## Shared Craft libraries

Before adding or changing reusable file-format, codec, protocol or UI code, check [craft-libs](https://github.com/storytold/craft-libs) and existing contributor work; reuse compatible public APIs or extend the appropriate shared library instead of adding an app-local duplicate, keeping app-specific policy and model mapping local and preserving compatibility, security limits and regression coverage. Keep existing framework and platform requirements intact.
