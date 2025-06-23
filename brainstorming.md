# Alrighty where to start?

The baseline decisions: 
- **Type**: Corne
- **Switch**: Chocolate
- **PCB**: [Choc spaced Wireless Corne](https://github.com/davidphilipbarr/Choc-Spaced-Corne/tree/main/chocorne-switch)  
- **Leds**: Probably not because we are going wireless
- **Wireless**: Yes 
- **OLED**: Yes 
- **Hotswap sockets**: Maybe Idk
- **Switchs**:
- **Keycaps**:

## Guides and docs
Official corne choc docs: [github docs](https://github.com/foostan/crkbd/tree/main/docs/corne-chocolate)
Build Guide inspiration:
[Choc Spaced Corne Keyboard - Wireless](https://github.com/rafaeldelboni/buildlogs/blob/main/crkbd-choc-spaced-switch.md)


## Dumping info about parts
### PCB
- [This board](https://github.com/davidphilipbarr/Choc-Spaced-Corne/tree/main/chocorne-switch) by davidphilipbarr looks good. it is a wireless choc spaced corne so pretty much fits the bill. I've found it referenced in a couple threads and it is used in the build guide I linked at the top so I'm pretty sure it will work. the only thing I don't like is the battery is soldered on. I like having a clip. but thats a small edit I'm sure I could make :). 
- There are the foostan/crkbd original PCB's but they aren't wireless. [foostan chocs](https://github.com/foostan/crkbd/tree/main/docs/corne-chocolate)

### MicroController

Use a Nice!Nano (v2 has built in charging) and ZMK is used for firmware. 

**Nice!Nano** 
- standard option, documented and will work
- spenny ($24 each plus shipping)

**SuperMini NRF52840**
- Cheap! $3-5 each 
- Well documented as far as cheap chinese alternatives go!
- [Supermini nRF52840](https://www.reddit.com/r/ErgoMechKeyboards/comments/16q5b2c/supermini_nrf52840_a_6_nicenano_20_compatible_mcu/)
- [Alternatives (man I love nerd community)](https://github.com/joric/nrfmicro/wiki/Alternatives) 
  
### OLED
Yes just cause it's pretty freaking cool. 

### Switches 

### Keycaps

# Rough BOM 

### Electrical Parts

|Part| Specific Part | Link | QTY | Cost | Notes |
| --- | ---          | ---  | --- | --- | --- | 
|MicroController|    |     |     |     |     |
|MicroController headers|     |     |     |     |     |
|PCB|     |     |     |     |     |
|Switches|     |     |     |     |     |
|Key Caps|     |     |     |     |     |
|Diodes|    |     |     |     |     |
|OLED display|    |     |     |     |     |
|OLED headers|    |     |     |     |     |
|Under key LEDS|    |     |     |     |     |
|Under glow LEDS|    |     |     |     |     |
|Reset Buttons|    |     |     |     |     |

#### Wireless Specific
|Part| Specific Part | Link | QTY | Cost | Notes |
| --- | --- | --- | --- | --- | --- |
|Battery|    |     |     |     |     |
|Power Switches|    |     |     |     |     |
|Battery Connector|    |     |     |     |     |

#### Wired Specific
|Part| Specific Part | Link | QTY | Cost | Notes |
| --- | --- | --- | --- | --- | --- |
|USB-C cable|    |     |     |     |     |
|TRRS Jack|    |     |     |     |     |
|TRRS cable|    |     |     |     |     |


### Mechanical Parts
Defined based off what type of PCB I order? 

|Part| Specific Part | Link | QTY | Cost | Notes |
| --- | --- | --- | --- | --- | --- | 
| Case |    |     |     |     |     |
| top Plate|    |     |     |     |     |
|Switch Plate|    |     |     |     |     |
|Standoffs + Screws|    |     |     |     |     |
|Threaded Inserts|    |     |     |     |     |






