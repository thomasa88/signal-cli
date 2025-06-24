# signal-cli library modification

This is quick modification of the Rust RPC client in [signal-cli](https://github.com/AsamK/signal-cli), to turn it into a library crate.

Minimal modifications will hopefully allow the source to track upstream modifications.

See the code in `client` for how to call `connect_unix()` and use the client functions.


## License

This project uses [signal-cli](https://github.com/AsamK/signal-cli) by Sebastian Scheibner and [libsignal-service-java](https://github.com/WhisperSystems/libsignal-service-java) from Open Whisper Systems.

Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html
