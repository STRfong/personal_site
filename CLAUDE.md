# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Single-file LaTeX resume based on the [sb2nov/resume](https://github.com/sb2nov/resume) template. The entire resume lives in `resume.tex`.

## Build

Compile the resume to PDF:
```bash
pdflatex resume.tex
```

## Structure

- `resume.tex` — Full resume source using custom commands (`\resumeSubheading`, `\resumeItem`, `\resumeSubItem`) for consistent formatting
- Sections: Heading, Education, Working Experience, Awards and Projects, Skill Summary
- Some sections (Extracurricular Activities) are commented out

## Conventions

- Language: Resume content is in English
- Paper size: US Letter, 11pt
- Custom commands are defined at the top of the file — use them for any new entries to maintain consistency
