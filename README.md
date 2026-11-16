# AI Coding Skills: Lazy & Rigorous Engineering

## Getting started

```bash
npx skills add https://github.com/niyazgim/bash-mode
```

## Feeding Context with Repomix (if you're not using AI agents)

To make the AI truly effective, you need to give it **codebase context**. That’s where [Repomix](https://github.com/yamadashy/repomix) comes in.

**Repomix** packs your entire repository into a single XML file (`repomix-output.xml`). The AI can read that file to understand the whole codebase, then apply the skills to suggest changes.

### How to Use Repomix

1. Install Repomix:

```bash
npm install -g repomix
```

Or use the web version at [repomix.com](https://repomix.com).

2. Generate the packed file:

```bash
repomix
```

This creates `repomix-output.xml` in your current directory.

3. Provide it to the AI

## Quick Tips

- For **bash‑mode** tasks (generating shell scripts), the skills include a special `bash mode` – just mention it in your request.
- If the AI asks too many clarifying questions, that’s a *good* sign – it’s following the “think before coding” rule.

## Use this helpful tools too!

- [Repomix GitHub](https://github.com/yamadashy/repomix)  
- [Repomix Web](https://repomix.com)

- [Ponytail GitHub](https://github.com/DietrichGebert/ponytail) 
- [Andrej Karpathy Skills GitHub](https://github.com/multica-ai/andrej-karpathy-skills)

## Credits

Niyaz Gimadiev <niyaztutor@gmail.com> with ❤️