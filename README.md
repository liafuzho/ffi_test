# ffi_test

## Build
RUSTFLAGS='-L /lib/pcre2/path' cargo build

## Run
LD_LIBRARY_PATH="/lib/pcre2/path" target/debug/xp
