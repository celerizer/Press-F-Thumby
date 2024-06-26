# Press F Thumby

https://github.com/celerizer/Press-F-Thumby/assets/33245078/f81acfcb-8bff-4878-9d88-d981f260120f

## Controls

| Thumby         | Channel F                 |
|----------------|---------------------------|
| Left           | Left                      |
| Right          | Right                     |
| Up             | Up                        |
| Down           | Down                      |
| A + Left       | Rotate counter-clockwise  |
| A + Right      | Rotate clockwise          |
| A + Up         | Pull up                   |
| A + Down       | Plunge down               |
| B + Left       | 1 / TIME                  |
| B + Right      | 2 / MODE                  |
| B + Down       | 3 / HOLD                  |
| B + Up         | 4 / START                 |


## Building

- Set up a [Thumby environment](https://thumby.us/CCPP/Environment-Setup/) in Arduino IDE.
- Clone the project and the core emulation submodule:
```sh
git clone https://github.com/celerizer/Press-F-Thumby.git --recurse-submodules
```
- Open `Press-F-Thumby.ino` in Arduino IDE and flash the system.

WARNING: Doing so will also overwrite the Thumby system firmware, erasing any games or save files that have not been backed up.
