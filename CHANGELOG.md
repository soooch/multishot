# 0.3.0 (2022-12-29)

- Implement `Send`, `UnwindSafe` and `RefUnwindSafe` for `Sender`.
- Simplify implementation and improve performance.
- Enable multi-threading in MIRI tests and add tests.

# 0.2.0 (2022-02-14)

- Fix soundness issue in `Receiver::sender` which should have taken `&mut self`
  rather than `&self`.
- Update copyright date in MIT license.

# 0.1.0 (2022-02-10)

Initial release
