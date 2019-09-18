# Interruptible Power Supply

## Overview

This board is an interruptible power supply, mainly for powering small board computers. It divides it input to four output channels.
And also, provides the ability to interrupt power source on an output, via the controller.

## Main goals

One goal of the board is to provide power supply on output ports even without controllers.
The controller might be used for cases, when one wants for example reset it's sbc by withdrawing power
from it. With this board, it can be achieved.

## Controller protocol

Controllers can be accessed via I2C, each controller might have a different ID. Controllers boards may be chained to
appear on one bus.

Controller software still to be written...

