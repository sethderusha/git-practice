# Git Practice

A small repository for practicing centralized and forking Git/GitHub workflows.

## An article worth reading

I found [Why Google Stores Billions of Lines of Code in a Single Repository](https://cacm.acm.org/research/why-google-stores-billions-of-lines-of-code-in-a-single-repository/) interesting. It describes how Google keeps most of its source code in one giant repository (a *monorepo*) instead of splitting it across many smaller ones.

What stood out to me is that version control is not just a backup tool. At Google's scale, the repository becomes part of how the company collaborates: anyone can find and reuse code, large refactorings can land in a single commit, and tooling can see the whole codebase at once. The article also makes the tradeoffs clear. A monorepo only works if you invest heavily in custom tooling, and most teams should not copy Google's setup just because it works there.