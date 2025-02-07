# Kotlin-Formatter for VSCode

This is a Formatter to have for Kotlin (`.kt`) and KotlinScript (`.kts`)

## Requirements

Make sure you have [ktlint](https://github.com/pinterest/ktlint) installed before installing this extension

This extension currently only supports `Linux` and `macOS`, I will add Windows support in a future release

## Using

You can either use the `kotlin-formatter.formatKotlin` command or set `cstef.kotlin-formatter` as your default formatter in VScode settings

## Format on save

Set `cstef.kotlin-formatter` as your formatter for `kotlin` and/or `kotlinscript` in VScode's `settings.json`:

```json
    {
        ...
        "[kotlin]": {
            "editor.defaultFormatter": "cstef.kotlin-formatter"
        },
        "[kotlinscript]": {
            "editor.defaultFormatter": "cstef.kotlin-formatter"
        }
        ...
    }
```
