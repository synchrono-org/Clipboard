# 📋 Clipboard 
Cut, copy, and paste absolutely anything anywhere you want, all from the comfort of your terminal! This is the ultimate clipboard system for the command line.

**Clipboard...**
- **is really tiny**. We're serious about code size; Clipboard rings in at mere kilobytes on most platforms.
- **is really simple**. We're serious about scope; Clipboard is exactly that, a clipboard.
- **is really friendly**. We're serious about UX; Clipboard is zero-config and is carefully designed to be friendly to newbies and power users alike.
- **is really global**. We're serious about localization; Clipboard currently supports English, Spanish, and Portuguese locales.
- **"just works" everywhere**. We're serious about compatibility; Clipboard works on any Windows, Linux, macOS, FreeBSD, OpenBSD, or OpenIndiana system, or anything that supports C++20, all with ZERO dependencies.
- **looks pretty**. We're serious about design; Clipboard has colorful text baked in everywhere.** 🌈 Say adiós to boring black & white!
- **saves time**. We're serious about productivity; Clipboard frees you from ugly, temporary directories and memorizing file locations!

**You can disable colors with the NO_COLOR environment variable.

# How To Use

In all commands, you can substitute `cb` for `clipboard`.

## Copy
`clipboard copy (file) [files]`

Examples:

```
cb copy foo.txt launchcodes.doc
clipboard copy MyDirectory
cb copy bar.conf AnotherDirectory baz.txt
```
## Cut
`clipboard cut (file) [files]`

Examples:

```
cb cut bar.txt baz.docx
clipboard cut MyDirectory
cb cut bar.conf AnotherDirectory baz.txt
```
## Paste
`clipboard paste`

## Pipe In

`(something) | clipboard [copy]`

## Pipe Out

`clipboard [paste] | (something)`

or

`clipboard [paste] > (some file)`

# Quick Installation
## Clone
```
git clone https://github.com/slackadays/Clipboard
```
## Compile

```
cmake Clipboard/src
cmake --build .
```
## Install
Platforms where you have `sudo` to install software (Linux, macOS, *BSD, OI):
```
sudo cmake --install .
```
OpenBSD:
```
doas cmake --install .
```
Windows:
```
cmake --install .
```

## Uninstall
Platforms where you have `sudo` to uninstall software (Linux, macOS, FreeBSD, OI):
```
sudo xargs rm < install_manifest.txt
```
OpenBSD:
```
doas xargs rm < install_manifest.txt
```
Windows:

This is currently WIP

## Install from the AUR

Arch-Linux users can install the [clipboard](https://aur.archlinux.org/packages/clipboard), [clipboard-bin](https://aur.archlinux.org/packages/clipboard-bin) or [clipboard-git](https://aur.archlinux.org/packages/clipboard-git) AUR package.

# Painless Documentation 

[Click here](https://github.com/Slackadays/Clipboard/wiki) to go the Clipboard Wiki.

# Fast Support

[Click here](https://discord.gg/J6asnc3pEG) to go to our Discord group.
