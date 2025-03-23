## Greetings! 👋

Here are some open-source tools I created to make software development simpler,
more ergonomic, and more automated, while working as a contributor or leader in
the software industry. I hope you find some of them useful! 🙏

- [Git Town](https://github.com/git-town/git-town) synchronizes and manages Git
  branches, which reduces merge conflicts.
- [Text-Runner](https://github.com/kevgo/text-runner) is a test framework for
  arbitrary content written in human languages, e.g. Markdown files. It can be
  used to verify end-user facing documentation of your software product for
  technical correctness.
- [Contest](https://github.com/contest-framework) reduces the effort to run unit
  tests to zero keystrokes during test-driven development, giving instantaneous
  feedback from your test suite each time you save files in your editor or IDE.
  Currently supports [VSCode](https://github.com/contest-framework/vscode) and
  [Vim](https://github.com/contest-framework/vim).
- [Run-that-app](https://github.com/kevgo/run-that-app) executes many small
  development tools - like linters - that are often difficult to install.
- [Multi-repo-tool](https://github.com/kevgo/multi-repo-tool) allows you to run
  development tasks (cloning, compiling, linting, testing, etc) or even a custom
  interactive shell on many repositories in one swoop.
- [Atalanta](https://github.com/kevgo/atalanta) helps work with a large variety
  of code bases by listing and running development tasks defined in various
  places like `package.json`, `Makefile`, `Rakefile`, etc.
- [Tikibase](https://github.com/kevgo/tikibase) is a database-free knowledge
  base, built with extreme longetivity in mind.
- [has](https://github.com/kevgo/has) allows querying a large variety of
  properties from codebases and Git repositories, like whether files, branches,
  commits, Make targets, or Node.js dependencies exist.
- [VSCode Markdown IDE](https://github.com/kevgo/vscode-markdown-ide) provides
  IDE-grade editing of Markdown files in VSCode.

I also open-sourced a number of language-specific libraries. Here is an
overview:

### Node.js

- [observable-process](https://github.com/kevgo/observable-process) spawns a
  custom command in a subshell and allows observing the running process: wait
  until it has printed something to STDOUT or STDERR
- [end-child-processes](https://github.com/kevgo/end-child-processes): ends all
  subprocesses spawned by the current process
- [jsonc-reader-ts](https://github.com/kevgo/jsonc-reader-ts) reads JSONC files
- [probot-kit](https://github.com/kevgo/probot-kit) provides tools to build
  GitHub bots.
- [assert-no-diff](https://github.com/kevgo/assert-no-diff) verifies equality of
  various JavaScript variables with error messages that highlight differences in
  ergonomic colors.
- [node-text-stream-search](https://github.com/kevgo/node-text-stream-search)
  searches for strings or regular expressions in Node.js streams.

### Ruby

- [ActiveCucumber](https://github.com/kevgo/active_cucumber) creates
  [ActiveRecord](https://guides.rubyonrails.org/v8.0/active_record_basics.html)
  objects from
  [Cucumber tables](https://cucumber.io/docs/gherkin/reference/#data-tables)
  using [FactoryBot](https://github.com/thoughtbot/factory_bot) factories.
- [mortadella-ruby](https://github.com/kevgo/mortadella-ruby) allows building
  data tables that can be compared to Cucumber tables.
- [Kappamaki](https://github.com/kevgo/kappamaki) helps write Cucumber steps
  that define data using natural language.

### Vim

- [jumbo](https://github.com/kevgo/jumbo) is a Vim plugin that jumps between
  code blocks separated by two empty lines.
