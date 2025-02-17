# Rhymestone

![rhymestone](https://boardsource.imgix.net/0968c21e-ed0c-47ec-ae5e-511ec6eb3bd2.jpg?raw=true)

The Rhymestone is 40-key ortholinear split keyboard. Originally the Rhymestone
was created to be sold alongside the Treadstone and used as either a Macro pad
or a 10-key numpad, hence the similar naming conventions. However; the
Rhymestone is also often used as a standalone split keyboard by people who
prefer a 5 column ortholinear layout.

Retailers (USA)  
[Boardsource](https://boardsource.xyz/store/5ecb6aee86879c9a0c22da89)  

Extensions enabled by default  
- [Layers](/docs/layers.md) Need more keys than switches? Use layers.
- [BLE_Split](/docs/split_keyboards.md) Connects halves without wires
- [ModTap](/docs/modtap.md) Allows mod keys to act as different keys when tapped.

Common Extensions
- [Split](/docs/split_keyboards.md) Connects halves using a wire
- [Power](/docs/power.md) Powersaving features for battery life

## Microcontroller support

Update this line in `kb.py` to any supported microcontroller in `kmk/quickpin/pro_micro`:

```python
from kmk.quickpin.pro_micro.boardsource_blok import pinout as pins
```
