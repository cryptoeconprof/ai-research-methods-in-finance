# AI Research Methods in Finance

An advanced undergraduate finance course taught by Professor Fahad Saleh at the
University of Florida in Spring 2027 as a half-semester course. The course trains
students to conduct empirical finance research using artificial intelligence and
aims to encourage students to pursue research.

This file provides course context and student setup guidance for the AI teaching
assistant. Students interact with the TA through their chosen interface. The
repository supplies the syllabus, released materials, and the TA's behavioral
instructions in [AGENTS.md](AGENTS.md).

## Syllabus and materials

- [Syllabus (PDF)](syllabus/syllabus.pdf)
- [Syllabus source (LaTeX)](syllabus/syllabus.tex)

Readings, instructional materials, and assignments will be added as they are released.

## Suggested setup: ChatGPT desktop app

Students may engage with the repository using whichever tools they prefer. The
instructor recommends the ChatGPT desktop app and its Codex interface:

1. The student [installs the ChatGPT desktop app](https://learn.chatgpt.com/docs/app)
   and signs in with a ChatGPT account.
2. In the app, the student selects **ChatGPT**, switches to **Work**, and opens a
   local folder for the course. The student asks Work to clone
   `https://github.com/cryptoeconprof/ai-research-methods-in-finance.git` into that
   folder over HTTPS.
3. The student selects **Codex** and opens the cloned `ai-research-methods-in-finance`
   folder as the course project. That folder must be the project's primary folder
   for Codex to discover the course instructions automatically. The
   [local-project guide](https://learn.chatgpt.com/docs/projects#use-local-projects-for-folders-and-codebases)
   describes folder selection.
4. The student starts a new conversation. The repository instructions establish
   Codex's teaching-assistant role.

The app's current documentation calls the mode in step 2 **Work**. See the
[mode guide](https://learn.chatgpt.com/docs/use-chatgpt#compare-work-mode-and-codex-on-desktop)
for how to switch between Work and Codex.

No GitHub account, login, or fork is required to download this public repository or
pull its updates. The student's ChatGPT account is used for the app and AI assistance.

## Scope of TA assistance

The TA can help with course logistics, course materials, assignments, coding, writing,
literature surveys, and other research tasks. Full AI assistance is permitted,
including completing assignments when a student asks. Students remain responsible
for everything they submit, including correctness, sources, attribution, and compliance with
assignment requirements. Ethical obligations, including honesty and confidentiality,
still apply. The instructor determines course requirements and grading.

The TA reads course files when they are relevant to the student's question. It does
not begin repository maintenance unless explicitly asked. Students have read-only
access to the instructor's GitHub repository. Their work takes place in local copies
or separate workspaces and does not alter the official course repository.

This repository requires no setup script or API key of its own. Students use their
own accounts for AI assistance. The [official quickstart](https://learn.chatgpt.com/docs/quickstart)
covers app setup.
Codex's [project-instruction documentation](https://learn.chatgpt.com/docs/agent-configuration/agents-md)
explains how it loads the TA instructions.

## Download and update using Git

The command for an initial download is:

```bash
git clone https://github.com/cryptoeconprof/ai-research-methods-in-finance.git
```

Students can ask the TA to download updates while preserving their work. The command
for updating an existing local copy, run from inside its repository folder, is:

```bash
git pull --ff-only
```

Student work is kept separate from the published course files to avoid conflicts
with course updates. If an update conflicts with local changes, the TA helps
preserve the student's work and resolve the conflict.

## Private material

The repository and its GitHub issues are public. Student records, grades,
accommodation information, credentials, and confidential research data belong
outside it. Synthetic or anonymized examples can support technical help without
exposing sensitive information. Personal student work, instructor-only material,
and unreleased assignments are maintained separately from the public repository.
