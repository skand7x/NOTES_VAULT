# Nebula vault

This directory is your Nebula data. Every note and task is a plain Markdown
file with a small frontmatter header, so it stays readable and recoverable
with or without Nebula installed.

    notes/   one file per note
    todos/   one file per task

Nebula keeps this directory under git. Do not rename files by hand — the `id`
field in the frontmatter is what Nebula uses to identify a record.
