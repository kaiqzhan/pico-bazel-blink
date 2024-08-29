A simple bazel example to build blink for Raspberry Pi Pico.

## Build
`bazel build --platforms=@pico-sdk//bazel/platform:rp2040 //:blink`

## Generate clangd compile_commands.json
`bazel run //:refresh_compile_commands`
