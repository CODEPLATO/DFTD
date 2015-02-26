Charger
====

Components:

1. Lithium Ion (7V 150mAH)
2. Charging Chip

![chipSchematic](./ChipSchematic.png =50x50)

## Outputs

PROG(Pin 2): Constant Charge Current Setting and Charge Current Monitor Pin charge
current is set by connecting a resistor RISET from this pin to GND. When in precharge mode, the
ISET pin’s voltage is regulated to 0.2V. When in constant charge current mode, the ISET pin’s
voltage is regulated to 2V.In all modes during charging, the voltage on ISET pin can be used to
measure the charge current as follows:

I(Bat) = V(Prog) / R(Prog)

| Symbol     | Description     | MIN | TYP | MAX |
| ----       | ---             | --- | --- | --- |
| **I**(Bat) | BAT Pin Current | 450 | 500 | 550 |
| V(Prog)    |                 |     |     |     |

