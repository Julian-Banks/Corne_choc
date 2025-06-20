# Alrighty where to start?

The baseline decisions: 
- **Type**: corne
- **Switch**: Chocolate
- **Version**: V2 or V4 ? I can't find much on the differences?  
- **Leds**: Yes 
- **Wireless**: Maybe but I think yes 
- **OLED**: Yes 
- **Hotswap sockets**: Maybe Idk 

Official corne choc docs: [github docs](https://github.com/foostan/crkbd/tree/main/docs/corne-chocolate)

## Type & Switch 
I am pretty happy with Corne. I think the 6 Col format seems safer than the 5 col? 

## Version
I can't find much documentation about the difference between these two versions... 

### V2
According to GPT: 
- Original Choc only compatible  

### V4
According to GPT:
- MX and Choc compatible

## LEDS

I don't see why not, always cool to make stuff light up. 

Only concern is power draw if going wireless. 


## Wireless vs Wired 

I really like the idea of wireless. 

### Wired
use a Pro Micro microcontroller and QMK is used for the firmware.

Pros:
- Seems to be more standard?
  
Cons:
- ? 

### Wireless
Use a Nice!Nano (v2 has built in charging) and ZMK is used for firmware. 

Microcontroller options:
- [Supermini nRF52840](https://www.reddit.com/r/ErgoMechKeyboards/comments/16q5b2c/supermini_nrf52840_a_6_nicenano_20_compatible_mcu/)
- [Alternatives (man I love nerd community)](https://github.com/joric/nrfmicro/wiki/Alternatives) 

**Pros:**
- Fucken wireless!
  
**Cons**: 
- less out there with info on it? 
- LEDs may be a big power drain and not really be worth it.

## OLED

Yes just cause it's pretty freaking cool. 

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






