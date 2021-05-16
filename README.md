# Rust Tutorials

## CONTENTS

* [ENVIRONMENT](#environment)
    * macOS 10.15.7
    * rustc 1.52.1 (9bc8c42bb 2021-05-09)
    * cargo 1.52.0 (69767412a 2021-04-21)
    * VS Code 1.56 with [Rust](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust) extension
* [RUN](#run)
    * [In VS Code](#in-vs-code)
* [REFERENCES](#references)

## RUN

### In VS Code

1. To run individual tasks (ex. `hello_cargo check`, `hello_cargo build`, etc.)
    * **Tasks: Run Task** (`CMD` + `SHIFT` + `B`) then select task from the list
    * All the tasks are defined in [tasks.json](./.vscode/tasks.json)
1. To run a specific app (ex. `hello_cargo run`)
    * **Run** > **Start debugging** (`F5`)
    * The run configuration is defined in [launch.json](./.vscode/launch.json)
    * The run configuration auto-runs corresponding `build` task

## REFERENCES

* [The Rust Programming Language](https://doc.rust-lang.org/stable/book/)
