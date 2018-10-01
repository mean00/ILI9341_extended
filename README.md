This add "truetype"-ish font support for the ILI9341 driver found in stm32duino (Roger CLarck version)
It is using block mode to quickly draw fonts and has "auto clear" support, i.e. no need to clear first then draw on top

It is an overlay on top of the ILI9341_STM and adds a few methods to print stuff
