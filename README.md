# Redundant Interruptible Power Supply

## Overview

This board can combine two power sources on its 4 outputs, suitable for powering single board computers. Besides
that, a controller can turn off each input power for each output power port. This enables to withdraw power from
a port if both input supplies are turned off. The PS can function with only one input as well, then half of the
board is operational.

## Main goals

One goal of the board is to provide redundant power supply on output ports even without controllers.
The controller might be used for cases, when one wants for example reset it's sbc with withdrawing power
from it. With this PS, it can be achieved.

## Controller protocol

Controllers can be accessed via I2C, each controller might have a different ID. Controllers may be chained
with on-board jumpers, or accessed directly using direct ports.
Controller software swill to be written...

