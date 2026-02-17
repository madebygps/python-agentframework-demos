# Instructions for coding agents

This repository contains many examples of using the Microsoft Agent Framework in Python (agent-framework), sometimes abbreviated as MAF.

The agent-framework GitHub repo is here:
https://github.com/microsoft/agent-framework
It contains both Python and .NET agent framework code, but we are only using the Python packages in this repo.

MAF is changing rapidly still, so we sometimes need to check the repo changelog and issues to see if there are any breaking changes that might affect our code. 
The Python changelog is here:
https://github.com/microsoft/agent-framework/blob/main/python/CHANGELOG.md

MAF documentation is available on Microsoft Learn here:
https://learn.microsoft.com/agent-framework/
When available, the MS Learn MCP server can be used to explore the documentation, ask questions, and get code examples.

## Spanish translations

There are Spanish equivalents of each example in /examples/spanish.

Each example .py file should have a corresponding _spanish.py file that is the translation of the original, but with the same code. Here's a guide on what should be translated vs. what should be left in English:

* Comments: Spanish
* Docstrings: Spanish
* System prompts (agent instructions): Spanish
* Tool descriptions (metadata like description=): English
* Parameter descriptions (Field(description=...)): English
* Identifiers (functions/classes/vars): English
* User-facing output/data (e.g., example responses, sample values): Spanish
* HITL control words: bilingual (approve/aprobar, exit/salir)

Use informal (tuteo) LATAM Spanish, tu not usted, puedes not podes, etc. The content is technical so if a word is best kept in English, then do so.

The /examples/spanish/README.md corresponds to the root README.md and should be kept in sync with it, but translated to Spanish.
