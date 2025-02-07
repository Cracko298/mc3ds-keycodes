# mc3ds-keycodes
- Keycodes, and Address' for making macro's for minecraft 3ds.
- View full keypad/ctrpf AR docs [Here](https://gist.githubusercontent.com/Nanquitas/d6c920a59c757cf7917c2bffa76de860/raw/b842b0f3f4c9aeb1f33e61e2ad5c5feb5a5eb6cd/ActionReplayCodeTypes.txt).
- They're also fully defined in the decomp if you'd like to see [Here](https://github.com/Cracko298/mc3ds-decomp/blob/main/source/include/keycodes.hpp).

## Address':
```
===============
KEYPAD ADDRESS'
===============
0x00B329E8
0x00B32948
0x00B32A00
0x00B32A18
0x00B32A30
0x00B32A48
0x00B32A60
0x00B32A78
0x00B32A90
0x00B32AB0
```

## Keypad Hex Codes:
```
===================
SPECIAL KEYPAD CODE
===================
0x1         A
0x2         B
0x4         Select
0x8         Start
0x10        Right
0x20        Left
0x40        Up
0x80        Down
0x100       R
0x200       L
0x400       X
0x800       Y
0x4000      ZL (N3DS Only)
0x8000      ZR (N3DS Only)

===================
UNKNOWN KEYPAD CODE
===================
0x100000    Touchpad (any position)
0x1000000   CStick-Right (N3DS Only)
0x2000000   CStick-Left (N3DS Only)
0x4000000   CStick-Up (N3DS Only)
0x8000000   CStick-Down (N3DS Only)
0x10000000  CPad-Right
0x20000000  CPad-Left
0x40000000  CPad-Up
0x80000000  CPad-Down
```

## Example:
```
[Touch Anywhere to Build]
D3000000 00000000
11E81000 00000000
DE000001 000100F0
21E81001 00000001
D0000000 00000000
DE000000 00010136
21E81000 00000001
D0000000 00000000
91E81000 00000101
10B329E8 00000200
10B32948 00000200
10B32A00 00000200
10B32A18 00000200
10B32A30 00000200
10B32A48 00000200
10B32A60 00000200
10B32A78 00000200
10B32A90 00000200
10B32AB0 00000200
D0000000 00000000
{As title Suggests, touch anywhere on Bottom screen to build fast.}
```
