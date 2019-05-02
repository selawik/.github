# Contributing to The Selawik Project
Thanks for taking the time to contribute to the Selawik project! To make sure that your efforts are used effectively, please take the time to read over these guidelines.

## Code style 
For C#, we mostly use Visual Studio defaults. You can see the C# style guidelines [here](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/inside-a-program/coding-conventions). However, we ask that you do a few things differently:

- Use `var` where possible.
- Always use the CLR type names (`Int32`) rather than the C# keywords (`int`).
- Do not specify member visibility where it is redundant (e.g. `class Sequence` over `internal class Sequence`).

We will provide an `.editorconfig` file wherever possible, enabling auto-formatting conforming to the above guidelines.

Please comment on all your code, including functions, using XML documentation. Fill out as much information about the member or type as you can.

## Pull Requests
- Always contribute code using pull requests; try not to make direct commits, so that code can be reviewed by others.
- Please create an issue before making a pull request that adds new functionality. APIs etc. need to be reviewed, approved, and spec'd.
- Give meaningful names to your commits that reference/[close](https://help.github.com/en/articles/closing-issues-using-keywords) relevant issues.
- When merging pull requests or resolving merge conflicts, please prefer squash/rebase instead of a merge commit.

Please keep in mind our [code of conduct](https://github.com/selawik/.github/blob/master/CODE_OF_CONDUCT.md) when discussing with others on GitHub.
