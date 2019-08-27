    rust-private-paths/binary$ cargo run
    Compiling binary v0.1.0 (/home/matti/devel/rust-private-paths/binary)
    error[E0599]: no method named `nonexistent_method` found for type `library::private::Type` in the current scope
    --> src/main.rs:4:7
    |
    4 |     t.nonexistent_method();
    |       ^^^^^^^^^^^^^^^^^^

    error: aborting due to previous error

    For more information about this error, try `rustc --explain E0599`.
    error: Could not compile `binary`.

    To learn more, run the command again with --verbose.
