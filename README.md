# Change-All-Occurrences_CLI
Repository to hold the code for and CLI_App that changes all occurrences in an especified file to a determined value in Rust.

This project intends to mantain the basic code in rust, so it can be revisited if something was forgotten.
It is actually functional, all you have to do is clone the repo and cargo build && cargo run the project.

Are expect some arguments in the cargo run:

cargo run <target string(beetwen quots)> <replacement string(beetwen quots)> <INPUT_FILE> <OUTPUT_FILE>, the files can be only the name if the archive is in the root folder of the project, with is the cloned one with src, Cargo.lock, Cargo.toml...

All dependencies must be automatically downloaded by the cargo itself.
