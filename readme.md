Since I spent more than 1h finding a proper configuration for the Sonoff Dual R1 (first version, which uses UART to control the relays and not GPIO), here the link to a working configuration:

https://github.com/esphome/issues/issues/44#issuecomment-463610263

Make sure to disable logging, as it uses the same UART pins.

Hopefully this will save other people time.
