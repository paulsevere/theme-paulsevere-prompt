<img
src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg"
align="left" width="144px" height="144px"/>

#### simple-ass-prompt
> A theme for [Oh My Fish][omf-link].

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)
[![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](http://fishshell.com)
[![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square)](https://www.github.com/oh-my-fish/oh-my-fish)

<br/>

## Install

```fish
$ omf install simple-ass-prompt
```

## Features
This is [Mathias Bynens][mths] Bash prompt ported to Fish with a few changed
icons and added functionalities. As he put it:


> Shell prompt based on the Solarized Dark theme.
> Screenshot: http://i.imgur.com/EkEtphC.png

> Heavily inspired by @necolas’s prompt: https://github.com/necolas/dotfiles

> iTerm → Profiles → Text → use 13pt Monaco with 1.1 vertical spacing.

Features:

- A dirty state of the branch is displayed by `!`
- Untracked files are displayed by `☡`
- The existence of a stash is displayed by `↩`
- A clean branch is displayed by `✓`
- The branch is ahead with `+`
- The branch is behind with `-`
- The branch has diverged from upstream `±`
- Support for Pythons virtual environments
- Support Rust active toolchain
- The last command failed is displayed with `↪` in red

## Screenshot
Git Usage
<p align="center">
<img src="http://cl.ly/1G0Z2j3A0C1Q/Screen%20Recording%202015-12-16%20at%2010.09%20pm.gif">
</p>

[VirtualFish][vf] Usage
<p align="center">
<img src="http://cl.ly/image/1Y36043M2U3M/simple_ass_prompt_virtual.png">
</p>

## Configuration
You can change the greeting message with:
```fish
set -g simple_ass_prompt_greeting MyGreeting
```

# License

[MIT][mit] © [lfiolhais][author] et [al][contributors]


[mit]:            http://opensource.org/licenses/MIT
[author]:         http://github.com/lfiolhais
[contributors]:   https://github.com/lfiolhais/simple_ass_prompt/graphs/contributors
[omf-link]:       https://www.github.com/oh-my-fish/oh-my-fish
[mths]: https://github.com/mathiasbynens/dotfiles
[license-badge]:  https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
[vf]: https://github.com/adambrenecki/virtualfish
