Shading and Losses
==================
.. toctree::
   :maxdepth: 3

The shading and losses are an important and inevitable part. The analysis would have a completely different view if
the system were considered without taking into account losses. That would mean that the system works in ideal
conditions.

At this point we have the complete documentation of the system, so it can be analyzed and the next step is a review
of the data obtained.

In order to define the exact shadings and losses, it is necessary to know the basic setting parameters, such as
Module orientation, Number of modules alongside of row, Number of modules along bottom of row, Total land area of the
system, Location area.

In the parameter calculation section, the layout and dimensions of the modules are defined. The picture in the
software itself when filling in this section describes all the parameters that need to be entered. The following are
the most important components of the system. Losses in the system are one of the essential components of system
operation.


**Shade**- This is the loss of irradiance caused by shading. Trees, obstructions, walls/roofs, and other modules can
cast shade on an array and reduce the overall irradiance.

**DC Losses** - represent energy lost on the DC side of the system (losses before the inverter) and are applied to the DC
output of each module or string. These losses relate to modules, strings, and wiring.

**Module Mismatch** - Two modules of the same type from the same manufacturer are not perfectly identical;
manufacturing variation leads to small variation in the electrical parameters of the modules. This loss represents
these manufacturing variations. It is not applied for designs using micro inverters or DC optimizers, because these
module­ level power electronics isolate the modules from one another.

**Diodes and Connections** - This is the loss due to internal wiring and soldering inside solar panels. The internal
connections add electrical resistance to the circuit, which results in power loss.

**DC wiring** - This is the loss due to the wiring that connects solar panels together in strings. The cabling adds
electrical resistance to the circuit, which results in power loss.

**Nameplate** - This is the same as the module nameplate rating loss in the system loss settings, representing the
loss due to inaccurate specification of a module. It is sometimes referred to as “power tolerance”.

**AC Losses** - This category includes all losses that occur on the output side of the inverter.

**Wiring losses (AC network)**consist of ohmic losses of the AC network on account of the medium voltage network
connecting the inverter cabinets. This loss can be precisely assessed if a detailed electrical design is made
available.

**Transformer losses**may be due to the fact that the transformer can only be precisely assessed with more
information on the transformer or during the eventual technical due diligence process for the project.

This defines the section of system shading and losses.
With all the completed parameters and configurations the client can consider the software report.

