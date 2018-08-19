# smBut
ideas from https://github.com/nw-wind/SmartButton/
It is a complete Arduino library for buttons having state pulled up to VCC(INPUT_PULLUP) or with high Z input (attach pullup resistor to negative).
You can redefine timings also.
// Debounce time where the button has been pressed but is not Click event.
#define SmartButton_debounce 10
// The hold time after pressing the button we have Hold event.
#define SmartButton_hold 1000
// The long hold time for LongHold event.
#define SmartButton_long 5000
// The idle time after that the key is pressed too long time and become have no value as an error.
#define SmartButton_idle 10000
