# KBD Keymap: Dvorak with Capslock as Control

This keymap will let you use capslock as an additional control key by
overriding `dvorak.map`.


## Requirements

Requires `dvorak.map` or `dvorak.map.gz` to be present under
`/usr/share/kbd/keymaps/i386/dvorak`, or equivalent directory.


## Installation

```sh
cp dvorak-caps-as-ctrl.map /usr/share/kbd/keymaps/i386/dvorak/dvorak-caps-as-ctrl.map
gzip /usr/share/kbd/keymaps/i386/dvorak/dvorak-caps-as-ctrl.map
```

## Usage

```sh
loadkeys dvorak-caps-as-ctrl
```
