# awesome-code-change
> A curated list of automated code change tools and projects. Search and replace, mass refactoring, codemods, and more

## Write code to change code

### Generic

- [comby](https://comby.dev/) -  a tool for searching and changing code structure. It's aware of syntax elements such as code blocks, strings and comments.
- [facebookarchive/codemod](https://github.com/facebookarchive/codemod) (archived) - a tool/library to assist you with large-scale codebase refactors that can be partially automated but still require human oversight and occasional intervention. Regex syntax.
_The are many language or framework-specific tools based off codemod, see [rajasegar/awesome-codemods](https://github.com/rajasegar/awesome-codemods)._
- [facebookincubator/fastmod](https://github.com/facebookincubator/fastmod) a fast partial replacement for codemod, focused on the interactive mode.
- [yelp/undebt](https://github.com/Yelp/undebt) (archived) - a tool that lets you define complex find-and-replace rules using standard, straightforward Python that can be applied quickly to an entire code base with a simple command.

### golang

- [astutil](https://sourcegraph.com/github.com/golang/tools/-/docs/golang.org/x/tools/go/ast/astutil) - common utilities to work with golang's AST
- [uber-go/gopatch](https://github.com/uber-go/gopatch#gopatch) - a tool to match and transform Go code. It is meant to aid in refactoring and restyling.
- [rf](https://github.com/rsc/rf) - `experimental` refactoring tool for go

### Java
- [openrewrite/rewrite](https://github.com/openrewrite/rewrite) - Semantic code search and transformation for Java.

### js

- [facebook/jscodeshift](https://github.com/facebook/jscodeshift) - a JavaScript codemod toolkit.

### python

- [google/pasta](https://github.com/google/pasta) - a library to refactor python code through AST manipulation. 
- [facebookincubator/Bowler](https://github.com/facebookincubator/bowler) - AST-level refactoring for python, guarantees that the resulting code compiles and runs.
- [python-rope/rope](https://github.com/python-rope/rope) - a python refactoring library
- [Instagram/LibCST](https://github.com/Instagram/LibCST) - a concrete syntax-tree parser for python

### rust

- [google/rerast](https://github.com/google/rerast) - a search/replace tool for Rust code using rules.

### Scala

- [scalacenter/scalafix](https://github.com/scalacenter/scalafix) - a refactoring and linting tool for Scala


### IDEs

- [IntelliJ](https://www.jetbrains.com/help/idea/refactoring-source-code.html) - has a lot of helpful refactoring functionalities
- [Eclipse](https://www.vogella.com/tutorials/EclipseJDT/article.html) - the Eclipse JDT provides AST manipulation tools


## Apply changes across many repositories

- [Sourcegraph Batch Changes](https://docs.sourcegraph.com/batch_changes) - apply and track code changes across many repositories and code hosts
- [gruntwork-io/git-xargs](https://github.com/gruntwork-io/git-xargs) - a command-line tool (CLI) for making updates across multiple Github repositories with a single command
- [Skyscanner/turbolift](https://github.com/Skyscanner/turbolift) - a simple tool to help apply changes across many GitHub repositories simultaneously
- [gabor-boros/hammurabi](https://github.com/gabor-boros/hammurabi) - an extensible CLI tool responsible for enforcing user-defined rules on code
