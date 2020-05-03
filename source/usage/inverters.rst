Inverters
=========

.. toctree::
   :maxdepth: 3

The Inverter page displays the characteristics of the Inverter model. A database of inverters with predefined
specifications from different manufacturers is given here. The database allows you to choose an inverter from a list
of commercially-available inverters.

Name, CEC Efficiency, European Efficiency, Maximum AC Power, Maximum DC Power, Operating Power Consumption, Night
Power Consumption, Minimum MPPT DC Voltage, Nominal DC Voltage, Maximum MPPT DC Voltage are the parameters for which
the user can search the database.

According to the specification the selected inverter has some predefined parameters that can also be adjusted and
modified by some of the user requirements and based on the type of inverter used in the system being analyzed. Only
parameters from the database can be changed from basic. If there is a need for a specification of a component that
does not exist in the database the client should contact us and we will enter it.

**Inverter name** that describes the inverter of the appropriate type and manufacturer.

**CEC Efficiency/European Efficiency**– These types of efficiency are ‘weighted’ efficiencies, which obtained by
assigning a percentage of time the inverter resides in a given operating range. These are useful figures because they
measure inverter performance across the range of the inverter’s capacity. Inverter efficiency is the ratio of the
usable AC output power to the sum of the DC input power and any AC input power. Efficiency changes as a function of
AC output power, DC voltage, and sometimes inverter temperature. The difference between European and CEC weighted
efficiency lies in the difference in how they allocate their weights to arrive at an average efficiency.

**Number of MPPT inputs** – Number of Maximum Power Point Tracker inputs.

There are four Sandia Coefficients, C0, C1, C2, C3. They are used by the models to characterize the efficiency and operation
of the inverter more accurately. It is not needed for the basic user to know what their meaning is.

In standard parameters from datasheet there are also, Maximum AC Power, Nominal AC voltage, Maximum DC Power, Nominal
DC voltage, Maximum DC voltage, Maximum DC current, Minimum MPPT DC voltage, Maximum MPPT DC voltage, Power
consumption during operation and Power consumption at night.

These parameters are standard which are specified in the inverter specification itself and only the corresponding
inverter used should be selected here and check that the parameters correspond to those stated herein taken from the
base.







