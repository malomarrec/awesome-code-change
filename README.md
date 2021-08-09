# awesome-code-change
> A curated list of automated code change tools and projects. Search and replace, mass refactoring, codemods, and more

## Automated code change

### Generic

- [comby](https://comby.dev/) - Comby is a tool for searching and changing code structure. It's aware of syntax elements such as code blocks, strings and comments.
- [google/rerast](https://github.com/google/rerast) - A search/replace tool for Rust code using rules.




### Refactoring tools

- (archived) [facebookarchive/codemod](https://github.com/facebookarchive/codemod) - Codemod is a tool/library to assist you with large-scale codebase refactors that can be partially automated but still require human oversight and occasional intervention. Regex syntax.

_The are many language or framework-specific tools based off codemod, see [rajasegar/awesome-codemods](https://github.com/rajasegar/awesome-codemods)._

- [facebook/jscodeshift](https://github.com/facebook/jscodeshift) - A JavaScript codemod toolkit.
- [facebookincubator/fastmod](https://github.com/facebookincubator/fastmod) fastmod is a fast partial replacement for codemod, focused on the interactive mode.
- (archived) [yelp/undebt](https://github.com/Yelp/undebt) - Undebt is a tool that lets you define complex find-and-replace rules using standard, straightforward Python that can be applied quickly to an entire code base with a simple command.
- [google/pasta](https://github.com/google/pasta) - A library to refactor python code through AST manipulation. 
- [facebookincubator/Bowler](https://github.com/facebookincubator/bowler - AST-level refactoring for python, guarantees that the resulting code compiles and runs.
- [python-rope/rope](https://github.com/python-rope/rope) is a python refactoring library



### IDEs

- [IntelliJ](https://www.jetbrains.com/help/idea/refactoring-source-code.html) - has a lot of helpful refactoring functionalities



## Apply changes across many repositories

- [Sourcegraph Batch Changes](https://docs.sourcegraph.com/batch_changes) - Apply and track code changes across many repositories and code hosts
- [Skyscanner/turbolift](https://github.com/Skyscanner/turbolift) - A simple tool to help apply changes across many GitHub repositories simultaneously
- [gruntwork-io/git-xargs](https://github.com/gruntwork-io/git-xargs) - a command-line tool (CLI) for making updates across multiple Github repositories with a single command
