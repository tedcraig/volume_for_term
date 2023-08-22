# volume_for_term

Sets system volume to specified percentage on MacOs.

## Usage
volume [0-100]


#### Example 1
command:
```
volume 75
```
output:
```
┌──────────────────────────────────────────────────┐
│█████████████████████████████████████             │
└──────────────────────────────────────────────────┘
  volume set to 75%
```

#### Example 2
command:
```
volume 0
```
output:
```
┌──────────────────────────────────────────────────┐
│                                                  │
└──────────────────────────────────────────────────┘
  volume muted
```
## Dev Notes
Just a fun experiment with osascript (on macos) and a smidge of terminal UI in bash.

Basically this is a toy for learning purposes.  Not much actual utility -- or, at least, volume can be adjusted more quickly/directly by using dedicated hotkeys on keyboad.

developed in GNU bash, version 3.2.57(1)-release (x86_64-apple-darwin22)