# jd4rider Homebrew tap

Nova is a Rust-native programming language with an LLVM backend and a desktop IDE.

## Studio + language together

```sh
brew install --cask jd4rider/tap/nova-studio
```

The cask depends on `jd4rider/tap/nova`, so it installs the language and Studio together.

## Language only

```sh
brew install jd4rider/tap/nova
nova --version
```

Artifacts are unsigned macOS arm64 previews. See <https://github.com/jd4rider/nova/blob/main/INSTALL.md>.
