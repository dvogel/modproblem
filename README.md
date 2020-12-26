```
Compiling modtest v0.1.0 (/platterdisks/misc/devel/modproblem)
error[E0432]: unresolved import `self::widgets`
 --> src/lib.rs:2:19
  |
2 |     pub use self::widgets::Widget;
  |                   ^^^^^^^ could not find `widgets` in `self`

error: aborting due to previous error

For more information about this error, try `rustc --explain E0432`.
error: could not compile `modtest`.

To learn more, run the command again with --verbose.
```
