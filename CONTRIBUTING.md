# Contributing to Open Kannada

Thank you for helping. These rules apply to every Open Kannada repository. A repository's own CONTRIBUTING.md or AGENTS.md adds its commands and checks.

## Report a bug

Open an issue in the repository the bug belongs to. Include:

- what you did, such as the command, the file or the word;
- what you expected, and what happened instead;
- a short sample, if the bug is about a document, a font or a word. A sample of a few lines is enough, and every fixed case becomes a test.

For a security problem, do not open a public issue. Follow the repository's SECURITY.md instead.

## Sign off every commit (DCO)

Open Kannada uses the [Developer Certificate of Origin](https://developercertificate.org/) (DCO), not a contributor license agreement. Every commit needs a `Signed-off-by` line with your name and email. It certifies that you wrote the change, or otherwise have the right to submit it under the repository's licenses.

`git commit -s` adds the line from your Git settings:

```text
Signed-off-by: Your Name <you@example.com>
```

If you forgot, `git commit --amend -s` signs off the last commit, and `git rebase --signoff origin/main` signs off every commit on your branch.

You keep the copyright in your work. It is licensed under the licenses of the files it changes, as each README's License section describes, and you join "The Open Kannada Authors".

## Licenses

- Code: MIT OR Apache-2.0.
- Fonts we make: SIL Open Font License 1.1, with no Reserved Font Name. A forked font keeps its upstream license.
- Data and docs we write: CC BY 4.0.
- A file copied from a share-alike source keeps that source's license, such as CC BY-SA 4.0 for words from Wikipedia. It is never mixed into a file under another share-alike license.

Each repository's README, NOTICE and REUSE.toml say which license applies to which file. Using the names and logos is covered in [TRADEMARKS.md](TRADEMARKS.md).
