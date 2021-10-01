# Kotlin-Formatter for VSCode

This is just a formatter for Kotlin (`.kt`) and KotlinScript (`.kts`)

## Requirements

Make sure you have [ktlint](https://github.com/pinterest/ktlint) installed before installing this extension

---

**IMPORTANT NOTE FOR WINDOWS USERS**

You need to have the [ktlint jar](https://github.com/pinterest/ktlint/releases) file in your project root for this to work. 

---

This extension supports `Linux`, `macOS` and `Windows`.

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
