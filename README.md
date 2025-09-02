# atuin-fish-export

This tool exports the history from the Atuin database and imports it to the fish
shell history database. This is useful because it allows fish's autosuggestions
to be correct and helpful on a new install, when Atuin has your history, but
fish doesn't.

I did nothing to the actual code, I just set up this repo for it.

## Original source

atuinsh/atuin#1073 (comment)

## Original author

https://github.com/zxh326

## Installation

### From prebuilt binary

Download the latest release from the [releases page](https://github.com/ataraxia937/atuin-fish-export/releases).

### From source

```fish
go install github.com/ataraxia937/atuin-fish-export@latest
```

## Usage

```fish
atuin-fish-export
```
