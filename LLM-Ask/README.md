# LLM-Ask

This folder is the repository's human-to-LLM review workspace.

Use it for:
- questions and prompts prepared for an LLM
- exported chat context
- architecture, content, UX, or code reviews
- peer-review notes and model critiques
- proposed changes before they are promoted into normal project files

Recommended layout when needed:

```text
LLM-Ask/
  INPUT/
  OUTPUT/
  REVIEWS/
  ARCHIVE/
```

## Rules

1. Treat LLM material as advisory until a human accepts it.
2. Do not put secrets, API keys, signing keys, customer credentials, or private tokens here.
3. Do not treat generated code as production code until it is reviewed and moved into the normal project tree.
4. Keep durable project documentation in the project's normal documentation location.
5. Keep filenames descriptive and date/version review rounds when useful.

For public repositories, assume everything committed here can be read by anyone.
