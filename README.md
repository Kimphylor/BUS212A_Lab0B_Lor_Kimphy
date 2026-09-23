# BUS 212A Lab 0B

Name: Kimphy Lor
Date: September 22, 2026

## Purpose

This repository demonstrates a reproducible workflow for running a Python
script, recording its output, documenting the repository structure, and
using GitHub version history.

## Structure

- `README.md` documents the purpose, structure, run instructions, output
  verification, privacy information, and version note.
- `.gitignore` identifies files and patterns that should not be committed.
- `src/` contains the Python source code.
- `outputs/` contains the verified output produced by the Python script.

## How To Run

From the repository root, run:

```bash
python src/hello_analytics.py > outputs/lab0b_output.txt
```

## Verified Output

The script creates:

`outputs/lab0b_output.txt`

I opened the output file after running the script and verified that it
contains the Lab 0B label, course, student name, date, and question printed
by the Python script.

## Privacy And .gitignore

`.gitignore` tells Git which files or file patterns should not be included
in commits.

A `.env` file may contain sensitive information such as passwords, API keys,
or access tokens, so it should not be committed publicly.

Adding a filename to `.gitignore` does not remove a file that was already
committed. It helps prevent matching untracked files from being added in
future commits, but a file that is already tracked must be handled
separately.

Two types of information that should never be committed publicly are
passwords and API or access tokens.

## Version Note

GitHub Desktop will be used as the GitHub workflow.

Commit message:

`Add reproducible Lab 0B workflow`

The commit records the required Lab 0B files and the state of the
repository at the time of the commit.

## AI Use Note

AI use note: I used ChatGPT to help me understand the Lab 0B instructions,
organize the repository structure, explain Git and GitHub steps, and draft
documentation. I verified the repository structure, run command, Python
script, and recorded output myself.