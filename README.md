# Lightspeed PCB

A reverse engineered Logitech G613 lightspeed PCB

![daughter board](https://user-images.githubusercontent.com/1764391/227828229-bd91c30f-06db-460b-8a7c-1ebef921f776.png)

1. Pins 0, 1, 45, 46 are negative
2. Keyboard turns on when 3 goes negative
3. Bond 4 and 5 to disable game mode

|   Key                   |   Column / Diode  |   Row  |
|-------------------------|-------------------|--------|
|   ESC                   |   37              |   30   |
|   F1                    |   36              |   31   |
|   F2                    |   36              |   30   |
|   F3                    |   35              |   31   |
|   F4                    |   35              |   30   |
|   F5                    |   34              |   31   |
|   F6                    |   34              |   30   |
|   F7                    |   33              |   31   |
|   F8                    |   33              |   30   |
|   F9                    |   32              |   31   |
|   F10                   |   32              |   30   |
|   F11                   |   19              |   30   |
|   F12                   |   18              |   30   |
|                         |                   |        |
|   TILDE                 |   37              |   28   |
|   1                     |   36              |   29   |
|   2                     |   36              |   28   |
|   3                     |   35              |   29   |
|   4                     |   35              |   28   |
|   5                     |   34              |   29   |
|   6                     |   34              |   28   |
|   7                     |   33              |   29   |
|   8                     |   33              |   28   |
|   9                     |   32              |   29   |
|   0                     |   32              |   28   |
|   - _                   |   19              |   29   |
|   = +                   |   19              |   28   |
|   BACKSPACE             |   18              |   28   |
|                         |                   |        |
|   TAB                   |   37              |   26   |
|   Q                     |   36              |   27   |
|   W                     |   36              |   26   |
|   E                     |   35              |   27   |
|   R                     |   35              |   26   |
|   T                     |   34              |   27   |
|   Y                     |   34              |   26   |
|   U                     |   33              |   27   |
|   I                     |   33              |   26   |
|   O                     |   32              |   27   |
|   P                     |   32              |   26   |
|   [ {                   |   19              |   27   |
|   ] }                   |   19              |   26   |
|   \ \|                  |   18              |   27   |
|                         |                   |        |
|   CAPS LOCK             |   37              |   24   |
|   A                     |   36              |   25   |
|   S                     |   36              |   24   |
|   D                     |   35              |   25   |
|   F                     |   35              |   24   |
|   G                     |   34              |   25   |
|   H                     |   34              |   24   |
|   J                     |   33              |   25   |
|   K                     |   33              |   24   |
|   L                     |   32              |   25   |
|   ; :                   |   32              |   24   |
|   ‘ ”                   |   19              |   25   |
|   RETURN                |   18              |   24   |
|                         |                   |        |
|   LSHIFT                |   37              |   23   |
|   Z                     |   36              |   22   |
|   X                     |   35              |   23   |
|   C                     |   35              |   22   |
|   V                     |   34              |   23   |
|   B                     |   34              |   22   |
|   N                     |   33              |   23   |
|   M                     |   33              |   22   |
|   , <                   |   32              |   23   |
|   . >                   |   32              |   22   |
|   / ?                   |   19              |   23   |
|   RSHIFT                |   18              |   22   |
|                         |                   |        |
|   LCTRL                 |   37              |   20   |
|   LWIN                  |   36              |   21   |
|   LALT                  |   36              |   20   |
|   SPACE                 |   35              |   21   |
|   RALT                  |   32              |   20   |
|   RWIN                  |   19              |   21   |
|   CONTEXT               |   19              |   20   |
|   RCTRL                 |   20              |   21   |
|                         |                   |        |
|   PRINT SCREEN / SYSRQ  |   17              |   31   |
|   SCROLL LOCK           |   17              |   30   |
|   PAUSE / BREAK         |   17              |   29   |
|                         |                   |        |
|   INS                   |   17              |   27   |
|   HOME                  |   17              |   26   |
|   PAGE UP               |   17              |   28   |
|                         |                   |        |
|   DEL                   |   18              |   26   |
|   END                   |   17              |   25   |
|   PAGEDOWN              |   17              |   24   |
|                         |                   |        |
|   UP ARROW              |   17              |   23   |
|   LEFT ARROW            |   18              |   20   |
|   DOWN ARROW            |   17              |   21   |
|   RIGHT ARROW           |   17              |   20   |
|                         |                   |        |
|   NUM LOCK              |   16              |   28   |
|   /                     |   16              |   27   |
|   *                     |   15              |   27   |
|   -                     |   15              |   26   |
|                         |                   |        |
|   7 / HOME              |   16              |   26   |
|   8 / ARROW UP          |   16              |   25   |
|   9 / PAGE UP           |   15              |   22   |
|   +                     |   15              |   24   |
|                         |                   |        |
|   4 / ARROW LEFT        |   16              |   24   |
|   5                     |   16              |   23   |
|   6 / ARROW RIGHT       |   15              |   23   |
|                         |                   |        |
|   1 / END               |   16              |   22   |
|   2 / ARROW DOWN        |   16              |   21   |
|   3 / PAGE DOWN         |   15              |   22   |
|   ENTER                 |   15              |   20   |
|                         |                   |        |
|   0 / INS               |   16              |   20   |
|   . / DEL               |   15              |   21   |
|                         |                   |        |
|   LIGHTSPEED            |   19              |   31   |
|   BLUETOOTH             |   18              |   31   |
|   MUTE                  |   16              |   31   |
|   VOLUME DOWN           |   15              |   31   |
|   VOLUME UP             |   15              |   30   |
|                         |                   |        |
|   PLAY / PAUSE          |   16              |   30   |
|   STOP                  |   16              |   29   |
|   PREVIOUS TRACK        |   15              |   28   |
|   NEXT TRACK            |   15              |   29   |
|                         |                   |        |
|   G1                    |   37              |   31   |
|   G2                    |   37              |   29   |
|   G3                    |   37              |   27   |
|   G4                    |   37              |   25   |
|   G5                    |   37              |   23   |
|   G6                    |   37              |   21   |
