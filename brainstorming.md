# Alrighty where to start?

The baseline decisions: 
- **Type**: Corne
- **Switch**: Choc V2 (ghost,white rain, black cloud)
- **PCB**: [Choc spaced Wireless Corne](https://github.com/davidphilipbarr/Choc-Spaced-Corne/tree/main/chocorne-switch)  
- **Leds**: Probably not because we are going wireless
- **Wireless**: Yes 
- **OLED**: Yes 
- **Hotswap sockets**:  Yes
- **Keycaps**: Some cheap blanks

## Guides and docs
Official corne choc docs: [github docs](https://github.com/foostan/crkbd/tree/main/docs/corne-chocolate)

Build Guide inspiration (V1 keycaps, no Hotswap): [Choc Spaced Corne Keyboard - Wireless](https://github.com/rafaeldelboni/buildlogs/blob/main/crkbd-choc-spaced-switch.md)

Blog with Chocoflan board: [some dudes blog](https://sascha.sh/posts/i-built-another-mechanical-keyboard/)

### MicroController

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
[Kailh Choc Switch Impressions](https://www.youtube.com/watch?v=mxUqfPf_1B0)
[Kailh Choc V2 Red Low-Profile Sound Test](https://www.youtube.com/watch?v=VXPfzeLmQ5g)
I think Red makes sense, most similar to my laptop, I don't like loud keyboards. idk. 
### Keycaps
[3d Print them myself?](https://www.printables.com/model/1066117-choc-louder-keycaps-choc-and-mx-spacing/files)
Low profile and choc spaced
[3d Resin printed](https://www.thingiverse.com/thing:4862025)

### Case 
[Nice slim look](https://www.printables.com/model/416378-wireless-corne-case)

[chocoflan case](https://www.printables.com/model/1020389-wireless-corne-chocoflan-minimal-keyboard-case/files)

# Rough BOM 

### Electrical Parts

|Part| Specific Part | Link | QTY | Cost | Notes |
| --- | ---          | ---  | --- | --- | --- | 
|MicroController|  Supermini nRF52840  |     |  2   |  86 (plus shipping and tax)   |   Cheap alternative to the Nice!Nano  |
|MicroController headers|     |  [aliexpress](https://www.aliexpress.com/item/32896689725.html?spm=a2g0o.cart.0.0.105238dah5uKsy&mp=1&pdp_npi=5%40dis%21ZAR%21ZAR%20165.63%21ZAR%2072.58%21%21ZAR%2072.58%21%21%21%40211b6c1917566326860124625e79d0%2112000045923311097%21ct%21ZA%214710544376%21%211%210)   | 10*40pin = 400pins    |  72   |     |
|PCB|  corne chocoflan    |  [repo](https://github.com/ergomechstore/Corne-chocoflan?tab=readme-ov-file)    |  5 pairs    |   600?  |     |
|Switches|  Kailh Choc V2 Low Profile - White Rain  | [aliexpress](https://www.aliexpress.com/item/1005009022408681.html?spm=a2g0o.cart.0.0.105238da7Wqxwy&mp=1&pdp_npi=5%40dis%21ZAR%21ZAR%20837.45%21ZAR%20644.84%21%21ZAR%20644.84%21%21%21%40210385bb17566390356553229eeae4%2112000047615610801%21ct%21ZA%214710544376%21%211%210)    |   90  |   750  |     |
|Switches|  Kailh Choc V2 Low Profile - Black Cloud   | [aliexpress](https://www.aliexpress.com/item/1005009022408681.html?spm=a2g0o.cart.0.0.105238da7Wqxwy&mp=1&pdp_npi=5%40dis%21ZAR%21ZAR%20837.45%21ZAR%20644.84%21%21ZAR%20644.84%21%21%21%40210385bb17566390356553229eeae4%2112000047615610807%21ct%21ZA%214710544376%21%211%210)    |   90  |  750   |     |
|Switches|  Kailh Choc V2 Low Profile - Ghost  | [aliexpress](https://www.aliexpress.com/item/1005007404357477.html?spm=a2g0o.cart.0.0.105238da7Wqxwy&mp=1&pdp_npi=5%40dis%21ZAR%21ZAR%201395.24%21ZAR%201325.48%21%21ZAR%201325.48%21%21%21%40210385bb17566390356553229eeae4%2112000040602981127%21ct%21ZA%214710544376%21%211%210)    |  90   |   1350  |     |
|Hot Swap Sockets|  Kailh Choc sockets   |   [aliexpress](https://www.aliexpress.com/item/1005008954571807.html?spm=a2g0o.cart.0.0.458738daAWVxOu&mp=1&sourceType=562&pdp_npi=5%40dis%21ZAR%21ZAR%20434.46%21ZAR%20212.89%21%21ZAR%20212.89%21%21%21%40211b6c1917566324998737892e79d0%2112000047352129245%21ct%21ZA%214710544376%21%212%210)  |   220  |  212   |     |
|Key Caps|  some cheap V2 blanks (I couldn't find PBT)   | [aliexpress](https://www.aliexpress.com/item/1005009100305250.html?spm=a2g0o.cart.0.0.105238da7Wqxwy&mp=1&pdp_npi=5%40dis%21ZAR%21ZAR%20444.18%21ZAR%20444.18%21%21ZAR%20444.18%21%21%21%40210385bb17566390356553229eeae4%2112000047915851230%21ct%21ZA%214710544376%21%212%210)    |  220   | 450    |     |
|Diodes| 1N4148W SMD diodes | [aliexpress](https://www.aliexpress.com/item/32921490945.html) |     |     |     |
|OLED display| SSD1306 | [aliexpress](https://www.aliexpress.com/item/1005008640132638.html?spm=a2g0o.cart.0.0.458738daAWVxOu&mp=1&pdp_npi=5%40dis%21ZAR%21ZAR%20352.29%21ZAR%20240.63%21%21ZAR%20240.63%21%21%21%40211b6c1917566324998737892e79d0%2112000046056501836%21ct%21ZA%214710544376%21%211%210)  |   10  |   240  |     |
| On/off switch |      |  [aliexpress](https://www.aliexpress.com/item/1005003829889015.html?spm=a2g0o.detail.0.0.6d14Az5XAz5X6H&mp=1&pdp_npi=5%40dis%21ZAR%21ZAR%20130.25%21ZAR%2074.42%21%21ZAR%2074.42%21%21%21%40211b876717566333507813224ef2ed%2112000027292033666%21ct%21ZA%214710544376%21%211%210)    |  20   |   75  |     |
|Reset Buttons| Momentery push buttons   |  [aliexpress](https://www.aliexpress.com/item/1005002201965659.html?spm=a2g0o.productlist.main.2.398f74d6NCG9Mu&algo_pvid=e2d2d9f1-23a4-4dc5-af7e-709c47e911fd&algo_exp_id=e2d2d9f1-23a4-4dc5-af7e-709c47e911fd-1&pdp_ext_f=%7B%22order%22%3A%225%22%2C%22eval%22%3A%221%22%7D&pdp_npi=6%40dis%21ZAR%2113.40%2113.21%21%21%210.72%210.71%21%402103864c17566391202706722ec892%2112000019260123904%21sea%21ZA%214710544376%21ACX%211%210%21n_tag%3A-29919%3Bd%3A54ca946f%3Bm03_new_user%3A-29894&curPageLogUid=0P5rhDvrknL9&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005002201965659%7C_p_origin_prod%3A)   | 100    |  30   |     |
|Battery|    | [DIY Electronics](https://www.diyelectronics.co.za/store/li-ion-li-po/6707-lipo-battery-37v-120mah-25x24x35mm-1c-1cell-with-ph20-connector.html?utm_campaign=google_shopping&utm_source=cpc&utm_medium=evergreen&utm_content=20485427402&gad_source=1&gad_campaignid=20489613595&gbraid=0AAAAADpm0I_3Nl-iDJVU4pgUnMGT22i95&gclid=CjwKCAjw2brFBhBOEiwAVJX5GM455BFd-ZcLSl2H0kspv53c7jLLApUWdxjkVHyDToH3SXGaemceBBoC-U8QAvD_BwE)    |     |   2  |  68   |

### Mechanical Parts
Defined based off what type of PCB I order? 

|Part| Specific Part | Link | QTY | Cost | Notes |
| --- | --- | --- | --- | --- | --- | 
| Case |    |     |     |     |     |
| top Plate|    |     |     |     |     |
|Switch Plate|    |     |     |     |     |
|Standoffs + Screws|    |     |     |     |     |
|Threaded Inserts|    |     |     |     |     |






