# 08 - Automatic Count Up and Down

## Description

Control a single 7-segment LED using an ATmega16 microcontroller.

* The initial displayed number is `0`.
* The number automatically increases from `0` to `9`.
* The display changes every `1 second`.
* After reaching `9`, the number automatically decreases from `9` to `0`.
* The process repeats continuously.

## Hardware

* ATmega16
* 1 × 7-segment LED
* Proteus
* CodeVisionAVR

## Operation

```text
0 → 1 → 2 → 3 → 4 → 5 → 6 → 7 → 8 → 9
                                          ↓
9 → 8 → 7 → 6 → 5 → 4 → 3 → 2 → 1 → 0
                                      ↓
                                  Repeat
```

## Files

* `CodeVision/main.c` — Source code
* `Proteus/08_Auto_Count_Up_Down.pdsprj` — Proteus simulation project
