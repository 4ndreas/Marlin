readme.md


how to:

## M119 
limit switch check


## M122
TMC driver status


## M10/M11 
Vacuum on/off


## PA14 and PA13 SWD pins
´´´
PA14 DIR pin for Driver 7 
#define E3_DIR_PIN                          PA6 // PA14  // SWD pin ...
´´´

PA13 staus led pin 
´´´
// #define LED_PIN                             PA13
#define LED_PIN                             -1
´´´

## G92 Set Position
G92 X10 E90

## G90 ; Set all axes to absolute