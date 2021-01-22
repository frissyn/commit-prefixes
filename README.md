# Commit Prefixes

My personal style guide for writing GitHub commit messages. More specifially, the prefixes. Prefixes should be written in the following format:

```html
<prefix>: <message> (<reference>)
```

`prefix` should be either an emoji OR it's name, not both. `message` is, of course, your commit message followed by `reference`, which is your issue or pull request reference (if applicable).

✨ **This is a Work in Progress!** ✨

|No. |Emoji |Names             |Example                                      |
|:---|:----:|:-----------------|:--------------------------------------------|
|01  |✨    |`update`, `feat`  |`✨: add docstrings and type hinting`        |
|02  |🔨    |`fix`, `bug`      |`🔨: fix broken control header (#4)`         |
|️️03  |🔀    |`merge`           |`🔀: merge pull request from user/patch-1`   |
|04  |⬆️    |`bump`, `upgrade` |`⬆️: bump highlight.js from 1.1.2 to 1.2.0`  |
|05  |🔒    |`security`        |`🔒: move exposed API key to .env file`      |
|06  |🏷️    |`label`, `tag`    |`🏷️: release v0.1.1`                         |
